# project-insertion-patika.dev
[22,27,16,2,18,6] -> Insertion Sort
@patika.dev

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Answers:

1) n -> [22,27,16,2,18,6] , n-1 -> [2,27,16,22,18,6] , n-2 -> [2,6,16,22,18,27] , n-3 -> [2,6,16,22,18,27] , n-4 -> [2,6,16,18,22,27] , n-5 -> [2,6,16,18,22,27]

2) n=6, 1'den n'e kadar olan sayıların toplamı = (n*(n+1))/2 => Big O Notation = O(n^2) olur.

3)
Avarage Case: n^2
Worst Case: n^2
Best Case: n

4) Dizi sıralandıktan sonta 18 sayısı ortalarda olduğu için Average Case kapsamına girmektedir.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6], [2,3,4,8,7,9,5,15,6], [2,3,4,5,7,9,8,15,6], [2,3,4,5,6,9,8,15,7]
