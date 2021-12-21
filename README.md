# Veri-Yap-lar-ve-Algoritmalar
Patika.dev Veri Yapıları ve Algoritmalar Modülü Projeleri

# Insertion Sort

# 1)

[22,27,16,2,18,6] n

[2,27,16,22,18,6] n-1

[2,6,16,22,18,27] n-2 

[2,6,16,22,18,27] n-3 (bu adımda 16' dan itibaren tekrar gezdi fakat 16 zaten en küçük)

[2,6,16,18,22,27] n-4

[2,6,16,18,22,27] n-5 (bu adımda 22' den itibaren tekrar gezdi fakat 22 zaten en küçük)

O(n^2) = 36

Dizi sıralandıktan sonra 18 sayısı Average Case kapsamına girer. 

# 2)

[7,3,5,8,2,9,4,15,6] 

Insertion Sort algoritmasına göre ilk dört adım aşağıdaki gibidir:

1. adım: [2,3,5,8,7,9,4,15,6]
2. adım: [2,3,5,8,7,9,4,15,6]
3. adım: [2,3,4,8,7,9,5,15,6]
4. adım: [2,3,4,5,7,9,8,15,6]







# Merge Sort
[16,21,11,8,12,22]

16,21,11    |     11,8,22 

16,21 |  11   |  11,8 |  22

16 | 21 | 11   |   11 | 8 | 22

11,16,21    |    8,11,22

8,11,12,16,21,22

Time complexity: O(nlogn)

# Binary Search Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Sıralı hali : [0,1,2,3,4,5,6,7,8,9]

                                  5
                               /     \
                          2                8
                        / \               /  \
                      1    3             7    9
                     /      \           /
                    0        4         6
                       
Root 5' dir. Solunda 2, sağında 8 bulunur.
