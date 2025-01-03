# Kimia Farma Big Data Analytics Project Based Internship x Rakamin Academy
Project Based Internship merupakan sebuah program kolaborasi Rakamin Academy dan Kimia Farma Big Data Analytics. Program ini membantu mempersiapkan karir saya sebagai seorang data analyst dengan menyediakan akses ke materi pembelajaran dasar berupa Article Review (materi bacaan) dan Company Coaching Video (video learning), serta tugas akhir yang akan menjadi portfolio dari program ini.

## Portfolio Project
Sebagai seorang Big Data Analytics Intern di Kimia Farma, saya diberikan salah satu proyek utama yaitu mengevaluasi kinerja bisnis Kimia Farma dari tahun 2020 hingga 2023 dengan tugas-tugas sebagai berikut:

### Part 1 - Import Dataset ke BigQuery
Pada tahapan pertama dilakukan import data ke Google BigQuery dengan data-data yang sudah saya cantumkan di folder dataset.

### Part 2 - Membuat Tabel Analisa
Tabel analisa dibuat berdasarkan hasil aggregasi dari keempat tabel yang sudah diimport sebelumnya dengan kolom-kolom pada tabel sebagai berikut:
- transaction_id: kode id transaksi
- date: tanggal transaksi dilakukan
- branch_id: kode id cabang Kimia Farma
- branch_name: nama cabang Kimia Farma
- kota: kota cabang Kimia Farma
- provinsi: provinsi cabang Kimia Farma
- rating_cabang: penilaian konsumen terhadap cabang Kimia Farma
- customer_name: nama customer yang melakukan transaksi
- product_id: kode produk obat
- product_name: nama obat
- actual_price: harga obat
- discount_percentage: persentase diskon yang diberikan pada obat
- persentase_gross_laba: persentase laba yang seharusnya diterima dari obat dengan
  ketentuan sebagai berikut:
  * Harga <= Rp 50.000 -> laba 10%
  * Harga > Rp 50.000 - 100.000 -> laba 15%
  * Harga > Rp 100.000 - 300.000 -> laba 20%
  * Harga > Rp 300.000 - 500.000 -> laba 25%
  * Harga > Rp 500.000 -> laba 30%
- nett_sales: harga setelah diskon
- nett_profit: keuntungan yang diperoleh Kimia Farma
- rating_transaksi: penilaian konsumen terhadap transaksi yang dilakukan

### Part 3 - Membuat Dashboard
Membuat sebuah dashboard analisis kinerja Kimia Farma tahun 2020-2023 dengan Google Looker Studio berdasarkan tabel analisa yang sudah dibuat sebelumnya. Dibawah ini merupakan cakupan dashboard yang saya buat:
1. Perbandingan pendapatan Kimia Farma dari tahun ke tahun
2. Top 10 total transaksi cabang provinsi
3. Top 10 nett sales cabang provinsi
4. Top 5 cabang dengan rating tertinggi, namun rating transaksi rendah
5. Indonesia's Geo Map untuk total profit masing-masing provinsi

  



