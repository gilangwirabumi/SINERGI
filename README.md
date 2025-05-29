SINERGI - Sistem Manajemen Presensi dan Cuti Karyawan

SINERGI adalah aplikasi berbasis Shiny yang dirancang untuk membantu perusahaan mengelola presensi dan pengajuan cuti karyawan secara mudah dan efisien. Aplikasi ini mendukung peran admin dan karyawan, dengan fitur login, register, input dan monitoring presensi, pengajuan cuti, serta evaluasi beban kerja.

Fitur Utama

-Landing Page dengan tampilan menarik dan informasi customer service.
-Login dan Register multi perusahaan dengan role admin/karyawan.

-Admin dapat:
     Input presensi karyawan.
     Melihat data presensi dan cuti seluruh karyawan perusahaan.
     Mengevaluasi beban kerja berdasarkan data presensi dan cuti.
     
-Karyawan dapat:
      Melihat data presensi sendiri.
      Mengajukan cuti dengan alasan.
      Tampilan kalender interaktif untuk melihat presensi dan cuti dalam satu timeline.


Penyimpanan data sederhana menggunakan file CSV lokal (mudah dimodifikasi ke database lain).

Instalasi

Pastikan R dan paket berikut sudah terinstall:

"install.packages(c("shiny", "shinydashboard", "dplyr", "DT", "lubridate", "plotly"))"



Cara Menjalankan

Clone atau download repository ini.

Buka file app.R di RStudio.

Jalankan aplikasi dengan menekan tombol Run App.

Halaman awal akan menampilkan landing page.

Klik Login untuk masuk atau Tentang Kami untuk informasi aplikasi.

Jika belum punya akun, lakukan registrasi terlebih dahulu.

Setelah login, fitur akan muncul sesuai peran (admin/karyawan).

Struktur Folder dan File

/SINERGI
|-- app.R
|-- data/
|   |-- data_presensi.csv
|   |-- data_cuti.csv
|   |-- users.csv
|-- README.md
data/ : Folder penyimpanan data presensi, cuti, dan user.


Cara Penggunaan

-Admin
   Setelah login sebagai admin, akses menu untuk input presensi karyawan, melihat data presensi dan cuti, serta evaluasi beban kerja.
   
   Admin dapat memilih tanggal dan karyawan untuk mencatat presensi.
   
-Karyawan
   Login dengan akun karyawan untuk melihat presensi sendiri dan mengajukan cuti.
   
   Pengajuan cuti akan direkam dan bisa dilihat oleh admin.
   

Package yang Digunakan:

R dan Shiny untuk antarmuka interaktif.

shinydashboard untuk tata letak dashboard yang profesional.

dplyr dan lubridate untuk manipulasi data tanggal dan tabel.

plotly untuk visualisasi data interaktif.

Penyimpanan data sederhana menggunakan file CSV.


Catatan

Aplikasi ini menggunakan penyimpanan data lokal berupa file CSV, cocok untuk penggunaan skala kecil atau demo.
Untuk penggunaan skala besar, direkomendasikan menghubungkan dengan database seperti PostgreSQL atau Supabase.
Keamanan password saat ini sederhana (plaintext), disarankan menambahkan hashing dan validasi lebih lanjut untuk produksi.

Kontak
Untuk pertanyaan atau dukungan, silakan hubungi:

Customer Service SINERGI

📞 +62 877-3916-8516

✉️ gilang.wira.wiri@gmail.com 
