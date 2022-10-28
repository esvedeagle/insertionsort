# Proje 1

[22,27,16,2,18,6] >> insertion sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## Çözüm
    [22,27,16,2,18,6]
1. [2,27,16,22,18,6] (n-1)
2. [2,6,16,22,18,27] (n-2)
3. [2,6,16,18,22,27] 1

n+(n-1)+(n-2)+...+1 =
$\frac{n*(n+1)}{2}$

Big-O = O($n^{2}$)

### time complexity:
worst case; çünkü 18 en son aşamada bulundu.

---
    [7,3,5,8,2,9,4,15,6] (n)
1. [2,3,5,8,7,9,4,15,6] (n-1)
2. [2,3,4,8,7,9,5,15,6] (n-2)
3. [2,3,4,5,7,9,8,15,6] (n-3)
4. [2,3,4,5,6,9,8,15,7] (n-4)
