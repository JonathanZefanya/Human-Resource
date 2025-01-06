# HRMS - Human Resource Management System

Human Resource Management System (HRMS) adalah sebuah sistem untuk manajemen karyawan yang dirancang untuk memudahkan administrasi perusahaan dalam mengelola data karyawan, penggajian, cuti, absensi, dan rekrutmen.

---

## 📋 Fitur-Fitur

### Fitur Khusus Admin

| Nama Fitur             | Gambar Preview               |
|------------------------|------------------------------|
| Management Karyawan    | ![Management Karyawan](#)    |
| Penggajian Karyawan    | ![Penggajian Karyawan](#)    |
| Rekrutmen Karyawan     | ![Rekrutmen Karyawan](#)     |
| Management Cuti        | ![Management Cuti](#)        |
| Management Data Pribadi| ![Data Pribadi](#)           |
| Management Absensi     | ![Absensi](#)                |
| Management Laporan     | ![Laporan](#)                |

### Fitur Khusus Karyawan/User

| Nama Fitur       | Gambar Preview        |
|------------------|-----------------------|
| Absensi          | ![Absensi](#)         |
| Pengajuan Cuti   | ![Pengajuan Cuti](#)  |
| Izin Sakit       | ![Izin Sakit](#)      |
| Melihat Gaji     | ![Melihat Gaji](#)    |

---

- **Laravel 11 (Blade)** - Framework PHP untuk membangun aplikasi web yang cepat dan aman.
- **MySQL** - Basis data relasional untuk menyimpan data karyawan dan transaksi.
- **Packages** yang digunakan:
  - `socialite` - Untuk integrasi login menggunakan media sosial.
  - `laravel-notify` - Untuk menampilkan notifikasi.
  - `excel` - Untuk ekspor dan impor data dalam format Excel.
  - `tinker` - Untuk menjalankan perintah Artisan secara interaktif.
  - `sweet-alert` - Untuk menampilkan pesan alert yang interaktif dan menarik.

---

## 🎥 Preview Project

Kalian dapat melihat preview project di deskripsi, atau kunjungi langsung website melalui link berikut:

➡️ [**Klik di sini untuk melihat demo**](https://company-profile-lovat.vercel.app/)

---

## 📚 Cara Install
Ikuti langkah-langkah berikut untuk menginstal project HRMS:

1. Clone repository ini ke komputer lokal Anda:
   ```bash
   git clone https://github.com/username/hrms.git
   ```

2. Masuk ke direktori project:
   ```bash
   cd hrms
   ```

3. Install dependencies menggunakan Composer:
   ```bash
   composer install
   ```

4. Buat file `.env` dan sesuaikan konfigurasi database Anda.

5. Jalankan migrasi untuk membuat tabel di database:
   ```bash
   php artisan migrate
   ```

6. Jalankan server lokal:
   ```bash
   php artisan serve
   ```

7. Akses aplikasi di browser dengan URL:
   ```
   http://localhost:8000
   ```

---

## 💡 Catatan Tambahan

- Gunakan `php artisan tinker` untuk mencoba perintah di terminal.
- Pastikan semua dependensi terinstal dengan benar.

---

**HRMS** adalah solusi terbaik untuk mempermudah proses administrasi sumber daya manusia di perusahaan Anda!