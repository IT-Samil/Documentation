# 📸 Galeri Dokumentasi SJI

Aplikasi galeri berbasis web sederhana dan responsif untuk mendokumentasikan berbagai kegiatan produksi dan korporat. Aplikasi ini dirancang untuk dijalankan langsung melalui **GitHub Pages** dengan sistem penyimpanan data lokal (`localStorage`) dan sinkronisasi manual via JSON.

## ✨ Fitur Utama
- **Masonry Layout:** Tata letak kartu foto yang adaptif dan estetik.
- **Form Input Interaktif:** Tambah data dokumentasi tanpa menyentuh kode program.
- **Sistem Kategori:** Filter foto berdasarkan Seminar, Workshop, Sosial, dan Olahraga.
- **Lightbox Viewer:** Pratinjau foto ukuran penuh dengan deskripsi lengkap.
- **Backup & Restore:** Ekspor dan Impor data dalam format `.json` untuk sinkronisasi antar perangkat (HP ke Laptop).
- **Offline-Ready:** Menggunakan library via CDN yang ringan dan performa cepat.

## 📂 Struktur Folder
Agar aplikasi berjalan lancar, pastikan struktur repositori Anda seperti ini:
```text
/galeri-SAMIL TEXTILE INDONESIA
  ├── index.html       # File utama aplikasi
  ├── images/          # FOLDER UTAMA: Simpan semua file foto (.jpg, .png, .webp) di sini
  └── README.md        # Panduan ini
