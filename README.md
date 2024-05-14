Insertion Sort Aşamaları ve Big-O Gösterimi
Verilen dizi: [22, 27, 16, 2, 18, 6]

Insertion Sort'un adımlarını aşağıdaki gibi yapabiliriz:

İlk eleman (22) zaten sıralı kabul edilir: [22, 27, 16, 2, 18, 6]
27'yi doğru yere yerleştir: [22, 27, 16, 2, 18, 6] 
16'yı doğru yere yerleştir: [16, 22, 27, 2, 18, 6]
2'yi doğru yere yerleştir: [2, 16, 22, 27, 18, 6]
18'i doğru yere yerleştir: [2, 16, 18, 22, 27, 6]
6'yı doğru yere yerleştir: [2, 6, 16, 18, 22, 27]

<---------------------------------------------->

Big-O gösterimi (Insertion Sort):
Time Complexity: 18 Sayısının Durumu
Dizi sıralandıktan sonra 18 sayısının durumu:

Ortalama durum (Average case): Aradığımız sayının ortada olması.
Sıralı dizimizde [2, 6, 16, 18, 22, 27], 18 ortada bulunmaktadır.
Bu durumda 18 sayısı average case kapsamına girer.

<----------------------------------------------->

Selection Sort İlk 4 Adım
Verilen dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

Selection Sort'un ilk 4 adımını:

1. Adım:
En küçük elemanı bul: 2
2 ile ilk elemanı yer değiştir: [2, 3, 5, 8, 7, 9, 4, 15, 6]

2. Adım:
Geriye kalan dizideki en küçük elemanı bul: 3
3 zaten doğru yerde: [2, 3, 5, 8, 7, 9, 4, 15, 6]

3. Adım:
Geriye kalan dizideki en küçük elemanı bul: 4
4 ile 5'i yer değiştir: [2, 3, 4, 8, 7, 9, 5, 15, 6]

4. Adım:
Geriye kalan dizideki en küçük elemanı bul: 5
5 ile 8'i yer değiştir: [2, 3, 4, 5, 7, 9, 8, 15, 6]
