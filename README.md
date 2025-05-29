🚀 SINERGI - Aplikasi Presensi dan Cuti Karyawan
SINERGI adalah aplikasi berbasis R Shiny untuk membantu perusahaan mencatat kehadiran (presensi) dan pengajuan cuti karyawan. Aplikasi ini cocok untuk admin dan karyawan dengan fitur sesuai perannya.

✨ Fitur Utama
🏠 Halaman Awal
Ada gambar keren orang bekerja dengan opacity rendah, info tentang aplikasi, dan kontak customer service.

🔐 Login & Register
Bisa daftar dan login untuk admin atau karyawan dari berbagai perusahaan.

👩‍💼 Admin

Input presensi karyawan

Lihat daftar presensi dan cuti

Lihat grafik evaluasi beban kerja

👨‍💼 Karyawan

Lihat data presensi sendiri

Ajukan cuti dengan alasan

📅 Kalender Interaktif
Tampilkan tanggal presensi dan cuti secara visual.

🎨 Tampilan warna hijau cerah dengan logo SINERGI.


⚙️ Cara Pakai
Jalankan aplikasi di RStudio (paket: shiny, shinydashboard, dplyr, DT, lubridate, plotly).

Di halaman awal, pilih login atau lihat tentang kami.

Kalau belum punya akun, klik daftar dan isi data.

Setelah login, gunakan menu sesuai peranmu.

Admin bisa input dan pantau presensi/cuti, karyawan bisa ajukan cuti dan lihat presensi.


📂 Struktur File
app.R — kode utama aplikasi

data/ — tempat menyimpan file data (presensi, cuti, user)

www/ — tempat gambar untuk tampilan aplikasi (logo dan background)


⚠️ Catatan Penting
Data disimpan di file CSV lokal, cocok untuk perusahaan kecil atau testing.

Password belum dienkripsi, jadi jangan dipakai untuk data penting.

Untuk skala besar, lebih baik pakai database.


📞 Kontak Customer Service
Kalau ada pertanyaan atau butuh bantuan:
+62 877-3916-8516
