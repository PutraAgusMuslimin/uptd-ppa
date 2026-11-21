# uptd-ppa
Aplikasi UPTD-PPA ini dibuat untuk membantu petugas dalam mengelola data dan administrasi pelayanan perlindungan perempuan dan anak. Dengan adanya sistem ini, diharapkan pekerjaan menjadi lebih mudah, data tersimpan dengan rapi, dan proses pelayanan dapat berjalan lebih baik.

# Sistem Informasi UPTD-PPA

Aplikasi berbasis web yang dikembangkan untuk mendukung pengelolaan informasi dan administrasi pada Unit Pelaksana Teknis Daerah Perlindungan Perempuan dan Anak (UPTD-PPA).

Sistem ini dibangun menggunakan framework Laravel dengan tujuan membantu meningkatkan efektivitas pengelolaan data, mempermudah proses administrasi, serta mendukung pelayanan perlindungan perempuan dan anak.

## Teknologi yang Digunakan

- **Framework:** Laravel
- **Bahasa Pemrograman:** PHP
- **Database:** MySQL
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Tools:** Composer, Visual Studio Code, Laragon/XAMPP

## Fitur Sistem

Fitur aplikasi disesuaikan dengan kebutuhan operasional UPTD-PPA.

## Persyaratan Sistem

- PHP sesuai versi Laravel yang digunakan
- Composer
- MySQL / MariaDB
- Web Browser

## Instalasi

1. Clone repository:

   ```bash
   git clone https://github.com/USERNAME/uptd-ppa.git
   ```

2. Masuk ke direktori proyek:

   ```bash
   cd uptd-ppa
   ```

3. Install dependency:

   ```bash
   composer install
   ```

4. Salin file konfigurasi:

   ```bash
   cp .env.example .env
   ```

5. Buat application key:

   ```bash
   php artisan key:generate
   ```

6. Buat database MySQL dengan nama sesuai konfigurasi `.env`.

7. Atur koneksi database pada file `.env`:

   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=uptd_ppa
   DB_USERNAME=root
   DB_PASSWORD=
   ```

8. Jalankan migrasi database:

   ```bash
   php artisan migrate
   ```

9. Jalankan aplikasi:

   ```bash
   php artisan serve
   ```

10. Buka aplikasi melalui browser:

    ```text
    http://127.0.0.1:8000
    ```

## Pengembang

Dikembangkan sebagai proyek sistem informasi UPTD-PPA.

---

© 2026 Sistem Informasi UPTD-PPA.
