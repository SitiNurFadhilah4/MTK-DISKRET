---
title: Deretan

---

## Deretan

### Pengertian deret 
Deret adalah penjumlahan dari suku-suku suatu barisan. Ada dua jenis utama deret yang sering dibahas, yaitu deret aritmatika dan deret geometri.

#### Deret Aritmatika

Merupakan penjumlahan suku-suku dari barisan aritmatika, di mana setiap suku bertambah atau berkurang dengan nilai yang sama (beda,𝑑).

* Rumus Suku ke-n Barisan Aritmatika:
 
$U_n = U_1 + (n-1) \cdot d$

Di mana:
𝑈𝑛: Suku ke-n
𝑈1: Suku pertama
𝑑: Beda antar suku
𝑛: Nomor suku

* Rumus Jumlah n Suku Pertama Deret Aritmatika:

$S_n = \frac{n}{2} \cdot (U_1 + U_n)$
Atau:
$S_n = \frac{n}{2} \cdot [2U_1 + (n-1)d]$

Contoh: barisan 2,5,8,11...
Penyelesaian:
$U_1 = 2, \quad d = 3$

Suku ke-4:$U_4 = 2 + (4 - 1) \cdot 3 = 11$

Jumlah 4 suku pertama:$S_4 = \frac{4}{2} \cdot (2 + 11) = 26$

#### Deret Geometri 

Merupakan penjumlahan suku-suku dari barisan geometri, di mana setiap suku diperoleh dengan mengalikan suku sebelumnya dengan rasio tetap (rasio,𝑟).

* Rumus Suku ke-n Barisan Geometri:
$U_n = U_1 \cdot r^{n-1}$

* Rumus Jumlah n Suku Pertama Deret Geometri: jika $r \neq 1$

$S_n = U_1 \cdot \frac{1 - r^n}{1 - r}$

Jika r=1:
$S_n = n \cdot U_1$

* rumus Jumlah Deret Tak Hingga (|r| < 1):
$S_\infty = \frac{U_1}{1 - r}$

Contoh: Barisan 3,6,12,24,...
Penyelesaian:
$U_1 = 3, \quad r = 2$

Suku ke-4:$U_4 = 3 \cdot 2^{4-1} = 24$

Jumlah 4 suku pertama:$S_4 = 3 \cdot \frac{1 - 2^4}{1 - 2} = 45$


## Rekursi

### Pengertian rekursi
Rekursi adalah cara mendefinisikan suatu fungsi atau barisan dengan mendasarkan suatu suku pada suku sebelumnya.

* Sifat Rekursi
Rekursi biasanya terdiri dari:
Basis: Nilai awal yang didefinisikan secara eksplisit.
Rumus Rekurens: Relasi antara suku-suku barisan.

Contoh Rekursi Barisan Aritmatika:
$U_n = U_{n-1} + d \quad \text{dengan basis: } U_1$
Penyelesaian:
$U_1 = 2, \quad r = 3$

Suku ke-2:
$U_2 = U_1 \cdot 3 = 6$

Suku ke-3:
$U_3 = U_2 \cdot 3 = 18$

Contoh Rekursi Barisan Geometri:$U_n = U_{n-1} \cdot r \quad \text{dengan basis: } U_1$
Penyelesaian:
$U_1 = 2, \quad r = 3$

Suku ke-2:
$U_2 = U_1 \cdot 3 = 6$

Suku ke-3:
$U_3 = U_2 \cdot 3 = 18$

#### Rekursi dalam Pemrograman

Rekursi juga digunakan dalam algoritma untuk menyelesaikan masalah dengan memanggil dirinya sendiri.
* Contoh Rekursi Faktorial:
$n! = n \cdot (n-1)!$

Dengan basis: 0!=1

* Contoh Rekursi Deret Fibonacci:
$F_n = F_{n-1} + F_{n-2} \quad \text{dengan basis: } F_1 = 1, \, F_2 = 1$

* Hubungan Deret dan Rekursi
Deret sering kali dapat dirumuskan menggunakan rekursi. Sebagai contoh:

Barisan aritmatika:
$$
U_n = U_{n-1} + d
$$

Barisan geometri:
$$
U_n = U_{n-1} \cdot r
$$

Rekursi memberikan cara untuk mendefinisikan atau menghitung suku-suku deret tanpa menggunakan rumus eksplisit.

