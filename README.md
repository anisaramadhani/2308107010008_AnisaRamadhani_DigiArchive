### DigiArchive - Sistem Pengelolaan Arsip Digital

- Nama : Anisa Ramadhani
- NIM  : 2308107010008

### Deskripsi Singkat Aplikasi
DigiArchive adalah aplikasi pengelolaan arsip digital berbasis web yang memudahkan organisasi atau individu dalam menyimpan, mencari, dan mengelola dokumen penting secara modern, aman, dan efisien. Aplikasi ini dilengkapi fitur manajemen arsip, pencarian, kategori, serta dashboard statistik.

### Penjelasan Kode & User Interface
### Struktur Folder Utama
- app/ : Berisi logic utama aplikasi.
- Models: Representasi data dan logika bisnis yang berhubungan dengan database.
- Controllers: Mengatur alur data dari model ke view dan sebaliknya (mengelola permintaan pengguna dan menentukan respon).
- resources/views/ : Menyimpan file tampilan berbasis Blade untuk halaman web.
- public/ : Asset publik (CSS, JS, gambar).
- routes/web.php : Mendefinisikan URL dan controller yang menangani request.
- `database/migrations/: File migrasi yang digunakan untuk membuat, mengubah, atau menghapus struktur tabel pada database.
- 'database/seeders/: File seeder untuk mengisi data awal ke database.

### User Interface
- Landing Page: Halaman Landing Page DigiArchive menampilkan gambaran umum aplikasi, fitur unggulan, tim pengembang, dan tombol aksi untuk memulai, dengan desain modern dan informatif.
- Login/Register: Halaman Login dan Daftar DigiArchive dirancang untuk memudahkan pengguna mengakses atau membuat akun dengan tampilan yang sederhana, modern, dan responsif.
- Dashboard: Halaman Dashboard menampilkan ringkasan data arsip secara real-time untuk membantu pengguna memantau aktivitas pengarsipan dengan mudah.
- Daftar Arsip: Halaman Daftar Arsip menampilkan data arsip secara lengkap dengan fitur pencarian, filter kategori, serta tombol untuk melihat, mengedit, dan menghapus arsip.
- Profil: Halaman Profil menampilkan informasi akun pengguna serta menyediakan fitur untuk memperbarui data dan mengubah password secara aman.

### Cara Instalasi Aplikasi
1. Clone repository
   - git clone [repo-url]
   - cd DigiArchive

2. Install dependency PHP
   - Composer install

3. Install dependency frontend
   - npm install
   - npm run dev

4. Copy file environment
   - cp .env.example .env

5. Generate application key
   - php artisan key:generate

6. Atur konfigurasi database di file .env
   - Sesuai dengan file .env.example

7. Jalankan migrasi dan seeder
   - php artisan migrate --seed

8. Jalankan aplikasi
   - php artisan serve

9. Akses aplikasi
   - Buka browser ke [http://localhost:8000]

10. Catatan
    - Pastikan sudah install PHP, Composer, Node.js, dan MySQL di komputer Anda.
    - Untuk login awal, cek data user hasil seeder di database.
