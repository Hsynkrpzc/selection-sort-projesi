# selection-sort-projesi

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.


    -- [22,27,16,2,18,6]
    22,27 /,16,2,18,6 
    22,27 /,16,2,18,6
    22,16,27 /,2,18,6 
    16,22,27 /,2,18,6
    16,22,2,27 /,18,6
    2,16,22,27/,18,6
    2,16,22,18,27/,6
    2,16,18,22,27,/6
    2,16,18,22,6,27
    [2,6,16,18,22,27]

Big-O gösterimini yazınız.

----
O(nlogn)
O(n)
O(logn)
n+(n-1)+(n-2)+(n-3)+...+1 = n.(n+1)/2
O(n²)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
----- Cevap   Average case:
[2,6,16,18,22,27]


Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
.



[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

2,3,5,8,7,9,4,15,6
2,3,5,8,7,9,4,15,6
2,3,4,8,7,9,5,15,6
2,3,4,5,7,9,8,15,6
2,3,4,5,6,9,8,15,7
2,3,4,5,6,7,8,15,9
2,3,4,5,6,7,8,9,15


