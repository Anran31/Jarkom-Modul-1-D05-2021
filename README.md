# Jarkom-Modul-1-D05-2021

## 1. Sebutkan webserver yang digunakan pada "_ichimarumaru.tech_"!  
### Jawaban

Inputkan pada display filter: _(http.host == ichimarumaru.tech)_

<img src="images/Picture1.png" width="400">

<br>Kemudian klik paket paling atas kemudian pilih Analyze > Follow > HTTP Stream

<img src="images/Picture2.png" width="400">

<br>Terlihat bahwa web server yang digunakan adalah nginx/1.18.0

## 2. Temukan paket dari web-web yang menggunakan basic authentication method!
### Jawaban

Inputkan pada display filter: _(http.authbasic)_

<img src="images/Picture3.png" width="400">

## 3. Ikuti perintah di _basic.ichimarumaru.tech_! Username dan password bisa didapatkan dari file .pcapng!

Inputkan display filter: http.host == basic.ichimarumaru.tech

<img src="images/Picture4.png" width="400">

<br>Dapat terlihat data username = “_kuncimenujulautan_” dan password = “_tQKEJFbgNGC1NCZlWAOjhyCOm6o3xEbPkJhTciZN_”

<img src="images/Picture5.png" width="400">

<br>Soal pada website _basic.ichimarumaru.tech_ berisi "Sebutkan urutan konfigurasi pengkabelan T568A!". Yang memiliki jawaban : "Putih hijau - Hijau - Putih orange - Biru - Putih Biru - Orange - Putih Cokelat - Cokelat"

## 4. Temukan paket mysql yang mengandung perintah query select!

Inputkan display filter: mysql.query matches “select”

<img src="images/Picture6.png" width="400">

## 5. Login ke _portal.ichimarumaru.tech_ kemudian ikuti perintahnya! Username dan password bisa didapat dari query insert pada table users dari file .pcap!

Inputkan display filter: mysql.query matches “insert”

<img src="images/Picture7.png" width="400">

<br>Soal pada website _basic.ichimarumaru.tech_ berisi "Sebutkan urutan konfigurasi pengkabelan T568B!". Yang memiliki jawaban : "Putih Oranye - Oranye - Putih Hijau - Biru - Putih Biru - Hijau - Putih Cokelat - Cokelat"

<img src="images/Picture8.png" width="400">