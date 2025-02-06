# Chatapp

Aplikasi chatapp sederhana yang dibangun menggunakan HTML, CSS, JavaScript, AJAX, PHP, dan MySQL. Aplikasi ini memungkinkan pengguna untuk berkomunikasi secara real-time dalam sebuah chat room.

## Fitur

- **Registrasi dan Login**: Pengguna dapat membuat akun baru dan login ke aplikasi.
- **Chat Room**: Pengguna dapat mengirim dan menerima pesan secara real-time.
- **AJAX**: Menggunakan AJAX untuk memperbarui pesan tanpa perlu me-refresh halaman.
- **Responsive Design**: Desain yang responsif untuk penggunaan di berbagai perangkat.

## Persyaratan

- XAMPP (Apache, MySQL, PHP)
- Browser modern (Chrome, Firefox, Edge, dll.)

## Instalasi

1. **Clone Repository**:
   ```bash
   git clone https://github.com/username/chatapp.git
   ```

2. **Jalankan XAMPP:**
- Buka XAMPP Control Panel.
- Start Apache dan MySQL.

3. **Import Database:**
- Buka phpMyAdmin di browser (http://localhost/phpmyadmin).
- Buat database baru dengan nama `chatapp`.
- Import file `chatapp.sql` yang ada di folder `database` ke dalam database `chatapp`.

4.**Konfigurasi Koneksi Database:**
- Buka file `config.php` di folder `php` dan sesuaikan dengan konfigurasi database Anda:

```
<?php
$host = 'localhost';
$db = 'chatapp';
$user = 'root';
$pass = '';
$conn = new mysqli($host, $user, $pass, $db);
?>
```

5. **Jalankan Aplikasi:**
- Letakkan folder `chatapp` di dalam direktori `htdocs` XAMPP.
- Buka browser dan akses `http://localhost/chatapp`.

