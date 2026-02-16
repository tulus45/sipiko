# ✨ SiPiko - Sistem Piket Kelas Otomatis

**SiPiko** adalah aplikasi berbasis web sederhana untuk membuat jadwal piket kebersihan kelas dan petugas doa secara otomatis, adil, dan merata. Dirancang untuk membantu Bapak/Ibu Guru serta Pengurus Kelas dalam mengatur tugas mingguan siswa dengan cepat.

🔗 **Link Aplikasi:** [Klik di sini untuk membuka SiPiko](https://tulus45.github.io/sipiko/)  

---

## 🚀 Fitur Utama

* **🎲 Sistem Acak Cerdas (Estafet):** Pembagian tugas Laki-laki dan Perempuan dilakukan secara bersambung (estafet) agar penyebaran petugas merata di setiap hari.
* **🗓️ Smart Calendar:** Pilih tanggal berapa saja, sistem otomatis mendeteksi hari Senin di minggu tersebut.
* **🛡️ Anti-Duplikat:** Otomatis menghapus nama ganda yang tidak sengaja terinput di kolom yang sama.
* **⚖️ Mode Murni vs Rata:** Pilihan fleksibel untuk membiarkan jadwal murni (satu siswa satu tugas) atau dipaksa rata (ada yang rangkap tugas).
* **📱 Mobile Friendly:** Tampilan otomatis menyesuaikan layar HP dan Laptop.
* **🖨️ Siap Cetak (PDF):** Layout otomatis menjadi *Landscape* dan Rata Tengah saat dicetak ke kertas A4.

---

## 📘 Panduan Penggunaan

### 1️⃣ Langkah Persiapan & Input
* Masukkan nama siswa **Laki-laki** di Kolom Biru (Kiri) dan **Perempuan** di Kolom Pink (Kanan).
* Sistem otomatis merapikan huruf menjadi **HURUF KAPITAL**.
* **Aturan Duplikat:** Nama ganda di kolom gender yang sama akan dihapus otomatis. Pastikan input nama sesuai kolom gendernya.

### 2️⃣ Pengaturan Jadwal
* **🔄 Ratakan Jumlah Siswa?**
    * **Dicentang:** Jumlah petugas per hari dipaksa sama rata (konsekuensi: ada siswa piket 2x).
    * **Tidak Dicentang (Default):** Tidak ada yang rangkap, namun jumlah petugas di hari Jumat mungkin lebih sedikit (Prioritas Jumat terakhir).
* **📅 Kalender Pintar:** Anda bebas memilih tanggal berapa saja (Senin-Minggu), SiPiko otomatis mendeteksi awal minggu (Senin) tersebut.

### 3️⃣ Membaca Hasil & Ulang
* **Indikator Gender:** Ditandai dengan titik warna (🔵 Biru = Laki-laki, 🔴 Merah = Perempuan).
* Petugas doa dipilih secara acak terpisah dari petugas piket.
* Jika hasil dirasa kurang pas, klik tombol **🔄 Ulang** di bagian atas untuk mengacak kembali.

### 4️⃣ Cetak PDF
* Klik tombol hijau **🖨️ Simpan PDF**.
* Pilih *Destination/Tujuan* printer sebagai **"Save as PDF"**.
* Layout akan otomatis menyesuaikan kertas A4 (Landscape) agar rapi.

---

## 💡 Tips untuk Guru
> *"Disarankan untuk mengacak jadwal kembali setiap hari Sabtu. Rotasi mingguan mengajarkan siswa tentang keadilan dan adaptasi, serta memecahkan 'geng' di kelas agar siswa saling mengenal teman kerja baru."*

---

### 💻 Teknologi
Dibuat menggunakan HTML5, CSS3, dan JavaScript (Vanilla). Tanpa *framework* berat, sehingga sangat ringan dan cepat diakses.

Created with ❤️ by **The Alus**
