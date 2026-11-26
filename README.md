PustakaKu — Sistem Informasi Perpustakaan (CRUD)

Aplikasi Sistem Informasi Perpustakaan PustakaKu merupakan aplikasi berbasis Python, Flask, dan SQLite yang dirancang untuk membantu pengelolaan data perpustakaan secara digital.

Aplikasi ini menyediakan fitur pengelolaan data buku, anggota, transaksi peminjaman dan pengembalian, serta laporan rekapitulasi dengan sistem CRUD (Create, Read, Update, Delete).

Teknologi yang Digunakan

- Bahasa Pemrograman: Python
- Framework: Flask
- Database: SQLite ("perpustakaan.db")
- Format Data: CSV untuk ekspor laporan

SQLite tidak memerlukan instalasi XAMPP atau MySQL secara terpisah.

Fitur Utama

- Dashboard: Menampilkan ringkasan jumlah judul buku, total stok, anggota aktif, transaksi peminjaman, dan peminjaman terbaru.
- Data Buku (CRUD + Filter + Export CSV): Menambahkan, melihat, mencari, memfilter kategori, mengedit, menghapus, dan mengekspor data buku ke CSV.
- Data Anggota (CRUD + Export CSV): Mengelola data anggota, memantau pinjaman aktif dan riwayat transaksi, serta mengekspor data ke CSV.
- Peminjaman & Pengembalian: Mencatat transaksi peminjaman, memantau keterlambatan dan estimasi denda, memproses pengembalian buku dengan pembaruan stok otomatis, serta mengekspor data ke CSV.
- Laporan & Rekap: Menampilkan rekap keterlambatan aktif, estimasi denda berjalan, buku terpopuler, dan peminjam teraktif.
- Mode Tampilan: Mendukung Mode Terang dan Mode Gelap.

Cara Menjalankan Aplikasi

1. Persyaratan

Pastikan perangkat sudah memiliki:

- Python yang sudah terinstal.
- Visual Studio Code atau terminal.
- Browser untuk mengakses aplikasi.

2. Instalasi Flask

Buka terminal pada folder project, kemudian jalankan perintah:

pip install flask

3. Menjalankan Aplikasi

Jalankan file utama aplikasi melalui terminal:

python perpustakaan_nabil_premium.py

4. Membuka Aplikasi

Setelah server Flask berhasil berjalan, buka browser dan akses alamat:

http://127.0.0.1:5000

Aplikasi PustakaKu siap digunakan.

Catatan: Pastikan nama file pada perintah menjalankan aplikasi sesuai dengan nama file utama yang terdapat di repository.

Database

Aplikasi menggunakan SQLite sebagai sistem pengelolaan database.

Database yang digunakan bernama "perpustakaan.db" dan berfungsi untuk menyimpan data buku, anggota, serta transaksi peminjaman dan pengembalian.

Struktur Project

perpustakaan_premium-nabil/
│
├── perpustakaan_nabil_premium.py
├── README.md
├── perpustakaan.db
└── Screenshot/
    ├── l1.png
    ├── l2.png
    ├── l3.png
    ├── l4.png
    ├── l5.png
    ├── l6.png
    └── l7.png

Catatan: Struktur di atas merupakan gambaran susunan project. Sesuaikan dengan file yang benar-benar tersedia di repository.

Tujuan Project

Project ini dibuat sebagai implementasi materi Praktik CRUD Dasar Sistem Informasi Perpustakaan dengan menggunakan teknologi Python dan Flask.

Melalui aplikasi ini, proses pengelolaan data perpustakaan dapat dilakukan secara lebih terstruktur, praktis, dan terkomputerisasi.

---

Project: PustakaKu — Sistem Informasi Perpustakaan

Teknologi: Python, Flask, SQLite

Kategori: Praktik CRUD Dasar Sistem Informasi Perpustakaan
