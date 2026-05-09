# CourtBook 🏸

CourtBook adalah sistem informasi berbasis web untuk pemesanan (booking) lapangan badminton. Proyek ini dirancang untuk memudahkan pemain mem-booking lapangan secara online tanpa perlu antri, sekaligus membantu pengelola (admin) dalam memanajemen jadwal lapangan secara praktis, efisien, dan terorganisir.

Proyek ini dikembangkan sebagai bagian dari Tugas / Proyek Akademik mata kuliah **Software Engineering**.

## ✨ Fitur Utama

Aplikasi ini dibagi menjadi dua antarmuka (User dan Admin) dengan fitur-fitur terintegrasi:

* **🖥️ Dashboard Booking:** Menampilkan jadwal lapangan yang tersedia secara *real-time*.
* **📅 Booking Lapangan:** Sistem reservasi cerdas yang mengunci jadwal otomatis untuk menghindari *double booking* (bentrok jadwal).
* **📤 Upload Bukti Pembayaran:** Pengguna dapat mengunggah bukti transfer langsung melalui sistem tanpa perlu konfirmasi manual via WhatsApp.
* **✅ Tracking Status Booking:** Pantau status reservasi secara langsung (Menunggu, Disetujui, atau Ditolak).
* **⚙️ Manajemen Lapangan (Admin):** Panel khusus untuk pengelola mengatur ketersediaan lapangan dan memvalidasi pembayaran.
* **📈 Laporan Booking (Admin):** Rekapitulasi pemesanan lengkap untuk keperluan monitoring dan dokumentasi.

## 👥 Peran Pengguna (Role)

1.  **Pemain (User):** Dapat melakukan login, melihat jadwal lapangan, melakukan booking, mengunggah bukti pembayaran, dan memonitor status reservasi.
2.  **Admin:** Mengelola data lapangan, jadwal bermain, memvalidasi bukti pembayaran, menyetujui/menolak booking, serta mencetak laporan.

## 🚀 Alur Pemesanan (Cara Kerja)

1.  **Login Akun** ke dalam sistem.
2.  **Lihat Jadwal Lapangan** yang tersedia sesuai tanggal dan waktu.
3.  **Pilih & Booking** slot lapangan yang diinginkan.
4.  **Upload Bukti Pembayaran** (screenshot transfer).
5.  **Verifikasi Admin** terhadap bukti pembayaran.
6.  **Selesai!** Booking disetujui dan pengguna mendapat konfirmasi.

## 🛠️ Teknologi yang Digunakan

* **Front-End:** HTML5, CSS3, Vanilla JavaScript
* **Styling:** [Tailwind CSS](https://tailwindcss.com/) (via CDN)
* **UI/UX:** Responsive Design, Glassmorphism UI, Light/Dark Mode Toggle, 3D Particle Canvas Animation
* **Metodologi Pengembangan:** Waterfall Model
* **Dokumentasi Desain:** UML Documentation

## 💻 Cara Menjalankan Proyek (Local Development)

Karena halaman ini bersifat statis (Front-End), kamu bisa menjalankannya dengan sangat mudah tanpa perlu instalasi server khusus:

1. Clone repository ini ke komputer lokal kamu:
   ```bash
   git clone [https://github.com/username-kamu/nama-repo-kamu.git](https://github.com/username-kamu/nama-repo-kamu.git)
