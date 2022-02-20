# binarySearchTree


# Proje 3 (Binary-Search-Tree)

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.



İlk eleman olan 7, ağacımızın root(kök) düğümü olarak belirlenir:

```
       (7)
```

5 değerinin eklenmesi:

```
       (7)
      /
    (5)
```

1 değerinin eklenmesi:

         (7)
        /
      (5)
      /
    (1)

8 değerinin eklenmesi:

         (7)
        /   \
      (5)   (8)
      /
    (1)

3 değerinin eklenmesi:

         (7)
        /   \
      (5)   (8)
      /
    (1)
       \
       (3)

6 değerinin eklenmesi:

         (7)
        /   \
      (5)   (8)
     /  \
    (1) (6)
       \
       (3)

0 değerinin eklenmesi:

            (7)
           /   \
         (5)   (8)
        /  \
       (1) (6)
      /  \
    (0)  (3)

9 değerinin eklenmesi:

```       (7)
        (7)
       /   \
     (5)   (8)
    /  \     \
   (1) (6)    (9)
  /  \
(0)  (3)
```

4 değerinin eklenmesi:

```
        (7)
       /   \
     (5)   (8)
    /  \     \
   (1) (6)    (9)
  /  \
(0)  (3)
        \
        (4)
```

2 değerinin eklenmesi:

 ```
        (7)
       /   \
     (5)   (8)
    /  \     \
   (1) (6)    (9)
  /  \
(0)  (3)
     /  \
   (2)  (4)
 ```

