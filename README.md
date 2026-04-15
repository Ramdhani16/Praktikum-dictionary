NAMA:M.ASROR RAMDHANI

NIM:22250019



#Program Pengolah Data Belanja (Python)

Program sederhana berbasis Python ini dirancang untuk mengelola data belanja harian menggunakan struktur data **Dictionary**, **List**, dan **Tuple**. Program ini mencakup fitur perhitungan total belanja, rekapitulasi barang, pencarian, hingga sistem diskon otomatis.

## 🚀 Fitur Utama

* **Manajemen Data Harian**: Data disimpan secara terstruktur berdasarkan hari.
* **Perhitungan Total**: Menghitung total belanja per hari dan total keseluruhan secara otomatis.
* **Rekapitulasi Barang**: Menggabungkan jumlah dan total harga untuk item yang sama dari hari yang berbeda.
* **Sorting**: Menampilkan daftar barang mulai dari yang paling banyak dibeli.
* **Pencarian Barang**: Mencari riwayat pembelian berdasarkan kata kunci nama barang.
* **Sistem Diskon**: Memberikan potongan harga 10% jika total belanja melebihi Rp 100.000.

## 🛠️ Struktur Data

Program ini menggunakan kombinasi struktur data sebagai berikut:
- **Dictionary**: Digunakan sebagai wadah utama (`belanjaan`) dengan *key* berupa nama hari.
- **List**: Digunakan untuk menampung sekumpulan item belanja di setiap hari.
- **Tuple**: Digunakan untuk menyimpan detail item (nama, jumlah, harga) agar data bersifat *immutable* (tidak mudah berubah secara tidak sengaja).

## 💻 Cara Menjalankan

1. Pastikan Anda sudah menginstal Python di perangkat Anda.
2. Clone repository ini atau unduh file `.py` terkait.
3. Jalankan program melalui terminal/CMD:
   ```bash
   python main.py
