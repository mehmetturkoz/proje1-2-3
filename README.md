# Veri Yapıları Ve Algortmalar Projeleri

[www.patika.dev](https://www.patika.dev/tr)

## PROJE 1 (Insertion Sort)
```
[22,27,16,2,18,6] -> Insertion Sort

[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
```

Big-O gösterimi : O(n^2)

TIME COMPLEXITY:
Worst Case: O(n^2)
Avarage Case : O(n^2)
Best Case : O(n)

18 sayısı ortada olduğu için avarage case kapsamına girer.

```
[7,3,5,8,2,9,4,15,6] 

[2,3,5,8,7,9,4,15,6] - 1
[2,3,4,8,7,9,5,15,6] - 2
[2,3,4,5,7,9,8,15,6] - 3
[2,3,4,5,6,9,8,15,7] - 4
```

# PROJE 2 (Merge Sort)

 
```
         [16,21,11,8,12,22]
       [16,21,11]        [8,12,22]
    [16]    [21,11]     [8]    [12,22]
    [16]   [21] [11]    [8]    [12] [22]
     [16]    [11,21]     [8]    [12,22]
        [11,16,21]          [8,12,22]
    
        [8,11,12,16,21,22]

```

Big-O gösterimi : O(n.logn)

## PROJE 3 (Binary Search Tree)

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 

                  7 (root)
            
              5              8         
                                  9
         1         6
     0         3
            
            2      4    

