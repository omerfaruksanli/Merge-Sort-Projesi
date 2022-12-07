# Merge-Sort-Projesi

16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.

Çözüm:

Merge Sort algoritmasında sıralı olmayan diziyi ortadan eşit olarak iki alt diziye ayırırız. Bu ayırma işlemi, alt diziler en çok iki elemanlı olana kadar devam eder. Alt dizileri kendi içinde sıralar. Sıralı iki alt diziyi tek bir sıralı dizi olacak şekilde birleştirir. Yani şemamız şu şekilde olur;

[16,21,11] [8,12,22]

[16] , [21,11] , [8,12] , [22]

[16] , [21] , [11] , [8] , [12] , [22]

[16] , [11,22] , [8,12] , [22]

[11,22,16] , [8,12,22]

[8,11,12,16,22]

Big-O gösterimi;

Birleştirme sıralaması her zaman diziyi ikiye böldüğünden ve iki yarıyı birleştirmek için doğrusal zaman aldığından, Birleştirme Sıralamasının zaman karmaşıklığı 3 durumda da (Worst, Average ve Best) O(n*Log n)'dir.
