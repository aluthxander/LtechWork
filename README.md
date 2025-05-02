# LtechWork

**LtechWork** adalah aplikasi berbasis web yang dikembangkan untuk mendukung kebutuhan manajemen pegawai dan tim Human Resource Development (HRD) dalam mengelola berbagai proses operasional terkait karyawan. Aplikasi ini dirancang agar intuitif, responsif, dan mudah digunakan, baik untuk tim HR maupun manajemen perusahaan.

Dengan **LtechWork**, perusahaan dapat melakukan digitalisasi seluruh proses pengelolaan pegawai secara efisien, mulai dari pencatatan data karyawan, pemantauan absensi dan cuti, hingga proses evaluasi kinerja. Aplikasi ini bertujuan untuk meningkatkan produktivitas divisi HR, mengurangi beban administrasi manual, dan memberikan visibilitas yang lebih baik terhadap performa dan status pegawai.

---

## 🌟 Tujuan Pengembangan

* Memberikan solusi digital terintegrasi untuk manajemen kepegawaian
* Menyediakan platform HR yang dapat dikustomisasi sesuai kebutuhan perusahaan
* Meningkatkan efisiensi dan akurasi dalam pengelolaan data SDM
* Mendukung pengambilan keputusan berbasis data dengan laporan dan analisis yang komprehensif

---

## 🧩️ Fitur Utama

* **Manajemen Data Pegawai**
  Menyimpan dan mengelola informasi personal, jabatan, status kepegawaian, serta dokumen-dokumen penting karyawan.

* **Absensi dan Cuti Online**
  Pegawai dapat melakukan presensi secara daring, mengajukan cuti, serta melihat histori absensi dan status pengajuan cuti.

* **Dashboard HR dan Manajemen**
  Tampilan ringkas yang menyajikan informasi penting seperti jumlah karyawan aktif, status kehadiran hari ini, notifikasi penting, dan grafik evaluasi.

* **Penilaian dan Evaluasi Kinerja**
  Sistem untuk memberikan dan mengelola penilaian kinerja secara berkala berdasarkan indikator tertentu.

* **Role dan Hak Akses**
  Manajemen level akses pengguna (admin, HR, pegawai) untuk menjaga keamanan dan integritas data.

* **Laporan dan Export Data**
  Menghasilkan laporan kepegawaian dan data evaluasi dalam format PDF/Excel untuk keperluan dokumentasi dan audit.

---

## 🛠️ Teknologi yang Digunakan

* **Backend**: [Laravel 12](https://laravel.com) (PHP 8.2)
  Framework backend modern yang cepat, aman, dan scalable.

* **Frontend**: [React](https://reactjs.org) + [Tailwind CSS](https://tailwindcss.com)
  UI responsif dan dinamis dengan pendekatan komponen modern dan desain utility-first.

* **Database**: MySQL/MariaDB
  Untuk menyimpan seluruh data pegawai, log aktivitas, dan histori evaluasi.

* **Tools**:

  * Composer (untuk dependency PHP)
  * NPM/Yarn (untuk dependency frontend)
  * Laravel Mix/Vite (untuk proses build dan bundling)

---

## 🚀 Cara Instalasi dan Menjalankan

1. **Clone Repository**

   ```bash
   git clone https://github.com/namakamu/LtechWork.git
   cd LtechWork
   ```

2. **Instalasi Backend**

   ```bash
   composer install
   cp .env.example .env
   php artisan key:generate
   ```

3. **Setup Database**

   * Buat database di MySQL (misal: `ltechwork_db`)
   * Atur koneksi DB di `.env`:

     ```
     DB_DATABASE=ltechwork_db
     DB_USERNAME=root
     DB_PASSWORD=
     ```

4. **Migrasi dan Seeder**

   ```bash
   php artisan migrate --seed
   ```

5. **Instalasi Frontend**

   ```bash
   npm install
   npm run dev
   ```

6. **Jalankan Server**

   ```bash
   php artisan serve
   ```

---

## 💡 Rencana Pengembangan Selanjutnya

* Integrasi dengan API untuk fingerprint/face recognition
* Notifikasi email dan WhatsApp untuk pengajuan cuti & evaluasi
* Modul rekrutmen & onboarding
* Modul training dan pengembangan SDM
* Dukungan multi perusahaan/divisi

---

## 🤝 Kontribusi

Kami terbuka untuk kontribusi dari developer lain. Silakan fork repositori ini dan kirim pull request untuk fitur atau perbaikan yang kamu buat. Laporkan bug atau usulan fitur baru melalui halaman [Issues](https://github.com/namakamu/LtechWork/issues).

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah lisensi [MIT](LICENSE).
Bebas digunakan, dimodifikasi, dan disebarluaskan sesuai dengan ketentuan lisensi.
