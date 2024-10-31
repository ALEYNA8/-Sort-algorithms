# -Sort-algorithms
1.ınsertion Sort Aşamaları:
dizi: [22,27,16,2,18,6]
1.Adım:22 ve 27 zaten sıralı,bu yüzden değişiklik yok.
2.Adım:16 yı sıralı alt diziye yerleştiririz.
[16,22,27,2,18,6]
3.Adım:2yi sıralı alt diziye yerleştiririz.
[2,16,22,27,18,6]
4.Adım: 18i sıralı alt diziye yerleştiririz
[2,16,18,22,27,6]
5.Adım: 6lı sıralı alt diziye yerleştiririz.

2.Big-o Gösterimi:
Insertion Sort'un Big-o karmaşıklığı 0(n^2)'dir. Çünkü her eleman için tüm önceki elemanlarla karşılaştırma yapılabilir.
 18 sayısı sıralanmış dizide ortada yer aldığı için AVERAGE CASE kapsamına girer.

 3.Selection Sort ile ilk 4 adımın yazma:
Başlangıç dizisi:
[7,3,5,8,2,9,4,15,6]
1.Adım:Dizideki en küçük eleman 2'dir.
 2,ilk sıraya (indeks 0) getirilir.
- [2,3,5,8,7,9,4,15,6]
2.Adım:ikinci en küçük eleman 3'tür. zaten ikinci sırada olduğu için yer değiştirmez.
  -[2,3,5,8,7,9,4,15,6]
3.Adım: Üçüncü en küçük eleman 4'tür. 4,üçüncü sıradaki 5 ile yer değiştirir.
  -[2,3,4,8,7,9,5,15,6]
4.Adım:Dördüncü en küçük eleman 5'tir. 5,dördüncü sıradaki 8 ile yer değiştirir.
  -[2,3,4,5,7,9,8,15,6]
İlk dört adımın sonunda dizi
[2,3,4,5,7,9,8,15,6] şeklini alır.
