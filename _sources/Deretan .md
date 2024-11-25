---
title: Deretan

---

## Deretan dan Rekursi

### deretan
deratan (sequence) adalah suatu urutan atau susunan elemen atau objek yang disusun secara teratur berdasarkan suatu aturan tertentu. Elemen dalam deretan biasanya berupa angka, huruf, simbol, atau objek lainnya, dan urutannya dapat didasarkan pada pola, nilai, atau hubungan tertentu
Definisi: Sebuah deretan adalah fungsi dari subset suatu himpunan bilangan bulat (biasanya N atau P) ke sebuah himpunan S.

   N = {1, 2, 3, 4, … }
   S misalnya {2, 4, 6, 8, …},   {1/3, 1/5, 1/7, …},  dsb

Notasi deretan: {an}
Deretan umumnya dinyatakan dalam suatu formula, misalnya:
	an = 2n
	an = 1/n
	an = 7 – 3n
Dalam konteks matematika, deretan sering merujuk pada barisan bilangan, yaitu kumpulan bilangan yang disusun dalam suatu pola tertentu.
 Misalnya:
Deretan bilangan ganjil: 1,3,5,7,…
Deretan bilangan genap: 2,4,6,8,…
Deretan bilangan yang membentuk deret aritmetika: 3,6,9,12....

Contoh-contoh deretan dan formulanya:

#### Deret Aritmetika
Deret dengan pola kenaikan atau penurunan tetap.
Contoh: 2,5,8,11,14,…
Rumus suku ke-n: 𝑈𝑛=𝑎+(𝑛−1)⋅𝑏 
Di mana:
- 𝑎: suku pertama 
- 𝑏: beda (selisih antar suku)
- 𝑛: nomor suku yang dicari

#### Deret Geometri
Deret dengan pola kelipatan tetap.
Contoh: 3,6,12,24,48,…
Rumus suku ke-n: 𝑈𝑛=𝑎⋅𝑟^((𝑛−1) )
Di mana:
- 𝑎: suku pertama 
- 𝑟: rasio (perbandingan antar suku)
- 𝑛: nomor suku yang dicari

#### Deret Bilangan Kuadrat
Deret dengan pola nilai berupa kuadrat bilangan bulat.
- Contoh: 1,4,9,16,25,…
- Rumus suku ke-n: 𝑈𝑛=𝑛^2

#### Deret Bilangan Kubik
Deret dengan pola nilai berupa kubik bilangan bulat.
- Contoh: 1,8,27,64,125,…
- - Rumus suku ke-n: 𝑈𝑛=𝑛^3

#### Deret Fibonacci
Deret dengan pola di mana setiap suku merupakan jumlah dua suku sebelumnya.
- Contoh: 0,1,1,2,3,5,8,…
- Rumus suku ke-n (rekursif): 𝐹_𝑛=𝐹_(𝑛−1)+𝐹_(𝑛−2),𝐹_0=0,𝐹_1=1

#### Penjumlahan deretan 
Jumlah deretan 
	am, am+1, am+2, …, an
  adalah
	 am + am+1 + am+2 + … + an
  atau dalam notasi sumasi:
	![matdis](https://hackmd.io/_uploads/Byw5EflQJe.jpg)
    
k adalah indeks summasi, 
m adalah batas bawah indeks,
n adalah batas atas indeks


Contoh 2: Berapa nilai ![matdis2](https://hackmd.io/_uploads/S12PHGxXJx.jpg)

Jawaban: 
	![matdis2.](https://hackmd.io/_uploads/HkVgLGl7kl.jpg)
= 12 + 22 + 32 + 42 + 52 = 1 + 4 + 9 + 16 + 25 = 55

Contoh 3: Batas bawah sumasi kadangkala perlu digeser agar dapat dijumlahkan dengan sumasi lain yang memiliki batas bawah berbeda. Pada contoh 2 di atas batas bawah digeser dari 1 menjadi 0, akibatnya:
	 ![matdis2.](https://hackmd.io/_uploads/rJbFIfe7Jg.jpg) ![matdis3](https://hackmd.io/_uploads/rJ0gvfeX1l.jpg)

Contoh 4: Sumasi dapat dipecah dengan membagi dua indeksnya, misalnya
![matdis4](https://hackmd.io/_uploads/SJ6w_fx7yx.jpg) ![matdis5](https://hackmd.io/_uploads/SkGC_fg71l.jpg)

TUGAS PEMBUKTIAN Dari 3 rumus dibawah
Beberapa sumasi sudah ditemukan rumus penjumlahannya sebagai berikut:

![image](https://hackmd.io/_uploads/ryt8vflX1e.png) (deret geometri) (deret aritmetika)

Contoh 5: Hitung nilai ![matdis6](https://hackmd.io/_uploads/HkjLFzgmJe.jpg)
Jawaban:
![matdis7](https://hackmd.io/_uploads/B1O5YGg7Jg.jpg)

Gunakan rumus ![image](https://hackmd.io/_uploads/S1s6YGeXkl.png) ![image](https://hackmd.io/_uploads/BJglqGxXyl.png) ![image](https://hackmd.io/_uploads/r1jm5GlQJe.png)
![matdis8](https://hackmd.io/_uploads/SyMDcfx7yl.jpg)

### Sumasi ganda
Di dalam algoritma, kita perlu menghitung berapa kali suatu operasi tertentu dilakukan di dalam sebuah kalang bersarang (nested loop). Penjumlahan semua operasi di dalam kalang bersarang dinyatakan dalam bentuk sumasi ganda.
Contoh: ![matdis9](https://hackmd.io/_uploads/HJxMszgQJe.jpg)
Untuk menghitung sumasi ganda, mula-mula ekspansi sumasi terdalam, lalu  dilanjukan dengan sumasi terluar:

![matdis10](https://hackmd.io/_uploads/HyDOjMe7kx.jpg)

Contoh penggunaan: Berapa kali operasi + dilakukan di dalam algoritma di bawah ini? 
x = 0
for j = 1 to 10 do
    for k = 1 to j do
           x = x + 2
   end for
end for 
Penyelesaian:
Operasi + terdapat di dalam pernyataan x = x + 2
Operasi ini dilakukan satu kali pada setiap pengulangan
Jumlah seluruh operasi + adalah:
![matdisi11](https://hackmd.io/_uploads/Sy7ZnGxmkl.jpg)

## Rekursi
* Sebuah objek dikatakan rekursif  (recursive) jika ia didefinisikan dalam terminologi dirinya sendiri. 
* Proses mendefinisikan objek dalam terminologi dirinya sendiri disebut rekursi (recursion).
* Perhatikan tiga buah gambar pada tiga slide berikut ini.

Objek fraktal  adalah contoh bentuk rekursif.
![image](https://hackmd.io/_uploads/H1GonGxmkl.png) ![image](https://hackmd.io/_uploads/ByN33zem1g.png)


#### fungsi rekursif

Fungsi rekursif didefinisikan oleh dua bagian:
 (i)  Basis 
Bagian yang berisi nilai fungsi yang terdefinisi secara eksplisit. 
Bagian ini juga sekaligus menghentikan rekursif (dan memberikan sebuah nilai yang terdefinisi pada fungsi rekursif).
 
 (ii)  Rekurens
Bagian ini mendefinisikan fungsi dalam terminologi dirinya sendiri. 
Berisi kaidah untuk menemukan nilai fungsi pada suatu input dari nilai-nilai lainnya pada input yang lebih kecil. 

Contoh 6:  Misalkan f didefinsikan secara rekusif sbb
![image](https://hackmd.io/_uploads/r18h6Mg7yx.png)
Tentukan nilai f(4)!

![matdis112](https://hackmd.io/_uploads/BJaVAfxXkl.jpg)

Contoh 7: Nyatakan n! dalam definisi rekursif
Solusi:![image](https://hackmd.io/_uploads/rJLTwmgmkg.png)
Misalkan f(n) = n!, maka ![image](https://hackmd.io/_uploads/SJhZdXl71g.png)

![matdis13](https://hackmd.io/_uploads/Hk9PdXgQJl.jpg)

![matdis14](https://hackmd.io/_uploads/ByMy5Qgm1x.jpg)
![matdsi15](https://hackmd.io/_uploads/r1Yz5me71e.jpg)

Contoh 8: Barisan Fibonacci  0, 1, 1, 2, 3, 5, 8, 11, 19, …. Dapat dinyatakan secara rekursif sebagai berikut:

![image](https://hackmd.io/_uploads/S1iO5QeQJg.png)

Contoh 9: Fungsi (polinom) Chebyshev dinyatakan sebagai
![image](https://hackmd.io/_uploads/ByncqQemye.png)

Latihan
	1. Definisikan an secara rekursif , yang dalam hal ini a adalah bilangan riil tidak-nol dan n adalah bilangan bulat tidak-negatif.
penyeleasaian:
![image](https://hackmd.io/_uploads/rJOMsmeXJe.png)

sehingga:
![image](https://hackmd.io/_uploads/HJxBiXl7Je.png)

2. Nyatakan a x b secara rekursif, yang dalam hal ini a dan b adalah bilangan bulat positif.
penyelesaian: 
![image](https://hackmd.io/_uploads/rkivoXx71x.png)
![image](https://hackmd.io/_uploads/HJ2asmxXyx.png)
![image](https://hackmd.io/_uploads/r1aRo7gmkl.png)

#### Struktur Rekursif
Struktur data yang penting dalam komputer adalah pohon biner (binary tree). 

![image](https://hackmd.io/_uploads/H1WfhmxXke.png)

* Simpul (node) pada pohon biner mempunyai paling banyak dua buah anak.
* Jumlah anak pada setiap simpul bisa 1, 2, atau 0.
* Simpul yang mempunyai anak disebut simpul cabang (branch node) atau simpul dalam (internal node)
* Simpul yang tidak mempunyai anak disebut simpul daun (leave).
* Pohon biner adalah struktur yang rekursif, sebab setiap simpul mempunyai cabang yang juga berupa pohon. Setiap cabang disebut  upapohon (subtree).

![image](https://hackmd.io/_uploads/HJIOhQxmkl.png)
Oleh karena itu, pohon dapat didefinisikan secara rekursif sebagari berikut:

(i) Basis: kosong adalah pohon biner
(ii) Rekurens: Jika T1 dan T2 adalah pohon biner, maka 
          adalah pohon biner
T1       T2   ![image](https://hackmd.io/_uploads/rJPba7gQke.png)![image](https://hackmd.io/_uploads/H16f6QxX1e.png)

Proses pembentukan pohon biner secara rekursif:
![matdis16](https://hackmd.io/_uploads/SyzjTQlX1x.jpg)
(ii) ![image](https://hackmd.io/_uploads/HySAp7gmJe.png)


				         	    