# Proje 3 - Binary Search Tree

## 1.Soru
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## Çözüm
Root düğüm 4 olarak seçilirse:

-> 7, 4'ün sağındadır.

-> 5, 4'ün sağındadır, 7'nin solundadır.

-> 1, 4'ün solundadır.

-> 8, 4'ün sağındadır, 7'nin sağındadır.

-> 3, 4'ün solundadır, 1'in sağındadır.

-> 6, 4'ün sağındadır, 7'nin solundadır, 5'in sağındadır.

-> 0, 4'ün solundadır, 1'in solundadır.

-> 9, 4'ün sağındadır, 7'nin sağındadır, 8'in sağındadır.

-> 2, 4'ün solundadır, 1'in sağındadır, 3'ün solundadır.

          4
       /     \
      1       7
     / \     / \
    0   3   5   8
       / \   \   \
      2   4   6   9
