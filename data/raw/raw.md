# 📂 Deskripsi Dataset Raw

## 📄 Nama File
`Online Retail.xlsx`

## 🌐 Sumber Dataset
UCI Machine Learning Repository  
🔗 [https://archive.ics.uci.edu/ml/datasets/Online+Retail](https://archive.ics.uci.edu/ml/datasets/Online+Retail)

## 📌 Deskripsi Umum
Dataset ini merupakan data transaksi penjualan dari sebuah perusahaan e-commerce berbasis di Inggris, yang dikumpulkan selama periode **Desember 2010 hingga Desember 2011**.

Dataset digunakan untuk analisis pola pembelian konsumen dan penggalian aturan asosiasi antar produk menggunakan metode data mining (Apriori & FP-Growth).

## 🧾 Kolom pada Dataset

| Kolom        | Deskripsi                                                                 |
|--------------|---------------------------------------------------------------------------|
| InvoiceNo    | Nomor faktur/nota untuk setiap transaksi                                  |
| StockCode    | Kode unik untuk setiap produk                                              |
| Description  | Nama atau deskripsi produk                                                |
| Quantity     | Jumlah unit barang yang dibeli dalam transaksi tersebut                   |
| InvoiceDate  | Tanggal dan waktu saat transaksi terjadi                                  |
| UnitPrice    | Harga per unit produk (dalam Pound Sterling)                              |
| CustomerID   | ID unik pelanggan (jika diketahui)                                        |
| Country      | Negara asal pelanggan (umumnya United Kingdom)                            |

## 🧼 Ciri Khas Data Mentah
- Terdapat **nilai kosong** pada kolom `CustomerID` dan `Description`.
- Beberapa baris bersifat **duplikat identik**.
- Format angka desimal menggunakan koma `,` (misalnya `2,55`), perlu dikonversi ke titik `.` saat diproses.
- Terdapat lebih dari 500 ribu baris transaksi dari berbagai negara, tetapi fokus penelitian dibatasi hanya pada **transaksi dari United Kingdom**.

## 📁 Lokasi File
Semua file mentah disimpan di dalam folder:/data/raw/Online Retail.xlsx
