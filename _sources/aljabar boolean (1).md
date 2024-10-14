---
title: aljabar boolean

---

## aljabar boolean dan gerbang logika

## aljabar boolean

### Pengertian Aljabar Boolean
Aljabar Boolean adalah cabang matematika yang mempelajari nilai kebenaran (true dan false) dan operasi logika. Nama ini diambil dari George Boole, yang mengembangkan sistem ini pada abad ke-19.
Nilai Kebenaran dari aljabar boolean :
- *True (1)*: Menyatakan kebenaran.
- *False (0)*: Menyatakan kebohongan.

Operasi Dasar dari aljabar boolean :
1. *AND (Konjungsi)*: 
   - Simbol: · atau ∧
   - Hasilnya true jika kedua operand benar.
   - Contoh: \( A \cdot B \) hanya benar jika \( A \) dan \( B \) keduanya benar.

2. *OR (Disjungsi)*: 
   - Simbol: + atau ∨
   - Hasilnya true jika salah satu atau kedua operand benar.
   - Contoh: \( A + B \) benar jika \( A \), \( B \), atau keduanya benar.

3. *NOT (Negasi)*: 
   - Simbol: ¬ atau '
   - Mengubah nilai kebenaran; true menjadi false dan sebaliknya.
   - Contoh: \( ¬A \) benar jika \( A \) salah.

Hukum-Hukum Aljabar Boolean :
1. *Hukum Identitas*:
   - \( A + 0 = A \)
   - \( A · 1 = A \)
   
2. *Hukum Dominasi*:
   - \( A + 1 = 1 \)
   - \( A · 0 = 0 \)

3. *Hukum Idempotensi*:
   - \( A + A = A \)
   - \( A · A = A \)

4. *Hukum Komplement*:
   - \( A + ¬A = 1 \)
   - \( A · ¬A = 0 \)

5. *Hukum Distributif*:
   - \( A · (B + C) = (A · B) + (A · C) \)
   - \( A + (B · C) = (A + B) · (A + C) \)

## gerbang logika

### Pengertian Gerbang Logika

Gerbang logika adalah komponen dasar dalam rangkaian digital yang digunakan untuk melakukan operasi logika. Mereka menerima satu atau lebih input dan menghasilkan output berdasarkan aturan tertentu. Gerbang logika sering digunakan dalam sirkuit komputer dan pemrograman.

### Jenis-Jenis Gerbang Logika

1. *Gerbang AND*:
   - *Simbol*: · (dot) atau &
   - *Fungsi*: Menghasilkan output true (1) hanya jika semua inputnya true.
   - *Tabel Kebenaran*:
     | A | B | A AND B |
     |---|---|---------|
     | 0 | 0 |    0    |
     | 0 | 1 |    0    |
     | 1 | 0 |    0    |
     | 1 | 1 |    1    |

2. *Gerbang OR*:
   - *Simbol*: + (plus)
   - *Fungsi*: Menghasilkan output true jika setidaknya satu inputnya true.
   - *Tabel Kebenaran*:
     | A | B | A OR B |
     |---|---|--------|
     | 0 | 0 |   0    |
     | 0 | 1 |   1    |
     | 1 | 0 |   1    |
     | 1 | 1 |   1    |

3. *Gerbang NOT*:
   - *Simbol*: ¬ atau !
   - *Fungsi*: Membalikkan nilai input; jika input true, outputnya false, dan sebaliknya.
   - *Tabel Kebenaran*:
     | A | NOT A |
     |---|-------|
     | 0 |   1   |
     | 1 |   0   |

4. *Gerbang NAND*:
   - *Fungsi*: Kebalikan dari AND; menghasilkan false hanya jika semua inputnya true.

5. *Gerbang NOR*:
   - *Fungsi*: Kebalikan dari OR; menghasilkan true hanya jika semua inputnya false.

6. *Gerbang XOR (Exclusive OR)*:
   - *Fungsi*: Menghasilkan true jika jumlah input yang true adalah ganjil.
   - *Tabel Kebenaran*:
     | A | B | A XOR B |
     |---|---|---------|
     | 0 | 0 |    0    |
     | 0 | 1 |    1    |
     | 1 | 0 |    1    |
     | 1 | 1 |    0    |

7. *Gerbang XNOR (Exclusive NOR)*:
   - *Fungsi*: Kebalikan dari XOR; menghasilkan true jika jumlah input yang true adalah genap.

### Aplikasi Gerbang Logika

- *Sirkuit Digital*: Digunakan dalam desain komputer untuk aritmetika, penyimpanan data, dan pengendalian.
- *Algoritma*: Menerapkan operasi logika dalam pemrograman untuk pengambilan keputusan.
- *Sistem Keamanan*: Menerapkan logika untuk autentikasi dan kontrol akses.

### Kesimpulan

Gerbang logika adalah fondasi dari sistem digital dan komputer. Memahami cara kerja dan fungsi masing-masing gerbang sangat penting dalam bidang elektronika dan pemrograman.

## referensi
https://poe.com/s/trw85DUZHphv49yieZdI
