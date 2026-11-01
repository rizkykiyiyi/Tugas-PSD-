# Analisis Pendapatan Transaksi POS Tahun 2024–2025

## Deskripsi
Proyek ini merupakan analisis data transaksi Point of Sale (POS) menggunakan Python melalui Jupyter Notebook. Analisis dilakukan untuk mengetahui total pendapatan dari transaksi pada tahun 2024 dan 2025 berdasarkan dataset yang telah disediakan.

## Tujuan
- Membaca dan memahami dataset transaksi POS.
- Memeriksa dan menangani missing value.
- Membersihkan data agar dapat diolah dengan baik.
- Menghitung pendapatan dengan memperhatikan jumlah barang, harga satuan, dan diskon.
- Memisahkan transaksi berdasarkan status.
- Membandingkan total pendapatan tahun 2024 dan 2025 menggunakan tabel dan diagram batang.

## Metode Pengolahan Data
Pengolahan data dilakukan menggunakan Python dengan bantuan library Pandas, NumPy, dan Matplotlib.

Perhitungan pendapatan menggunakan rumus:

**Pendapatan = Jumlah Barang × Harga Satuan × (1 − Diskon / 100)**

Hanya transaksi dengan status **SELESAI** yang dihitung sebagai pendapatan penjualan. Transaksi BATAL dan RETUR tidak dimasukkan ke dalam perhitungan pendapatan.

## File dalam Repository
1. `Analisis_Transaksi_POS.ipynb` – Notebook berisi proses pengolahan dan analisis data.
2. `dataset_transaksi_bersih.csv` – Dataset yang telah melalui proses pembersihan.
3. `hasil_pendapatan_2024_2025.csv` – Hasil perhitungan pendapatan tahun 2024 dan 2025.

## Teknologi yang Digunakan
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib

## Hasil
Hasil akhir dari proyek ini berupa total pendapatan transaksi POS tahun 2024 dan 2025 yang ditampilkan dalam bentuk tabel dan diagram batang sehingga memudahkan perbandingan pendapatan dari kedua tahun tersebut.
