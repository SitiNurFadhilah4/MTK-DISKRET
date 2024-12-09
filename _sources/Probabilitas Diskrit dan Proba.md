---
title: Probabilitas Diskrit dan Proba

---

## Probabilitas Diskrit dan Probabilitas Bayesian

### Probabilitas Diskrit

Probabilitas diskrit merujuk pada peluang dari hasil yang terpisah dalam ruang sampel diskrit, di mana setiap hasil memiliki peluang tertentu. Probabilitas ini dihitung menggunakan rumus-rumus dasar dalam teori probabilitas.

#### Pengertian Probabilitas Diskrit
Probabilitas diskrit adalah pengukuran dari kemungkinan suatu kejadian terjadi. Ini digunakan ketika kejadian-kejadian tersebut bisa dihitung atau direpresentasikan sebagai nilai diskret.

### Konsep Utama dalam Probabilitas

* Sampel ruang (Sample Space): Semua kemungkinan hasil dari suatu eksperimen. Misalnya, jika Anda melempar satu dadu, sampel ruang Anda adalah {1, 2, 3, 4, 5, 6}.
* Kejadian (Event): Suatu himpunan dari hasil yang dipilih dari sampel ruang. Misalnya, untuk melempar satu dadu, hasil genap (2, 4, 6) adalah sebuah kejadian.
* Probabilitas Kejadian: Jika P(A) adalah probabilitas kejadian A, maka P(A)=
jumlah hasil dalam sampel ruang/
jumlah hasil kejadian A

Rumus Dasar: Jika 𝑆 adalah ruang sampel diskrit dengan 𝑛 elemen dan P(A) adalah probabilitas dari kejadian A Maka: 
P(A)= 
jumlah elemen dalam S/
jumlah elemen dalam A


### Probabilitas Bayesian
Probabilitas bayesian melibatkan update probabilitas berdasarkan bukti baru. Prinsip dasarnya adalah menggunakan informasi yang relevan untuk memperbarui keyakinan kita terhadap suatu kejadian.

#### Pengertian Probabilitas Bayesian
Probabilitas bayesian adalah metode penghitungan probabilitas di mana kita memperbarui probabilitas awal 𝑃(𝐴)berdasarkan bukti 𝐵

Rumus Bayes: 


$P(H|E) = \frac{P(E|H) \cdot P(H)}{P(E)}$

Dimana:
P(H∣E): Probabilitas hipotesis 𝐻 benar setelah memperhitungkan bukti 𝐸 (posterior probability).
P(H): Probabilitas awal hipotesis 𝐻(prior probability).
P(E∣H): Probabilitas munculnya bukti 𝐸 jika hipotesis 𝐻 benar (likelihood).
P(E): Probabilitas munculnya bukti 𝐸 tanpa memperhatikan hipotesis (evidence).

contoh:
* 1% populasi menderita penyakit tertentu (𝑃(𝐻)=0.01)
* Tes medis memberikan hasil positif pada 99% orang yang sakit (𝑃(𝐸∣𝐻)=0.99)
* Tes juga memberikan hasil positif pada 5% orang sehat (𝑃(𝐸∣¬𝐻)=0.05)

Jika hasil tes seseorang positif, berapa probabilitas dia benar-benar sakit (𝑃(𝐻∣𝐸)) ?Menggunakan Teorema Bayes:

$P(H|E) = \frac{P(E|H) \cdot P(H)}{P(E|H) \cdot P(H) + P(E|\neg H) \cdot P(\neg H)}$

$P(H|E) = \frac{0.99 \cdot 0.01}{0.99 \cdot 0.01 + 0.05 \cdot 0.99} \approx 0.17$

Jadi, meskipun tes positif, probabilitas orang tersebut sakit hanya sekitar 17%.
