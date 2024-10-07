---
icon: note
---

# Examkey

Examkey berfungsi untuk mencegah siswa membuka halaman ujian menggunakan browser biasa. Apabila examkey diisi maka halaman ujian harus dibuka menggunakan examkey tersebut. Examkey di setting melalui wp/web-admin > pengaturan test > examkey

contoh :

![contoh examkey](/images/Screenshot_10.png)

URL Ujian : https://cbt.my.id/  
Examkey : 123123

maka untuk halaman ujian bisa terbuka, jika dan hanya jika url yg diinput ke dalam browser adalah [https://cbt.my.id/?examkey=123123](https://cbt.my.id/?examkey=123123).

Examkey ini harus di jaga kerahasiannya, bisa dengan operator membuka url + examkey di chrome di laptop sekolah dan membuat tampilan menjadi full screen. Atau memasukkan url + examkey ke dalam settingan aplikasi Exam Client PC seperti Safe Exambrowser.

Examkey tidak untuk di bagi diinput ke laptop siswa, karena siswa bisa dengan mudah mengecek examkey dengan membuka history.

## ExamClient Android Bimasoft

ExamClient Android buatan Bimasoft, di dalamnya sudah ter-inject examkey secara otomatis. Jadi tidak perlu memasukkan / mensetting examkey lagi ke dalam APK Exam Client Bimasoft.