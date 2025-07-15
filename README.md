# RT006-PAH

Static Websites of RT.006 Pesona Anggrek Harapan

## Changelog

### [v1.3.0] - 2025-07-15

#### Changed

- Mengganti judul teks "RT 006" dengan logo gambar di kedua halaman (index.html dan 17an.html) untuk menciptakan identitas visual yang seragam.
- Warna tombol WhatsApp disesuaikan dengan gradien merah agar selaras dengan tema utama halaman portal.
- Daftar "Agenda Terdekat" pada halaman portal disederhanakan untuk hanya menampilkan dua acara utama: "Acara Perlombaan HUT RI" dan "Malam Kebersamaan Warga".

#### Fixed

- Memperbaiki tautan pada logo di halaman HUT RI (17an.html) agar mengarah kembali ke halaman portal utama (index.html), meningkatkan alur navigasi pengguna.
- Mengimplementasikan teknik "responsive wrapper" pada iframe Google Maps untuk mengatasi masalah overflow dan memastikan peta tampil proporsional di semua ukuran perangkat.

### [v1.2.0] - 2025-07-15

#### Changed

- Ikon logo pada tombol WhatsApp diubah menjadi warna putih untuk meningkatkan kontras dan visibilitas terhadap latar belakang gradien.
- Ikon pada bagian "Jadwal Kegiatan" di halaman HUT RI diseragamkan menggunakan satu ikon kalender dari Font Awesome untuk tampilan yang lebih rapi dan profesional.
- Daftar "Agenda Terdekat" pada halaman portal disederhanakan untuk hanya menampilkan dua acara utama: "Acara Perlombaan HUT RI" dan "Malam Kebersamaan Warga".

#### Removed

- Bagian "Informasi Penting" yang berisi tiga kartu telah dihapus dari halaman portal utama.

#### Added

- Menambahkan bagian baru "Lokasi & Kontak Kami" di halaman portal yang menampilkan Google Maps, alamat, dan tautan media sosial.

### [v1.1.0] - 2025-07-15

#### Added

- Menambahkan pustaka Font Awesome di kedua halaman untuk standarisasi ikon. Ikon WhatsApp dan beberapa ikon jadwal telah diperbarui.

#### Changed

- Bagian "Pengumuman Terkini" di halaman portal diubah menjadi "Struktur Pengurus RT" dengan desain kartu 3 kolom yang modern, lengkap dengan foto placeholder dan tombol WhatsApp.
- Tampilan header pada halaman HUT RI disesuaikan agar konsisten dengan header di halaman portal, menggunakan latar belakang putih dan menjadi sticky (tetap di atas).
- Bagian "Agenda Terdekat" di halaman portal diubah menjadi sistem kartu acara yang dapat diklik, dengan efek hover dan penanda untuk acara yang akan datang (TBA).
- Bagian "Panitia Pelaksana" di halaman HUT RI didesain ulang menggunakan tata letak grid untuk tampilan yang lebih terstruktur.

### [v1.0.0] - 2025-07-15

#### Added

- Inisialisasi halaman utama untuk portal informasi warga RT 006.
- Pembuatan halaman khusus untuk acara HUT Kemerdekaan RI ke-80 berdasarkan transkripsi dokumen. Halaman ini mencakup:
  - Hitung mundur (countdown) menuju acara.
  - Jadwal kegiatan yang terperinci.
  - Daftar perlombaan dengan filter kategori.
  - Susunan panitia pelaksana.
  - Visualisasi anggaran dan detail partisipasi.

#### Fixed

- Memperbaiki masalah background-image SVG yang tidak tampil dengan menggantinya menggunakan pola gradien CSS yang lebih andal.
- Memperbaiki logika klik pada kartu agenda di halaman portal agar dapat mengarahkan ke URL tujuan jika tersedia, dan hanya menampilkan alert jika statusnya "TBA".
