[16,21,11,8,12,22]  Merge Sort
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Merge Sort Aşamaları

Dizi

16,21,11,8,12,22

Bölme

16,21,11,8,12,22 – 16,21,11 ve 8,12,22
16,21,11 – 16 ve 21,11 – 21 ve 11
8,12,22 – 8 ve 12,22 – 12,22

Birleştirme

21 ve 11  - 11,21 
16 ve 11,21 – 11,16,21
12 ve 22 – 8,12,22
11,16,21 ve 8,12,22 – 8,11,12,16,21,22

Sonuç 
8,11,12,16,21,22

Big-O Gösterimi
O(n log n)