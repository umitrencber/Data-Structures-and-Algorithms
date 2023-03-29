# Project1

# İnsertion
## 22,27,16,2,18,6 -> insertion'a göre sıralıyacağız.

1.  22,16,27,2,18,6
2.  16,22,27,2,18,6
3.  16,22,2,27,18,6
4.  16,2,22,27,18,6
5.  2,16,22,27,18,6
6.  2,16,22,18,27,6
7.  2,16,18,22,27,6
8.  2,16,18,22,6,27
9.  2,16,18,6,22,27
10. 2,16,6,18,22,27
11. 2,6,16,18,22,27

* Big O Notation: O(n^2)
 
 18 -> Avarage case olur.

Best case: Aradığımız sayının dizinin en başında olması. -> o(n)
Average case: Aradığımız sayının ortada olması -> 0(n^2)
Worst case: Aradığımız sayının sonda olması -> 0(n^2)

## 7,3,5,8,2,9,4,15,6 -> selection sort'e göre sıralması

1. 2,7,3,5,8,9,4,15,6
2. 2,3,7,5,8,9,4,15,6
3. 2,3,4,7,5,8,9,14,6
4. 2,3,4,5,7,8,9,14,6
5. 2,3,4,5,6,7,8,9,14 ( son adım)

# Proje 2:



## 16,21,11,8,12,22 -> merge sort
* big nation -> O(nLogn)

1. 16,21,11          |            8,12,22
2. 16 | 21,11                     8 | 12,22
3. 16 | 11,21                     8 | 12,22
4. 11,16,21                       8,12,22 (tek parçaya ayırdı hepsini son adımda)
5. 8,11,12,16,21,22 


