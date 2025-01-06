# HRMS - Human Resource Management System

Human Resource Management System (HRMS) adalah sebuah sistem untuk manajemen karyawan yang dirancang untuk memudahkan administrasi perusahaan dalam mengelola data karyawan, penggajian, cuti, absensi, dan rekrutmen.

---

## 📋 Fitur-Fitur

### Deskripsi
Berikut adalah fitur-fitur yang tersedia dalam HRMS:

### Fitur Khusus Admin

| Fitur             | Deskripsi                          |
|-------------------|------------------------------------|
| **Management Karyawan** | Mengelola data karyawan, termasuk menambah, mengedit, dan menghapus data karyawan. |
| **Penggajian Karyawan**  | Mengatur penggajian karyawan dengan perhitungan otomatis dan laporan gaji. |
| **Rekrutmen Karyawan**   | Mengelola proses rekrutmen mulai dari pengumuman lowongan hingga seleksi. |
| **Management Cuti**      | Mengatur pengajuan dan persetujuan cuti karyawan. |
| **Management Data Pribadi** | Mengelola informasi pribadi karyawan seperti alamat, kontak, dan dokumen penting. |
| **Management Data Absensi** | Mencatat dan memantau kehadiran karyawan. |
| **Management Laporan**   | Membuat laporan terkait kinerja dan data karyawan. |

### Fitur Khusus untuk Karyawan/User
- Absensi harian secara online.
- Pengajuan cuti langsung dari sistem.
- Izin sakit dengan mengunggah bukti.
- Melihat slip gaji dan histori pembayaran.

### Screenshot
#### Fitur Khusus Admin

| Nama Fitur             | Gambar Preview               |
|------------------------|------------------------------|
| Management Karyawan    | ![Management Karyawan](https://github.com/JonathanZefanya/Human-Resource/blob/main/Screenshoot/admin/mk.png)    |
| Penggajian Karyawan    | ![Penggajian Karyawan](https://github.com/JonathanZefanya/Human-Resource/blob/main/Screenshoot/admin/gaji.png)    |
| Rekrutmen Karyawan     | ![Rekrutmen Karyawan](https://github.com/JonathanZefanya/Human-Resource/blob/main/Screenshoot/admin/rk.png)     |
| Management Cuti        | ![Management Cuti](https://github.com/JonathanZefanya/Human-Resource/blob/main/Screenshoot/admin/cuti.png)        |
| Management Data Pribadi| ![Data Pribadi](https://github.com/JonathanZefanya/Human-Resource/blob/main/Screenshoot/admin/dp.png)           |
| Management Absensi     | ![Absensi](https://github.com/JonathanZefanya/Human-Resource/blob/main/Screenshoot/admin/ma.png)                |
| Management Laporan     | ![Laporan](https://github.com/JonathanZefanya/Human-Resource/blob/main/Screenshoot/admin/laporan.png)                |

#### Fitur Khusus Karyawan/User

| Nama Fitur       | Gambar Preview        |
|------------------|-----------------------|
| Absensi          | ![Absensi](https://github.com/JonathanZefanya/Human-Resource/blob/main/Screenshoot/user/absensi.png)         |
| Pengajuan Cuti   | ![Pengajuan Cuti](https://github.com/JonathanZefanya/Human-Resource/blob/main/Screenshoot/user/cuti.png)  |
| Izin Sakit       | ![Izin Sakit](https://github.com/JonathanZefanya/Human-Resource/blob/main/Screenshoot/user/izinsakit.png)      |
| Melihat Gaji     | ![Melihat Gaji](https://github.com/JonathanZefanya/Human-Resource/blob/main/Screenshoot/user/gaji.png)    |

---
## Teknologi Yang Dipakai
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