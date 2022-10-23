# Kodluyoruz
**[22,27,16,2,18,6]**-> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

insertion sort dizinin tüm elemanlarını tek tek inceleyerek sıralama yapar dolayısıyla

[**22,27,16,2,18,6**]

[**2,27,16,22,18,6**] (2 en küçük değer olduğu için 22 ile yer değiştirdi)

[**2,6,16,22,18,27**] (daha sonra 6 ve 27’nin yerini değiştirdi, 16’dan  daha küçük olmadığı için bir sonraki sayıya geçti)

[**2,6,16,18,22,27**] (18 ve 22’nin yerini değiştirdikten sonra kontrol etti ve çıktıyı son haliyle verdi)

2. Big-O gösterimini yazınız.

Genellikle sıralama (sorting) algoritmalarında bu O(n^2) görülür. çünkü iç içe for döngüleri kurulur ve bu for döngülerinde if operasyonu ile karşılaştırma yapılır.

3.Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

best case: dizinin zaten sıralı verilmesidir, average case: karışık verilmesidir, worst case: dizinin tam tersi sırlanmasıdır.

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

average case kapsamına girer çünkü 18 değeri ortalarda bir yerlere denk gelmektedir (4.eleman)

**[7,3,5,8,2,9,4,15,6**] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1.adım **[2,3,5,8,7,9,4,15,6**]

2.adım **[2,3,5,8,7,9,4,15,6**]

3.adım **[2,3,4,8,7,9,5,15,6**]

4.adım **[2,3,4,5,7,9,8,15,6**]
