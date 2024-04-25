# Dataset Transjakarta

Dataset ini berisi data transaksi dari layanan transportasi Transjakarta. Data ini mencakup berbagai informasi tentang setiap transaksi, termasuk detail pelanggan, rute perjalanan, waktu, dan jumlah pembayaran.

## Deskripsi Kolom

- `transID`: ID transaksi unik untuk setiap transaksi
- `payCardID`: ID utama pelanggan. Kartu yang digunakan pelanggan sebagai tiket masuk dan keluar.
- `payCardBank`: Nama bank penerbit kartu pelanggan
- `payCardName`: Nama pelanggan yang tertanam di dalam kartu.
- `payCardSex`: Jenis kelamin pelanggan yang tertanam di dalam kartu
- `payCardBirthDate`: Tahun kelahiran pelanggan
- `corridorID`: ID Koridor / ID Rute sebagai kunci untuk pengelompokan rute.
- `corridorName`: Nama Koridor / Nama Rute berisi Awal dan Akhir untuk setiap rute.
- `direction`: 0 untuk pergi, 1 untuk pulang. Arah rute.
- `tapInStops`: ID Henti Tap In (masuk) untuk mengidentifikasi nama henti
- `tapInStopsName`: Nama Henti Tap In (masuk) di mana pelanggan masuk.
- `tapInStopsLat`: Garis lintang Tap In Stops
- `tapInStopsLon`: Garis Bujur Tap In Stops
- `stopStartSeq`: Urutan berhenti, berhenti pertama, berhenti kedua, dll. Terkait dengan arah.
- `tapInTime`: Waktu tap in. Tanggal dan waktu
- `tapOutStops`: ID Tap Out (Keluar) Stops untuk mengidentifikasi nama henti
- `tapOutStopsName`: Tap out (keluar) Nama henti di mana pelanggan tap out.
- `tapOutStopsLat`: Tap Out Stops Garis Lintang
- `tapOutStopsLon`: Tap Out Stops Garis Bujur
- `stopEndSeq`: Urutan berhenti, berhenti pertama, berhenti kedua, dll. Terkait dengan arah.
- `tapOutTime`: Waktu tap out. Tanggal dan waktu
- `payAmount`: Jumlah yang dibayar pelanggan. Beberapa gratis. Beberapa tidak.

## Tujuan Dataset

Dataset ini dikumpulkan untuk menganalisis pola perjalanan, preferensi pengguna, dan faktor-faktor lain yang memengaruhi penggunaan layanan Transjakarta. Analisis atas data ini diharapkan dapat membantu meningkatkan efisiensi operasional, kepuasan pengguna, dan manajemen sistem transportasi umum di Jakarta.
