---
title: Algoritma

---

# Algoritma
## Definisi Algoritma
Algoritma adalah sekumpulan langkah-langkah yang terstruktur dan sistematis untuk menyelesaikan suatu masalah.

### Algoritma Sequential Search

Sequential Search atau pencarian linear adalah metode pencarian di mana setiap elemen dalam suatu list diperiksa satu per satu sampai elemen yang dicari ditemukan atau sampai semua elemen telah diperiksa.

Cara menyelesaikan Sequential Search:

1. Mulai dari elemen pertama dalam list.
2. Bandingkan elemen tersebut dengan nilai yang dicari.
3. Jika ditemukan, pencarian berhenti.
4. Jika tidak, lanjutkan ke elemen berikutnya.
5. Ulangi langkah ini hingga elemen yang dicari ditemukan atau list habis.

Kelebihan dan Kekurangan:

Kelebihan: Cocok untuk list yang kecil atau tidak terurut.

Kekurangan: Memiliki waktu pencarian yang relatif lama pada list besar, karena harus memeriksa satu per satu.

Contoh soal Sequential Search :

Misalkan kita ingin mencari angka 5 dalam list [3, 5, 2, 7, 1].

Hasil:
Output akan menunjukkan indeks di mana angka 5 ditemukan, yaitu indeks ke-1.

### Algoritma Binary Search

Binary Search adalah metode pencarian yang hanya dapat diterapkan pada list yang terurut. Algoritme ini bekerja dengan cara membagi list menjadi dua bagian secara berulang hingga menemukan elemen yang dicari.

Cara menyelesaikan Binary Search:

1. Tentukan nilai tengah dari list.
2. Bandingkan elemen tengah dengan nilai yang dicari.
Jika sama, pencarian selesai.
Jika nilai yang dicari lebih kecil, abaikan separuh kanan dan lanjutkan pencarian di separuh kiri.
Jika nilai yang dicari lebih besar, abaikan separuh kiri dan lanjutkan pencarian di separuh kanan.
3. Ulangi proses ini hingga elemen ditemukan atau list habis.

Kelebihan dan Kekurangan:

Kelebihan: Lebih efisien untuk list yang besar.
Kekurangan: Hanya bisa digunakan pada list yang sudah terurut.

Contoh Binary Search:
Misalkan kita memiliki list [1, 2, 3, 5, 7] dan ingin mencari angka 5.

Hasil:
Output akan menunjukkan indeks di mana angka 5 ditemukan, yaitu indeks ke-3.

## Pseudocode adalah
Pseudocode adalah metode menulis algoritma dalam bentuk bahasa sehari-hari yang menyerupai kode, tetapi tidak terikat oleh sintaks bahasa pemrograman tertentu. Pseudocode membantu dalam merancang algoritma dan memahami alur penyelesaian masalah sebelum diterjemahkan ke dalam bahasa pemrograman yang spesifik.

## Big O Algoritma 
Big O merupakan alat canggih yang digunakan dalam ilmu komputer untuk menggambarkan kompleksitas waktu atau kompleksitas ruang dari suatu algoritma. Notasi ini menyediakan cara standar untuk membandingkan efisiensi berbagai algoritma dalam hal kinerja terburuknya. Memahami notasi Big O sangat penting untuk menganalisis dan merancang algoritma yang efisien.

## Hitung Big o dari Algoritma Sequential Search

* waktu kompleksitas (time complexity)
kompleksitas waktu adalah kompleksitas komputasi yang menggambarkan jumlah waktu komputer yang dibutuhkan untuk menjalankan suatu algoritma .

* ruang kompleksitas (space koplexity)
Ruang kompleksitas (space complexity) adalah jumlah ruang memori yang dibutuhkan oleh suatu algoritma untuk menyelesaikan masalah komputasi.


# Referensi
https://www.gramedia.com/literasi/pengertian-algoritma/

https://fikti.umsu.ac.id/algoritma-sequential-search-pengertian-fungsi-dan-cara-kerjanya/

https://tekno.kompas.com/read/2022/12/03/03000047/pengertian-binary-search-cara-kerja-dan-keunggulannya

https://www.gramedia.com/best-seller/pseudocode/

https://www-geeksforgeeks-org.translate.goog/analysis-algorithms-big-o-analysis/?_x_tr_sl=en&_x_tr_tl=id&_x_tr_hl=id&_x_tr_pto=tc

https://www.geeksforgeeks.org/time-complexity-and-space-complexity/