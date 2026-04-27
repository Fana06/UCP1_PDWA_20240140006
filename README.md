# Tech Community Website
### UCP 1 - Praktikum Pengembangan Desain Web
---

//Identitas//

| **Nama** | Aquilla Faza Naufan |
| **NIM** | 20240140006 |
| **Kelas A** |
| **Mata Kuliah** | Praktikum Pengembangan Desain Web |
| **Tugas** | UCP 1 |
| **Tahun** | 2025/2026 |
---
 
## Deskripsi
 
Website sederhana untuk komunitas teknologi bernama **Tech Community**. Website ini dibuat sebagai pemenuhan tugas UCP 1 Praktikum Pengembangan Desain Web, dibangun menggunakan **HTML, CSS, dan JavaScript** murni tanpa framework atau database.
 
Website berfungsi untuk memperkenalkan komunitas, mendata anggota baru melalui form, serta menampilkan konten multimedia.
---
 
## Struktur File
```
ucp1/
├── beranda.html       # Halaman utama & tabel anggota
├── pendaftaran.html   # Halaman form pendaftaran anggota
├── dokumentasi.html   # Halaman multimedia (gambar, video, audio)
├── style.css          # Stylesheet eksternal (dipakai semua halaman)
├── gambar1.jpg        # Aset gambar 1
├── gambar2.jpg        # Aset gambar 2
├── video1.mp4         # Aset video
└── audio1.mp3         # Aset audio
```
---
 
## Halaman Website
 
### 1. Beranda (`beranda.html`)
- Menampilkan judul dan deskripsi singkat Tech Community
- Navigasi menuju halaman Pendaftaran dan Dokumentasi
- Tabel daftar anggota yang dirender secara dinamis menggunakan JavaScript
- Data anggota dibaca dari `localStorage` sehingga tetap tersimpan antar sesi
### 2. Pendaftaran (`pendaftaran.html`)
- Form input data anggota baru: **Nama**, **Email**, **Bidang Minat**
- Saat submit, data ditangkap oleh JavaScript dan:
  - Ditampilkan sebagai notifikasi di bawah form
  - Ditampilkan via `alert()`
  - Disimpan ke `localStorage` sebagai simulasi penyimpanan sementara
- Tombol kembali ke halaman Beranda
### 3. Dokumentasi (`dokumentasi.html`)
- Menampilkan gambar dengan fitur **ganti gambar** menggunakan JavaScript
- Menampilkan video menggunakan tag `<video>`
- Menampilkan audio dengan tombol **Putar** dan **Hentikan** berbasis JavaScript
---
 
## Teknologi yang Digunakan
 
| Teknologi | Keterangan |
|---|---|
| HTML5 | Struktur dan konten website |
| CSS3 (External) | Styling seluruh halaman via `style.css` |
| JavaScript (Vanilla) | Interaksi form, ganti gambar, kontrol audio |
| localStorage | Simulasi penyimpanan data anggota sementara |
| Google Fonts | Font `IBM Plex Mono` & `Inter` | 
---
 
## Fitur JavaScript
 
- **Form submit** → simpan data ke array & `localStorage`, tampil alert + notifikasi
- **Render tabel** → membaca data dari `localStorage` dan menampilkannya dinamis
- **Ganti gambar** → klik tombol untuk switch antara `gambar1.jpg` dan `gambar2.jpg`
- **Info gambar** → alert nama file gambar yang sedang aktif
- **Kontrol audio** → tombol Putar dan Hentikan untuk tag `<audio>`
---

