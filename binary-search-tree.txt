Soru: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Dizi: 7,5,1,8,3,6,0,9,4,2
1.	Root: 7'dir.
2.	5: 7'den küçüktür, soluna eklenir.
3.	1: 7'den küçüktür, 5'ten de küçüktür, 5'in soluna eklenir.
4.	8: 7'den büyüktür, sağına eklenir.
5.	3: 7'den küçüktür, 5'ten küçüktür, 1'den büyüktür, 1'in sağına eklenir.
6.	6: 7'den küçüktür, 5'ten büyüktür, 5'in sağına eklenir.
7.	0: 7'den, 5'ten ve 1'den küçüktür, 1'in soluna eklenir.
8.	9: 7'den ve 8'den büyüktür, 8'in sağına eklenir.
9.	4: 7'den küçüktür, 5'ten küçüktür, 3'ten büyüktür, 3'ün sağına eklenir.
10.	2: 7'den küçüktür, 5'ten küçüktür, 1'den büyüktür, 3'ten küçüktür, 3'ün soluna eklenir.



Sonuç:
        7
       / \
      5   8
     / \   \
    1   6   9
   / \ 
  0   3
     / \
    2   4
