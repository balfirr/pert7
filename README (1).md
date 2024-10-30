
# Menambahkan komponen didalam Ionic

1. Menambahkan Komponen Bawaan Ionic
Ionic menyediakan berbagai komponen bawaan seperti tombol, input, kartu, dan lainnya yang bisa langsung digunakan. Untuk menambahkan komponen ini:
 - Buka file HTML halaman yang ingin ditambahkan komponennya. Biasanya berada di direktori src/app/pages/nama-halaman/nama-halaman.page.html.
 - Gunakan elemen HTML yang sesuai untuk komponen yang diinginkan.

2. Membuat dan Menggunakan Komponen Kustom
Ionic juga mendukung komponen kustom, yang berguna jika ingin membuat elemen UI yang dapat digunakan di banyak tempat dalam aplikasi. Langkah-langkahnya adalah berikut:
 - Buat komponen kustom baru menggunakan CLI Ionic dengan perintah ionic generate component nama-komponen
 - Lalu, di halaman tempat komponen tersebut ingin digunakan, impor komponen tersebut di nama-halaman.module.ts atau di app.module.ts agar komponen dikenali
 - Tambahkan NamaKomponenComponent di dalam declarations dan exports pada file modul agar bisa digunakan
 - Gunakan komponen di file HTML halaman, contohnya <app-nama-komponen></app-nama-komponen>







## Screenshots

![App Screenshot](https://github.com/balfirr/pert7/blob/78747e1fa6240c8723c8c19e22a09959ff88d4a5/appcb/Screenshot%202024-10-30%20213253.jpg)

