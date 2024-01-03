# Selection-Sort-Projesi
[22,27,16,2,18,6] -> Eklemeli Sıralama

1) Yukarı verilen dizin türüne göre aşamalarını yazınız.

- min=2 -> 2 ile 22'nin yerini değiştirin -> [2, | 27, 16, 22, 18, 6]
- min=6 -> 27 ve 6'yı değiştirin -> [2, 6, | 16, 22, 18, 27]
- min=16 -> değiştirmeye gerek yok -> [2, 6, 16, | 22, 18, 27]
- dk=18 -> 18 ve 22'yi değiştirin -> [2, 6 16 18 ,22, 27]

2) Big-O gösterimini yazın.

Adım 1 -> n
Adım 2 -> n-1
Adım 3 -> n-2
....
Adım n-1 -> 1

toplam = (n*(n-1))/2 -> O(n^2)

Zaman Karmaşıklığı: Ortalama durum: Aradığımız sayının ortada olması, En kötü durum: Aradığımız sayının sonda olması, En iyi durum: Aradığımız sayının dizinin en başında olması.
3) Dizi yapıldıktan sonra 18 sayısı hangi durum kapsamına girer? Yazınız.
En kötü durumda

4) [7,3,5,8,2,9,4,15,6] serisinin Insertion Sort'a göre ilk 4 adımını yazın.

- min=2 -> 7 ile 2'nin yerini değiştirin -> [2, | 3, 5, 8, 7, 9, 4, 15, 6]
- min=3 -> değiştirmeye gerek yok [2, 3, | 5, 8, 7, 9, 4, 15, 6]
- min=4 -> 5 ve 4'ün yerini değiştirin -> [2, 3, 4, | 8, 7, 9, 5, 15, 6]
- min=5 -> 8 ve 5'in yerini değiştirin -> [2, 3, 4, 5, | 7, 9, 8, 15, 6]
