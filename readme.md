# Sistem Informasi Mahasiswa UNISKA

[cite_start]Sistem Informasi Mahasiswa UNISKA adalah sebuah aplikasi berbasis web yang dirancang dengan antarmuka yang sederhana, modern, dan informatif[cite: 7]. [cite_start]Aplikasi ini berfungsi sebagai alat bantu untuk mengelola data akademik mahasiswa agar menjadi lebih praktis, efisien, dan terorganisir dengan baik[cite: 7, 8].

---

## 🚀 Fitur Utama

[cite_start]Aplikasi ini menyediakan manajemen data mahasiswa secara penuh (CRUD) yang mencakup fitur-fitur berikut[cite: 15]:
* [cite_start]**Dashboard Informatif**: Halaman beranda (*landing page*) bersih yang menyambut pengguna dengan ringkasan komponen teknologi yang digunakan[cite: 7, 9, 13, 14].
* **Manajemen Data (CRUD)**:
  * [cite_start]**Melihat Data**: Menampilkan daftar mahasiswa dalam bentuk tabel terstruktur beserta status keaktifannya[cite: 16, 21].
  * [cite_start]**Tambah Data**: Formulir input data mahasiswa baru dilengkapi dengan validasi kolom wajib (*required fields*)[cite: 17, 52, 53].
  * [cite_start]**Detail Data**: Menampilkan profil lengkap, rincian akademik, serta waktu pembuatan/pembaruan data[cite: 39, 68, 69].
  * [cite_start]**Ubah Data**: Mengedit informasi mahasiswa yang sudah ada dengan menampilkan nilai lama pada form[cite: 18, 40, 72].
  * [cite_start]**Hapus Data**: Menghapus data dari sistem yang dilengkapi dengan sistem pengamanan konfirmasi[cite: 19, 41, 75].
* [cite_start]**Pencarian & Filtrasi**: Mempermudah pencarian mahasiswa berdasarkan NPM/Nama serta penyaringan berdasarkan Jurusan[cite: 42, 44, 45].
* [cite_start]**Keamanan Data**: Jendela peringatan (*modal dialog*) konfirmasi hapus data untuk mencegah tindakan penghapusan yang tidak disengaja[cite: 75].

---

## 🛠️ Arsitektur & Teknologi

Sistem ini dibangun menggunakan kombinasi teknologi dan pola arsitektur modern untuk memastikan performa dan keamanan yang optimal:

1. [cite_start]**Arsitektur - MVC (Model-View-Controller)** [cite: 9]
   [cite_start]Pola desain yang memisahkan komponen utama aplikasi untuk mempermudah pengembangan[cite: 9]:
   * [cite_start]**Model**: Menangani pemrosesan data dan interaksi dengan database[cite: 10].
   * [cite_start]**View**: Menangani tampilan antarmuka pengguna (UI)[cite: 11].
   * [cite_start]**Controller**: Menjadi penghubung logika utama dari sistem[cite: 12].

2. [cite_start]**Database Connection - PDO (PHP Data Objects)** [cite: 13]
   [cite_start]Digunakan sebagai lapisan akses data untuk memastikan koneksi database yang lebih aman (terhindar dari SQL Injection), fleksibel, dan mendukung berbagai jenis *database engine*[cite: 13].

3. [cite_start]**Frontend Framework - Bootstrap 5 (BS 5)** [cite: 14]
   [cite_start]Framework CSS yang digunakan untuk membangun antarmuka web yang modern, rapi, dan sepenuhnya responsif di berbagai perangkat[cite: 14].

---

## 📸 Dokumentasi Antarmuka (UI)

### 1. Tampilan Utama (Index)
[cite_start]Halaman beranda yang berfungsi sebagai *landing page* utama untuk mengarahkan pengguna ke basis data mahasiswa[cite: 7, 8].
*(Tempatkan gambar Index di sini)*

### 2. Tampilan Data Mahasiswa
[cite_start]Menyajikan informasi terstruktur mahasiswa seperti ID, NPM, Nama, Jurusan, Jenis Kelamin (L/P), dan Status dalam bentuk tabel interaktif[cite: 21, 31, 33]. [cite_start]Kolom aksi menyediakan tombol pintas untuk melihat detail, menyunting, atau menghapus entri data[cite: 22].
*(Tempatkan gambar Daftar Mahasiswa di sini)*

### 3. Tampilan Tambah Data Mahasiswa
[cite_start]Formulir khusus untuk merekam identitas mahasiswa baru[cite: 52]. [cite_start]Inputan wajib ditandai dengan tanda asterik (*) untuk menjaga validitas data sebelum disimpan ke database[cite: 53].
*(Tempatkan gambar Tambah Mahasiswa di sini)*

### 4. Tampilan Detail Mahasiswa
Menampilkan profil spesifik mahasiswa secara mendalam, lengkap dengan informasi fakultas, jurusan, hingga jejak waktu kapan data dibuat atau diperbarui[cite: 68, 69]. Halaman ini juga memiliki opsi cetak fisik dokumen[cite: 70].
*(Tempatkan gambar Detail Mahasiswa di sini)*

### 5. Tampilan Edit Data Mahasiswa
Halaman penyuntingan yang otomatis memuat data lama mahasiswa agar admin dapat memperbarui informasi yang diperlukan secara akurat[cite: 72].
*(Tempatkan gambar Edit Mahasiswa di sini)*

### 6. Jendela Konfirmasi Hapus Data
Sistem pengamanan tingkat akhir berupa *modal dialog* untuk memastikan bahwa pengguna benar-benar yakin ingin menghapus data secara permanen[cite: 75, 76].
*(Tempatkan gambar Modal Hapus di sini)*

---

## 👥 Anggota Kelompok
Proyek praktikum ini disusun dan dikembangkan oleh[cite: 2]:
* [cite_start]Ahmad Taufiq Wahyu Pratama (2310010392) [cite: 3]
* [cite_start]Aditya Rafael Ramadhan (2310010530) [cite: 4]
* [cite_start]Abdul Wahab (2310010150) [cite: 5]