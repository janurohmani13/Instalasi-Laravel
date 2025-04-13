# Panduan Instalasi Laravel Menggunakan Laragon

Panduan ini akan membantu kamu menginstall dan menjalankan Laravel menggunakan Laragon di Windows.

---

## 1. Install Laragon

Langkah pertama adalah menginstall Laragon. Kamu bisa download installer dari [https://laragon.org](https://laragon.org).

![Install Laragon](Install-laragon.png)

---

## 2. Jalankan Laragon

Setelah selesai menginstal, buka Laragon lalu klik tombol **Start All** untuk menyalakan semua service (Apache, MySQL, dll).

![Klik Start Laragon](Klik-Start-laragon.png)

---

## 3. Buka Terminal Laragon

Klik menu **Terminal** di Laragon untuk membuka terminal bawaan.

![Klik Terminal Laragon](Klik-Terminal-Laragon.png)

---

## 4. Cek Composer & Buat Project Laravel

Sebelum membuat project, pastikan Composer sudah terinstal dengan perintah:

```bash
composer --version
```Jika sudah, buat project Laravel dengan perintah:
composer create-project laravel/laravel:^11.0 nama-project
Setelah selesai, jalankan server Laravel:
php artisan serve
Jika semua langkah berhasil, kamu bisa membuka project Laravel di browser melalui:
http://localhost:8000


