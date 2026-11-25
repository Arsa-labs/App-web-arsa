# App Web 0.2 Arsa — Prototype 0.1

## Menjalankan
1. Ekstrak folder/ZIP.
2. Buka `index.html` menggunakan browser modern (Chrome disarankan).
3. Data prototipe disimpan di `localStorage` browser pada perangkat yang digunakan.

## Yang sudah bisa diuji
- Navigasi enam menu.
- Rutinitas harian dan kalender Senin–Minggu dengan indikator 1–4 aktivitas.
- Target clipping harian dan arsip.
- Campaign clipping aktif dan tombol Selesai untuk mengarsipkan.
- Pencatatan pemasukan/pengeluaran, grafik bulanan/tahunan, dan riwayat.
- Input alokasi aset manual dan grafik donut.
- Arsip Data.

## Batasan prototipe
- Belum terhubung ke Supabase atau GitHub.
- Data lokal browser belum tersinkron antarperangkat dan dapat hilang jika data browser dihapus.
- Palet dasar sementara netral karena nilai warna dashboard 0.1 belum tersedia dalam catatan spesifikasi. Ganti token CSS `:root` setelah warna asli dipastikan.
- Ringkasan Keuangan di Beranda sementara memakai data hari ini.
- Penambahan nominal untuk kode aset yang sama digabungkan ke total aset.
- Belum ada autentikasi, backup cloud, atau pengaturan akun.
