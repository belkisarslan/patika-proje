# Binary Search Tree
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree

Dizimizin ilk rakamı olan 7'yi root olarak kabul ederek ortaya yerleştiriyoruz. İkinci rakamımız 5 7'den küçük olduğu için soluna yerleştiriyoruz.
```
                         [7]
                 [5]
```
Sonra gelen 1 7'den küçük mü? Evet. Bir basamak kaydırıyoruz. 5'ten küçük mü? Evet. 5'in soluna yerleştiriyoruz.
```
                         [7]
                 [5]
            [1]
```
Sonra gelen 8 7'den büyük olduğu için sağına yerleştiriyoruz.
```
                         [7]
                 [5]            [8]
            [1]
```
Sonra gelen 3 7'den küçük, 5'ten küçük, 1'den büyük olduğu için 1'in sağına yerleştiriyoruz. Sonra gelen 6 7'den küçük, 5'ten büyük 5'in sağına yerleştiriyoruz. Sonra gelen sıfır adım adım ilerlediğimizde 1'in soluna yerleşiyor.

Bu şekilde devam ettiğimizde çıkan sonuç:
```
                         [7]
                 [5]           [8]
        [1]           [6]             [9]
 [0]          [3]
         [2]      [4]
```