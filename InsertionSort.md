# Proje1
[22,27,16,2,18,6] ->  **Insertion Sort**

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity:
    1. Average case: Aradığımız sayının ortada olması,
    2. Worst case: Aradığımız sayının sonda olması, 
    3. Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
---

## Insertion Sort Aşamaları

* [22, 27, 16, 2, 18, 6]
* [16, 22, 27, 2, 18, 6]
* [2, 16, 22, 27, 18, 6]
* [2, 16, 18, 22, 27, 6] 
* [2, 6, 16, 18, 22, 27] 
---
## Bıg O Notation
* 1 + (n-3) + (n-2) + (n-4) + (n-2) 
* Big-O notation : [(n.(n+1))/2] - [(n-5) + (n-1)] +(n-2)] --> O(n²)
---
## Time Complexity
* **best case**: aradığımız sayının başta olması durumu 
* **average case**: aradığımız sayının ortada olması
* **worst case**: aradığımız sayının sonda olması durumu
---
## Sıralı Array'de 18 sayısı
Average casede aradığımız sayı (18) ortada.

--- 
## Insertion Sort'a göre ilk dört adımı
[7,3,5,8,2,9,4,15,6]

1. [3,7,5,8,2,9,4,15,6]
2. [3,5,7,8,2,9,4,15,6]
3. [3,5,7,8,2,9,4,15,6]
4. [3,5,7,2,8,9,4,15,6]
---
