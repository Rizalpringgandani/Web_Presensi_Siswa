# Presensi Siswa SMK Bina Karya 2 Karawang

## Daftar Isi
- [Tentang](#tentang)
- [Prasyarat](#prasyarat)
- [Instalasi](#instalasi)
- [Penggunaan](#penggunaan)
- [Kontribusi](#kontribusi)
- [Lisensi](#lisensi)
- [Kontak](#kontak)

## Tentang
ini adalah aplikasi absensi siswa berbasis website pada SMK Bina Karya 2 Karawang yang mempermudah guru untuk melakuakan absensi kepada siswa dan memperpudah dalam melakukan rekapitulasi absensi 

## Prasyarat
Sebutkan prasyarat yang diperlukan sebelum menginstal proyek ini. Misalnya:
- PHP versi 8.1.25
- Composer
- Web server Apache
- teks editor
- xampp

## Instalasi
Berikan langkah-langkah untuk menginstal proyek Anda. Misalnya:
1. download
   download melalui link di bawah ini lalu ekstrak file zip hasil download
    ```bash
    git clone https://github.com/Rizalpringgandani/Absensi_BK2
    ```
2.  buka xampp lalu klik start apache dan myqsl
    ```bash
    ![Alt text](url_gambar)

    ```
3. buka link 
    ```bash
    http://localhost/phpmyadmin/
    ```
   laluimport database [database](database/db_imas.sql)

4. buka link di bwah ini untuk membuka halaman guru/siswa
    ```bash
    http://localhost/nama_folder
    ```
    buka link bawah ini untuk membuka halaman admin
    ```bash
    http://localhost/nama_folder/admin
    ```
## Penggunaan
1. Untuk akun Admin gunakan
   Username : admin@gmail.com
   password : admin
   
   halaman admin:
   ![Alt text](img/halamanAdmin)

   Pada Menu admin anda dapat mengelola data umum, jadwal mengajar, data guru, dan data siswa

   Halaman guru:
   ![Alt text](img/halamanGuru)
   Pada halaman Guru anda dapat melakukan presensi kepada siswa dan melakukan rekap persemester

   Halaman guru:
   ![Alt text](img/halamanSiswa)
   Pada halaman Siswa anda dapat melihat daftar kehadiran siswa
   
## Kontak

Rizal Pringgandani - [@rizalpringgandani009](https://twitter.com/TwitterHandle) - pringgandanirizal37@gmail.com

Demo aplikasi: [Presensi BK2 Admin](https://rizalbk2tryhard.000webhostapp.com/admin)
               [Presensi BK2 Guru/Siswa](https://rizalbk2tryhard.000webhostapp.com/)

