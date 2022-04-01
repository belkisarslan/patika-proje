# Merge Sort

1- [16,21,11,8,12,22] -> Merge Sort
```
[16 21 11] [8 12 22]
[16 21] [11] [8 12] [22]
[16] [21] [11] [8] [12] [22]
[16 21] [11] [8 12] [22]
[11 16 21] [8 12 22]
[8 11 12 16 21 22]
```

2- Big-O gösterimi
<br>
İşlemimiz her defasında yarıya indiği için
```
2^x=n 
logn=x
O(nlogn)
```
Patika link: https://app.patika.dev/belkisarslan