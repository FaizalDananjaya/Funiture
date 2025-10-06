# Funiture – Sistem Manajemen Furniture  

Funiture adalah aplikasi web untuk manajemen perusahaan furniture, dirancang agar perusahaan dapat mengelola produk, stok, pelanggan, dan pesanan secara mudah dan efisien.

---

## 🏢 Profil Perusahaan (Dummy untuk Localhost)  
Nama perusahaan: **PT Kayu Indah Perkasa**  
Alamat: Jl. Merpati No. 18, Jakarta Barat, DKI Jakarta 11430  
Telepon: +6281390098876  
Email: kayuindah.perkasa@gmail.com  

---

## ✨ Fitur Utama  

- Manajemen produk: tambah, ubah, hapus produk furniture  
- Pengelolaan stok gudang: masuk/keluar barang, update stok  
- Sistem pesanan: pelanggan dapat memesan produk  
- Manajemen pelanggan: data pelanggan disimpan dan bisa diedit  
- Dashboard: ringkasan stok, pesanan, produk terlaris  
- Autentikasi pengguna: role admin dan staff  

---

## 🛠️ Teknologi yang Digunakan  

Misalnya (ubah sesuai dengan apa yang kamu pakai):  
- Backend: PHP + CodeIgniter  
- Database: MySQL / MariaDB  
- Frontend: HTML, CSS, JavaScript, Bootstrap  
- Libraries tambahan: TCPDF untuk invoice, jQuery  

---

## 👥 User Default  

**Admin**  
- Username: `admin`  
- Password: `admin`  

**Staff**  
- Username: `staff`  
- Password: `staffpassword`  

---

## ⚙️ Cara Instalasi & Setup  

1. Clone repository  
   ```bash
   git clone https://github.com/FaizalDananjaya/Funiture.git
   cd Funiture

    Ubah nama folder (jika perlu) sesuai keinginan proyekmu

    Import database (file .sql yang tersedia) ke MySQL / MariaDB

    Sesuaikan file config/database.php (jika CodeIgniter) agar terhubung ke database lokalmu

    Jalankan aplikasi melalui server lokal (misalnya XAMPP / WAMP) dengan URL seperti:

    http://localhost/funiture

📝 Catatan Khusus

    Jika muncul error pada fitur invoice (PDF), pastikan library TCPDF terbaru telah diletakkan di folder application/libraries/tcpdf. Kamu bisa mendownloadnya dari:
    https://github.com/tecnickcom/TCPDF

    Jika meng-clone atau mendownload, pastikan struktur folder sudah benar agar aplikasi berjalan normal.

🚀 Pengembangan & Kontribusi

    Proyek ini terbuka untuk perbaikan UI/UX, fitur tambahan, dan optimasi

    Kamu bisa membuat branch baru untuk fitur, lalu ajukan Pull Request

    Dokumentasi lebih lengkap akan menyusul sesuai pengembangan
