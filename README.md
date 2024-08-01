# Notes App
> Task Seleksi Lab IRK created by Fahrian Afdholi

versi **01 Agustus 2024**



## 💡 Latar Belakang
Notes app adalah aplikasi berbasis android yang memungkinkan pengguna untuk membuat, mengedit, menghapus, mencari, dan melihat catatan. Aplikasi ini dibuat dengan tujuan untuk memudahkan pengguna dalam menyimpan catatan catatan penting seperti catatan belanjaan, catatan kuliah, catatan meeting, dan lain-lain. Aplikasi ini juga memungkinkan pengguna untuk mengurutkan catatan catatan tersebut berdasarkan kategori tertentu.


## 📝 Spesifikasi Tugas
Pada aplikasi ini terdapat beberapa algoritma yang difokuskan yaitu algoritma sorting dan searching. Algoritma sorting sendiri digunakan untuk mengurutkan catatan berdasarkan tanggal dibuat(dari yang terbaru ke terlama maupun sebaliknya) dan berdasarkan huruf


### Spesifikasi Wajib (2500 Poin)
Pada tugas kali ini kalian diminta untuk membuat sebuah aplikasi berbasis android yang dapat melakukan CRUD pada catatan. Berikut merupakan spesifikasi lengkapnya:
1. Aplikasi dapat melakukan CRUD (Create, Read, Update, Delete) pada catatan.
2. Aplikasi dapat melakukan opsi sorting pada catatan berdasarkan **title**, **created_at**, dan **updated_at** menggunakan algoritma sorting yang dipilih, dengan prioritas tertinggi ke terendah sebagai berikut:
   - title (A-Z)
   - title (Z-A)
   - created_at (Terbaru)
   - created_at (Terlama)
   - updated_at (Terbaru)
   - updated_at (Terlama)
3. Aplikasi dapat melakukan searching pada catatan dengan menggunakan **algoritma string** matching yang kalian pilih (jadi jangan make query doang ya!). Hal yang perlu dicari adalah sebagai **Title** dan **Note** dengan prioritas tertinggi ke terendah sebagai berikut:
   - Title dan Note
   - Title
   - Note
4. Aplikasi dapat melakukan import dan export catatan ke dalam format **.xls dan .xlsx**
5. Aplikasi dapat melakukan filter pada catatan berdasarkan kategori catatan (pastinya make string matching ya).
6. Aplikasi berbasis android dengan batasan sebagai berikut
   - programming language: Kotlin
   - minimum API level: 24
   - database: room/realm
7. Data catatan pada database seminimal minimalnya terdiri dari:
   - title
   - note (isi catatan)
   - category
   - created_at
   - updated_at
8. Aplikasi **WAJIB** memiliki page **SETTINGS** untuk melakukan perubahan algoritma sorting dan searching yang digunakan yang dimana algoritma sorting merupakan 2 pilihan algoritma terbaik kalian dan algoritma string matching merupakan KMP dan BM.
9. Buatlah readme yang seminimal minimalnya berisi:
   - cara penggunaan aplikasi
   - mengapa kalian memilih algoritma sorting yang kalian pilih dan jelaskan perbandingannya antara algoritma tersebut.
   - jelasin algoritma string matching yang kalian pilih dan jelaskan perbandingannya antara algoritma tersebut.
   - screenshot aplikasi
   - spek minimum device yang bisa menjalankan aplikasi

## Hal yang Perlu Diperhatikan
1. Jika terdapat huruf yang sama seperti contohnya "AAA" dan "AAB" maka jika diurutkan dari "A-Z" maka "AAA" akan berada di atas "AAB" dan sebaliknya.
2. Jika terdapat case dengan huruf seperti "AAA" dan "AAAA" maka jika diurutkan dari "A-Z" maka "AAA" akan berada di atas "AAAA" dan sebaliknya.

## 📂 Pengerjaan dan Pengumpulan
1. Buatlah repositori **private** pada github masing-masing dan invite `fchrgrib` dalam repositori tersebut.
2. Berkas yang dikumpulkan berupa **link rilis tag ke repositori github** yang telah dibuat dengan ketentuan sebagai berikut.
    - Memberikan tag `vn` pada commit terakhir Anda setiap kali ingin melakukan submisi dengan `n` adalah jumlah submisi yang telah dilakukan. (contoh: `v1` untuk submisi pertama).
    - **Tidak menggunakan *url shortener*** (bit.ly, shortlink, atau yang lain) saat melakukan pengumpulan *task*.
    - Anda dapat melakukan rilis dengan panduan [berikut](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository).
3. Jika terdapat pertanyaan dapat menghubungi LINE `@fchrgrib2310`.

## 📌 Penilaian
| Aspek                     | Nilai Maksimal |
|---------------------------|----------------|
| Algoritma Sorting         | 750            |
| Algoritma String Matching | 750            |
| Import Export             | 250            |
| Readme                    | 250            |
| CRUD Notes                | 250            |
| Filter                    | 250            |


**Selamat mengerjakan!**
