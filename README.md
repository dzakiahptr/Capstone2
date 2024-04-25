# Analisis Penggunaan Transjakarta

Untuk meningkatkan pemahaman tentang penggunaan Transjakarta dan meningkatkan efisiensi operasional, perlu dilakukan tiga jenis analisis: analisis perjalanan, analisis pendapatan, dan analisis demografi.

## 1. Analisis Perjalanan
Analisis perjalanan melibatkan pemahaman mendalam tentang pola perjalanan pengguna Transjakarta. Ini meliputi identifikasi rute yang paling sering digunakan, titik-titik transfer utama, dan waktu perjalanan yang paling umum. Dengan memahami pola perjalanan ini, Transjakarta dapat menyesuaikan jadwal dan rute untuk meningkatkan efisiensi dan kenyamanan pengguna.

**Stakeholder Terkait:**
- Manajemen Operasional Transjakarta: Untuk merencanakan penjadwalan dan rute bus yang optimal.
- Pengguna Transjakarta: Untuk memastikan pelayanan yang sesuai dengan kebutuhan dan preferensi mereka.

## 2. Analisis Pendapatan
Analisis pendapatan penting untuk memahami profil ekonomi pengguna Transjakarta. Ini termasuk tingkat pendapatan mereka, kecenderungan pembelian tiket atau kartu langganan, dan preferensi pembayaran. Analisis ini akan membantu Transjakarta dalam mengatur tarif yang adil dan dapat diakses oleh berbagai lapisan masyarakat, serta mengembangkan program diskon atau insentif bagi pengguna dengan pendapatan rendah.

**Stakeholder Terkait:**
- Departemen Keuangan Transjakarta: Untuk merencanakan kebijakan tarif.
- Pengguna Transjakarta: Untuk memastikan tarif yang terjangkau dan berbagai opsi pembayaran yang sesuai.

## 3. Analisis Demografi
Analisis demografi penting untuk memahami demografi pengguna Transjakarta, seperti usia, jenis kelamin, pekerjaan, dan tempat tinggal. Dengan memahami demografi pengguna, Transjakarta dapat menyesuaikan layanan dan fasilitas yang ditawarkan, misalnya dengan menyediakan layanan tambahan untuk kelompok pengguna tertentu atau meningkatkan aksesibilitas bagi mereka yang tinggal di area tertentu.

**Stakeholder Terkait:**
- Departemen Layanan Pelanggan Transjakarta: Untuk merencanakan layanan tambahan yang sesuai dengan kebutuhan demografis pengguna.
- Pengguna Transjakarta: Untuk memastikan aksesibilitas dan kenyamanan layanan yang diberikan.

Dengan kombinasi ketiga analisis ini, Transjakarta akan memiliki pemahaman yang lebih baik tentang kebutuhan dan preferensi pengguna, sehingga memungkinkan mereka untuk meningkatkan layanan secara keseluruhan dan memberikan pengalaman yang lebih baik bagi pengguna.

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
