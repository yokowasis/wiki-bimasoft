---
order: 1100
author: Wasis Haryo Sasoko
icon: note 
---

# Quick Start

## Video Tutorial

[!embed](https://www.youtube.com/watch?v=rd4PuQIcuTo)

## Pengaturan Test Awal
1. Login ke halaman webadmin. Url admin, username dan password bisa di cek pada halaman invoice

![alt text](../../images/quick-start/image.png)

2. Masuk ke halaman Pengaturan test
    - Ganti Password
    - Isi nama sekolah dan upload logo pada kolom yang telah disediakan.
    - Isi pengaturan test yg lain sesuai kebutuhan

![alt text](../../images/quick-start/image-1.png)    

## Persiapan Alat dan Bahan
1. Download Template Word dan Excel melalui [Google Drive](https://bimasoft.web.id/gdrive/)
![Google Drive](../../images/gdrive.png)

2. Catat Link - Link Penting Yang ada di Dashboard Webadmin
    - URL Word 
    - Username / Password Word
    - URL Server Excel

![alt text](../../images/quick-start/image-2.png)

## Pembuatan Soal
1. Buka `Template Word`
2. Pilih `Manage Account`
![alt text](../../images/quick-start/image-3.png)
3. Pilih [!button variant="secondary" text="New"]
![alt text](../../images/quick-start/image-4.png)
4. Ganti `Blog` dari `Choose your blog provider` menjadi `Wordpress`, [!button variant="secondary" text="Next"]
![alt text](../../images/quick-start/image-5.png)
5. Isi sesuai data yg di catat pada point sebelumnya

![alt text](../../images/quick-start/image-6.png)

Nama Kolom          | Isian
--------------------|------------------------
Blog Post Url       | `URL Word`
Username            | Username Word
Password            | Password Word
Remember Password   | ✅

Klik [!button variant="secondary" text="OK"]

*Konfirmasi Berhasil*
![alt text](../../images/quick-start/image-7.png)

Klik [!button variant="secondary" text="OK"], Klik [!button variant="secondary" text="Close"]

6. Buat soal sesuai template yg disediakan. Ganti Kode Test (Judul Soal, Paling atas)
7. Publish

![alt text](../../images/quick-start/image-8.png)

## Input Kunci Jawaban dan Data Siswa

### Kunci Jawaban

1. Buka `Template Excel`
2. Isi Sesuai Petunjuk di bawah ini

![alt text](../../images/quick-start/image-10.png)

Nama Kolom              | Isian                                     | Contoh 
------------------------|-------------------------------------------|---------------------------
Server                  | URL Server Excel di atas                  | https://cbt-dst-nya.com/
Kode Test               | Kode Test yang diisi di `Word`            | IPA
Nama Test               | Bebas                                     | IPA
Status                  | Bebas                                     | PAS
Sub Test                | Bebas                                     | PAS
Tanggal                 | Tanggal Test                              | 12-02-2022
Waktu Test              | Waktu Test                                | 07:30
Alokasi                 | Durasi Test (dalam menit)                 | 90
Jumlah Soal             | Sesuai Jumlah soal di `Word`              | 30
Yang Harus Dikerjakan   | Jumlah soal wajib yg di kerjakan siswa    | 30 
Acak Soal / Option      | Apakah soal / option mau di acak ?        | 1 / 1


3. Isi Kunci Jawaban dan Skor Pada Kolom di Sebelah Kanan, Semua No. Soal wajib memiliki kunci. Jika ada Soal yang kelebihan, maka hapus soal tersebut.
4. Klik Tombol [!button variant="secondary" text="Save"] di sebelah Kanan

### Data Siswa

![alt text](../../images/quick-start/image-11.png)

1. Klik `Sheet Peserta`
2. Isi Biodata
    - Server wajib huruf besar semua tanpa spasi
    - Sesi wajib angka
3. Klik Tombol [!button variant="secondary" text="Save"] di sebelah kanan

## Mengimport Soal Yang Sudah Di Publish
1. Masuk ke dalam *webadmin*
2. Klik *Database Test*
3. Klik tombol import soal di deretan tombol yang ada di paling kanan

![import](/images/importsoal.png)

## Pelaksanaan Ujian

![alt text](../../images/quick-start/image-12.png)

1. Buka `URL Siswa`
2. Pilih Mapel
3. Gunakan `username` dan `password` yang di input pada `Template Excel` di `Sheet Peserta` pada langkah [sebelumnya](#data-siswa)

## Penilaian / Hasil

![alt text](../../images/quick-start/image-13.png)

1. Buka `Template Excel`
2. Klik `Sheet Hasil`
3. Klik Refresh Hasil Kiri Atas 🔃

