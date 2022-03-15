# PatikaDevVeriYapilariVeAlgoritmaProjesi

### Insertion Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[22,27,16,2,18,6] 
[2,22,27,16,18,6]
[2,6,22,27,16,18]
[2,6,16,22,27,18]
[2,6,16,18,22,27]

Big-O gösterimini yazınız.
n+(n-1)+(n-2)+...+1 ---> O(n^2)

Time Complexity: 
Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması, 
Best case: Aradığımız sayının dizinin en başında olması. Bu durumda 
Average Case=n/2=3-4
Worst Case= n=6
Best Case= 1 işlem

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

3-4 aralığında olduğu için average case

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


[2,7,3,5,8,9,4,15,6] 
[2,3,7,5,8,9,4,15,6]
[2,3,5,7,8,9,4,15,6]
[2,3,5,7,6,8,9,4,15]
