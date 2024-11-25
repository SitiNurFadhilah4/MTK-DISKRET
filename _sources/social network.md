---
title: social network

---

# Analisa graph


## social network analysis

### pengertian social network analysis
merupakan bidang kajian yang mengekplorasitentang hubungan manusia dengan menggunakan teori graf. Implementasi Social Network Analysis dapat menjelaskan relasi atau hubungan antar aktor melalui visualisasi berbentuk graf. Relasi dalam analisis jaringan sosial dapat diproses dalam bentuk perhitungan yang disebut centrality dalam sebuah jaringan sosial sesuai dengan posisi masing-masing aktor di dalam struktur jaringan tersebut

![Cuplikan layar 2024-11-23 132457](https://hackmd.io/_uploads/Bk4dHlyQye.png)

![image](https://hackmd.io/_uploads/Hk8aBxkXyg.png)

#### Social network

terdapat node yang mewakili orang atau individu atau aktor. Relasi  antar objek  dapat dinyatakan dengan link atau edges yang terjadi antara aktor tersebut Social network terdiri dari banyak aktor yang mempunyai relasi satu sama lain hingga membentuk peta jaringan sosial yang dinyatakan dengan graph

* Tidak semua node dalam jaringan adalah penting (aktor). 
* Mencari node yang paling penting dalam suatu jaringan.
*  Centrality adalah penentuan aktor menggunakan ukuran pada Social Network Centrality dalam teori graf dan social network. Dibagi menjadi empat jenis, 
1. degree centrality, 
2. betweeness centrality, 
3. closeness centrality, 
4. eigenvector centrality

## Degree Centrality

### pengertian Degree Centrality
* Degree centrality adalah jumlah edge yang terkoneksi pada suatu node yang mewakili interaksi.
* Pentingnya node ditentukan oleh jumlah node yang berdekatan dengan node tersebut
Lebih besar derajatnya (degree), maka lebih penting node itu dalam suatu jaringan 
Hanya sebagian kecil node yang memiliki derajat tinggi dalam jaringan 

Degree Centrality ![image](https://hackmd.io/_uploads/ry3OtgJ7ke.png)

Normalisasi  Degree Centrality: ![image](https://hackmd.io/_uploads/SyxjYlJXJl.png)

![image](https://hackmd.io/_uploads/S1g2KgkXke.png)

Untuk  node 1, degree centrality adalah 3;
Normalisasi degree centrality adalah  
3/(9-1)=3/8.

## Closeness Centrality

### pengertian Closeness Centrality
Closenes centrality adalah nilai kedekatan antara satu node dengan node lain dalam jaringan dengan menghitung rata-rata dari jarak relasi node-node tersebut. Skor closeness centrality mewakili kecepatan dalam penyebaran informasi.

Average Distance: ![image](https://hackmd.io/_uploads/H1hiMZk71g.png)

Closeness Centrality ![image](https://hackmd.io/_uploads/S1GAzZkQye.png)

Contoh Closeness Centrality 
![image](https://hackmd.io/_uploads/S17e7WJmJe.png)
![image](https://hackmd.io/_uploads/BJhjQ-kQ1x.png)
![image](https://hackmd.io/_uploads/HJR27ZyXyl.png)

Node 4  lebih central  dari node 3

## Betweenness Centrality
* Skor betweeness Centrality mewakili seberapa besar informasi yang tersebar dari suatu aktor. Semakin besar skor, artinya aktor tersebut semakin berperan dalam penyebaran informasi 
* Semakin banyak lintasan yang harus melewati persimpangan itu (misal tidak ada jalan alternatif), maka semakin penting arti persimpangan tersebut. Hal ini menandakan seberapa besar suatu node diperlukan sebagai penghubung dalam penyebaran informasi di dalam jaringan
* Ukuran ini juga dapat digunakan untuk mengidentifikasi boundary spanners, yaitu orang atau node yang berperan sebagai penghubung (jembatan) antara dua komunitas
* Menghitung jumlah lintasan terpendek yang melewati suatu node
* Node dengan  betweenness  tinggi  adalah  penting dalam komunikasi dan penyebaran informasi
* Betweenness Centrality
![image](https://hackmd.io/_uploads/SyqUBWk7Jl.png)
![image](https://hackmd.io/_uploads/SkqPHZ17kl.png)
![image](https://hackmd.io/_uploads/S16_H-1X1x.png)

![image](https://hackmd.io/_uploads/B1gynB-k7yx.png)
![image](https://hackmd.io/_uploads/r1snHbkXJx.png)
betweenness centrality  untuk node 5?
![image](https://hackmd.io/_uploads/B1hlLWy7Jl.png)Jumlah path terpendek antara  s dan t
![image](https://hackmd.io/_uploads/Hyd4L-1XJl.png)
![image](https://hackmd.io/_uploads/rkcLUZkQyl.png)
![image](https://hackmd.io/_uploads/SyWCPb1Xkg.png)

#### Normalisasi Betweenness Centrality
![image](https://hackmd.io/_uploads/ryJbuZkQye.png)






