
# logika matematika

## Negasi
negasi adalah kalimat yang tidak terjadi. Atau dapat disebutkan bahwa negasi adalah kebalikan dari preposisi. Negasi ditandai dengan simbol (~). Jika preposisi awal (p) bernilai benar, maka pernyataan negasinya (~p) adalah salah.


| p| ~p | 
| -------- | -------- | 
| B    | S| 
| S    |B

Contoh negasi adalah:
p : Semua anak suka menonton film. 
~p: Tidak semua anak suka menonton film.

## konjungsi
Konjungsi adalah logika matematika yang menarik kesimpulan dari dua premis. Konjungsi terdiri dari dua pernyataan (p dan q) yang berlaku untuk kata depan majemuk atau dihubungkan oleh kata "dan".
Konjungsi disimbolkan dengan (^). Kebenaran kalimat dengan konjungsi dijelaskan dalam tabel kebenaran konjungsi.


| p | q | p^q |
| -------- | -------- | -------- |
| B   | B    | B     |
| B   | S    | S
| S   | B    | S
| S   | S    | S

Contoh konjungsi adalah
p: Echidna adalah mamalia yang bertelur. (benar) 
q: Platipus adalah mamalia yang bertelur. (benar) 
p∧q: Echidna dan platipus adalah hewan mamalia yang bertelur.(benar)
jika salah satu premisnya bernilai salah maka konjungsinya sudah pasti bernilai salah juga.




## disjugsi
Disjungsi adalah logika matematika yang membandingkan dua obyek. Disjungsi dicirikan dengan kata “atau” dan dilambangkan dengan “v”.
disjungsi hanya bernilai salah jika kedua pernyataan salah dan tetap bernilai benar jika hanya salah satunya yang salah.


| p | q | p^q |
| -------- | -------- | -------- |
| B    | B    | B    |
| B    | S    |  B        |
| S    | B    |B
| S    |S     | S

Contoh disjungsi adalah
p : paus adalah mamalia(pernyataan bernilai benar)
q : paus adalah herbivora(pernyataan bernilai salah)
p∧q: Paus adalah mamalia atau herbivora (pernyataan bernilai benar)

## implikasi
Implikasi merupakan logika matematika berupa pernyataan majemuk. Implikasi menunjukkan hubungan sebab dan akibat, menggunakan konjungsi seperti “jika” dan “maka”, juga disimbolkan oleh karakter "→".

| p | q|p→q  |
| -------- | -------- | -------- |
|B     | B     | B   |
| B     | S     |S      |
| S     |  B    |  B   |
| S     |  S    | B  |

Contoh implikasi adalah
Jika lulus ujian dengan nilai baik, maka ibu akan membelikan sepeda.
Jika tidak bisa dibagi bilangan lain selain satu dan dirinya sendiri, maka angka 3 adalah bilangan prima.

## Biimplikasi
Biimplikasi adalah logika matematika yang ditandai dengan penggunaan kata “jika dan hanya jika”. Implikasi ganda terjadi dalam kalimat majemuk dan diwakili oleh "↔".

Biimplikasi  benar hanya  jika dua pernyataan (p dan q) keduanya benar atau keduanya salah. Jika salah satu pernyataan salah, implikasi kondisional salah.

| p | q | p↔q |
| -------- | -------- | -------- |
| B    | B   | B   |B
|  B    |  S    |  S   
|  S    |  B     |S
|  S    |  S  | B

Contoh biimpliasi adalah
Hukum gas ideal berlaku jika dan hanya jika berada dalam keadaan standar.

## Referensi
https://amp.kompas.com/skola/read/2022/06/02/145036669/negasi-konjungsi-disjungsi-implikasi-dan-biimplikasi

Latihan soal : 
Buatlah tabel kebenaran untuk~pernyataan berikut $$P\lor(R\to\ Q)$$

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{-}&\text{-}&\text{-}\\\text{Т}&\text{Т}&\text{F}&\text{-}&\text{-}&\text{-}\\\text{T}&\text{F}&\text{T}&\text{-}&\text{-}&\text{-}\\\text{T}&\text{F}&\text{F}&\text{-}&\text{-}&\text{-}\\\text{F}&\text{T}&\text{T}&\text{-}&\text{-}&\text{-}\\\text{F}&\text{T}&\text{F}&\text{-}&\text{-}&\text{-}\\\text{F}&\text{F}&\text{T}&\text{-}&\text{-}&\text{-}\\\text{F}&\text{F}&\text{F}&\text{-}&\text{-}&\text{-}&\text{-}\end{array}$$

jawaban

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{T}&\text{T}&\text{T}\\\text{Т}&\text{Т}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{T}&\text{F}&\text{T}&\text{F}&\text{F}&\text{T}\\\text{T}&\text{F}&\text{F}&\text{F}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{T}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{T}&\text{F}&\text{F}&\text{F}\\\text{F}&\text{F}&\text{F}&\text{F}&\text{T}&\text{T}&\text{}\end{array}$$
