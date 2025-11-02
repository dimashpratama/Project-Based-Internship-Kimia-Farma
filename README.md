# Project-Based-Internship-Kimia-Farma
Deskripsi Proyek

Proyek ini merupakan bagian dari Virtual Internship Experience (VIX) Kimia Farma — Big Data Analytics yang diselenggarakan oleh Rakamin Academy.
Tujuan utama proyek ini adalah untuk menganalisis kinerja bisnis Kimia Farma pada periode tahun 2020–2023 menggunakan Google BigQuery dan Google Looker Studio.
Melalui proyek ini, dilakukan proses pengolahan data transaksi, cabang, dan produk Kimia Farma, kemudian menghasilkan dashboard interaktif yang menampilkan performa pendapatan, profit, serta kepuasan pelanggan berdasarkan data historis.

Tujuan Analisis

Mengevaluasi kinerja bisnis Kimia Farma dari tahun 2020 hingga 2023.
Melakukan pengolahan data (data cleaning, joining, dan agregasi) dari beberapa sumber dataset.
Membuat tabel analisis terintegrasi yang berisi informasi lengkap dari seluruh dataset.
Membuat dashboard interaktif di Google Looker Studio untuk menampilkan insight seperti:
Tren pendapatan dari tahun ke tahun
Cabang dan provinsi dengan penjualan tertinggi
Cabang dengan rating terbaik dan terburuk
Distribusi profit berdasarkan wilayah Indonesia

Dataset yang Digunakan

Keempat dataset berikut diunggah ke Google BigQuery ke dalam dataset kimia_farma:
Nama Dataset	Keterangan
kf_final_transaction.csv	Data transaksi penjualan Kimia Farma (ID transaksi, harga, diskon, rating, dll.)
kf_product.csv	Data produk obat (ID produk, nama, kategori, harga)
kf_inventory.csv	Data stok produk di masing-masing cabang
kf_kantor_cabang.csv	Data cabang Kimia Farma (nama cabang, kota, provinsi, rating cabang)
Semua dataset ini kemudian digabungkan menjadi satu tabel utama bernama tabel_analisis menggunakan BigQuery SQL.






