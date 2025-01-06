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

## ⚙️ Teknologi yang Digunakan

- **Laravel 11** (Blade Template Engine)
- **MySQL**
- **Packages yang Digunakan:**
  - `socialite`
  - `laravel-notify`
  - `excel`
  - `tinker`
  - `sweet-alert`

---

## 🎥 Preview Project

Kalian dapat melihat preview project di deskripsi, atau kunjungi langsung website melalui link berikut:

➡️ [**Klik di sini untuk melihat demo**](https://company-profile-lovat.vercel.app/)

---

## 📌 Cara Menjalankan Project

1. Clone repository ini.
2. Install dependensi dengan perintah:
   ```bash
   composer install
   npm install
   ```
3. Konfigurasi file `.env` sesuai dengan database lokal.
4. Jalankan migrasi:
   ```bash
   php artisan migrate
   ```
5. Jalankan server lokal:
   ```bash
   php artisan serve
   ```

---

## 💡 Catatan Tambahan

- Gunakan `php artisan tinker` untuk mencoba perintah di terminal.
- Pastikan semua dependensi terinstal dengan benar.

---

**HRMS** adalah solusi terbaik untuk mempermudah proses administrasi sumber daya manusia di perusahaan Anda!