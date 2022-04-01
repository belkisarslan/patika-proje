# Insertion Sort

[22,27,16,2,18,6] -> Insertion Sort

1- Dizinin insertion sort türüne göre aşamaları
```
     2 | 27 16 22 18 6
     2 6 | 16 22 18 27
     2 6 16 | 22 18 27
     2 6 16 18 | 22 27
     2 6 16 18 22 | 27
     2 6 16 18 22 27
```
2- Big-O gösterimi
İlk adımda en küçük elemanı seçtik n kadar işlem yaptık. Ardından işlemlerimiz (n-1), (n-2) şeklinde 1'e kadar devam etti.
```
n + (n-1) + (n-2) + ... + 1
n(n+1)/2
n^2+n /2
Big-O notationda domine eden fonksiyonu aldığımız için O(n^2) olacaktır.
```

3- Time Complexity
<br>
En iyi ihtimalle dizinin sıralı yada çoğunlukla sıralı gelmesi durumunda bile tüm elemanların kontrol edileceğinden time complexity n^2 dir.

4- Tek tek kontrol edeceğimiz için worst case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı
```
2 | 3 5 8 7 9 4 15 6
2 3 | 4 8 7 9 5 15 6
2 3 4 | 8 7 9 5 15 6
2 3 4 5 | 7 9 8 15 6
```
Patika link: https://app.patika.dev/belkisarslan


