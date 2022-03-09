---
icon: note
---
# Gagal Terhubung ke Server

Ada beberapa penyebab pesan Gagal Terhubung ke Server :

**1. Salah penulisan URL**
Pastikan url yang ditulis adalah benar
http://192.168.0.199/ubk/ : ✅ BENAR
http://192.168.0.199/ubk  : ❌ SALAH (tidak ada garis miring di akhir)

**2. Web Server Belum Hidup**
Pastikan ketika URL yang diinput di Template Excel ketika di buka di chrome muncul halaman Login Siswa. 

**3. Versi Template Excel dan versi Aplikasi tidak sesuai**
Aplikasi dan template Excel minimal Versi #12

**4. Belum Reset DATABASE.**
Ketika melakukan update / install tema, belum melakukan reset database. Reset database dilakukan dengan cara (*Kerjakan Sesuai Urutan*): WP-Admin -> Pengaturan Test -> Reset Database = Tidak -> Save -> Reset Database = Ya -> Save -> Reset Database = Tidak -> Save. 

**5. Excel Key Salah.**
Pastikan Key di Microsoft Excel (yg berwarna coklat) sama dengan excel key di pengaturan test.
