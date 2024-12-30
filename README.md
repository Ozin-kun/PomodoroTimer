# PomodoroTimer Web Application

## Gambaran Umum
Aplikasi web **Pomodoro Timer** dirancang untuk membantu pengguna meningkatkan produktivitas dengan menggunakan **Teknik Pomodoro**. Teknik ini melibatkan pergantian antara sesi kerja fokus dan istirahat singkat untuk meningkatkan konsentrasi dan mengurangi kelelahan mental. Selain itu, aplikasi ini dilengkapi dengan **Daftar Tugas** untuk mengelola pekerjaan secara efektif dan **playlist Spotify** bawaan untuk pengalaman kerja yang lebih baik.

## Fitur-Fitur
- **Timer untuk Sesi Belajar dan Istirahat**: Secara otomatis bergantian antara waktu belajar dan istirahat.
- **Durasi Timer yang Dapat Dikustomisasi**: Pengguna dapat mengatur durasi belajar dan istirahat sesuai preferensi.
- **Daftar Tugas**: Memungkinkan pengguna untuk menambah, menandai selesai, dan menghapus tugas.
- **Integrasi Spotify**: Playlist Spotify bawaan untuk menyediakan musik latar.
- **Daftar Tugas yang Persisten**: Menyimpan tugas dalam penyimpanan lokal agar tetap tersedia di sesi berikutnya.
- **Notifikasi Bertema**: Notifikasi SweetAlert2 dengan gambar dan timer khusus.

---

## Teknologi yang Digunakan

### Frontend:
1. **HTML5** - Bahasa markup untuk membangun struktur aplikasi.
2. **CSS3** - Styling menggunakan TailwindCSS untuk desain yang responsif dan modern.
3. **JavaScript (ES6)** - Fungsi inti dan logika untuk timer dan daftar tugas.

### Library:
1. **jQuery** - Mempermudah manipulasi DOM dan penanganan event.
2. **SweetAlert2** - Untuk notifikasi dan alert yang bergaya.
3. **Font Awesome** - Ikon untuk tombol dan elemen antarmuka.

### Alat Tambahan:
1. **TailwindCSS** - Framework CSS berbasis utilitas untuk desain cepat dan responsif.
2. **Spotify Embed** - Untuk mengintegrasikan musik latar.

---

## Cara Menggunakan Aplikasi

### Memulai
1. Buka aplikasi di browser web.
2. Halaman utama menampilkan **Pomodoro Timer** dengan sesi belajar dan istirahat, **Daftar Tugas**, dan pemutar Spotify.

### Timer
- **Mulai Timer Belajar**: Tekan tombol Play (▶️) untuk memulai timer belajar.
- **Jeda Timer Belajar**: Tekan tombol Pause (⏸) untuk menjeda/melanjutkan.
- **Reset Timer Belajar**: Tekan tombol Reset (♻️) untuk mengatur ulang timer belajar.
- **Beralih ke Istirahat**: Aplikasi secara otomatis beralih ke timer istirahat setelah timer belajar selesai.
- **Sesuaikan Durasi Timer**:
  1. Klik tombol Pengaturan (⚙️).
  2. Masukkan durasi yang diinginkan untuk waktu belajar dan istirahat.
  3. Klik **Simpan** untuk menerapkan perubahan.

### ToDo List
- **Tambah Tugas**: Ketik tugas di bagian input dan klik tombol "+".
- **Tandai Tugas Selesai**: Centang kotak di samping tugas.
- **Hapus Tugas**: Klik ikon (🗑) di samping tugas.
- **Tugas Persisten**: Tugas disimpan dalam penyimpanan lokal dan tetap tersedia setelah halaman dimuat ulang.

### Pemutar Spotify
- **Putar Musik Latar**: Gunakan playlist Spotify bawaan untuk sesi fokus.

---

## Cara Kerja Aplikasi

### Fungsi Pomodoro Timer
1. **Timer Belajar**:
   - Memulai hitungan mundur untuk durasi belajar yang telah dikonfigurasi.
   - Memperbarui total waktu belajar dan jumlah siklus saat sesi berakhir.
   - Beralih ke timer istirahat dengan notifikasi yang menandai bahwa saat istirahat dimulai.

2. **Timer Istirahat**:
   - Memulai hitungan mundur untuk durasi istirahat yang telah dikonfigurasi.
   - Memberi tahu pengguna saat istirahat selesai dan beralih kembali ke timer belajar.

### Fungsi ToDo List
1. Menambahkan tugas baru secara dinamis ke DOM.
2. Menyimpan tugas dalam penyimpanan lokal untuk memastikan tugas tetap tersedia setelah halaman dimuat ulang.
3. Mengelola penyelesaian dan penghapusan tugas dengan pembaruan waktu nyata.

### Notifikasi SweetAlert2
- Notifikasi memberi tahu pengguna pada peristiwa penting, seperti akhir sesi belajar atau istirahat.
- Gambar khusus digunakan untuk pengalaman pengguna yang lebih menarik.
- Notifikasi otomatis ditutup setelah 5 detik.

---

## Pengembangan di Masa Depan
1. Menambahkan **dashboard statistik** untuk melacak produktivitas harian/mingguan.
2. Mengimplementasikan **mode gelap** untuk aksesibilitas pengguna yang lebih baik.
3. Mengintegrasikan dengan backend untuk memungkinkan akun pengguna dan sinkronisasi tugas.
4. Menambahkan fitur untuk membuat beberapa profil timer untuk tugas yang berbeda.

---

## Kredit
- **Pengembang**: Rozin Gunagraha
- **Ikon**: Font Awesome
- **Musik**: Spotify
- **Notifikasi**: SweetAlert2

