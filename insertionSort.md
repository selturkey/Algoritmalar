# Insertion Sort Proje 1
[22,27,16,2,18,6] -> Insertion Sort

## 1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

- Step (1) minIntegar=2 -> swap 2 and 22 -> [2, | 27, 16, 22, 18, 6]
- Step (2) minIntegar=6 -> swap 27 and 6 -> [2, 6, | 16, 22, 18, 27]
- Step (3) minIntegar=16 -> no need to swap -> [2, 6, 16, | 22, 18, 27]
- Step (4) minIntegar=18 -> swap 18 and 22 -> [2, 6 16 18 ,22, 27]
------------------

## 2) Big-O gösterimini yazınız.

* Step 1 -> n
* Step 2 -> n-1
* Step 3 -> n-2
* .... Contunie untill one element
* Step n-1 -> 1
* sum = n+(n-1)+(n-2)+ ... + 1
### Result  (n*(n+1))/2 => 0(n^2)
-------------------------------
## 3) Dizi Siralandiktan sonra 18 Sayisi hangi kapsama girer ?
- Avarage Case

-----------------------
## 4) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı

- Step (1) minIntegar=2 -> swap 7 and 2 -> [2, | 3, 5, 8, 7, 9, 4, 15, 6]
- Step (2) minIntegar=3 -> no need to swap [2, 3, | 5, 8, 7, 9, 4, 15, 6]
- Step (3) minIntegar=4 -> swap 5 and 4 -> [2, 3, 4, | 8, 7, 9, 5, 15, 6]
- Step (4) minIntegar=5 -> swap 8 and 5 -> [2, 3, 4, 5, | 7, 9, 8, 15, 6]
degisti 