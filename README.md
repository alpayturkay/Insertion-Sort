# Insertion-Sort
Patika Insertion Sort Project

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Cevap:

1.Insertion Sort
En basit sorting algoritmalarından biridir.
Verilen diziden en küçük elemanı bulup en baştaki ile yer değiştiriyor ve bu işlem tüm sayılarda en büyükten en küçüğe olacak şekilde tekrarlanıyor.
Buna göre:

[22|27,16,2,18,6]
[22,27|16,2,18,6]
[16,22,27|2,18,6]
[2,16,22,27|18,6]
[2,16,18,22,27|6]
[2,6,16,18,22,27]

2. Big-O gösterimini yazınız. 
Big-O (n²)

3. Time Complexity:

Average case: O(n^2)
Worst case: O(n^2)
Best case: O(n)

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıkan sonra:
[2,6,16,18,22,27]  18 sayısı average case kapsamına girer.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Başlangıç: [7,3,5,8,2,9,4,15,6]
1.aşama:   [2,3,5,8,7,9,4,15,6] 
2.aşama:   [2,3,4,8,7,9,5,15,6] 
3.aşama:   [2,3,4,5,7,9,8,15,6] 
4.aşama:   [2,3,4,5,6,9,8,15,7]



