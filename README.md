# Brazilian E-Commerce (Olist) - Customer Analytics Project

## 📌 Project Overview
Proyek ini bertujuan untuk menganalisis perilaku pelanggan menggunakan metode **Cohort Retention Analysis** dan **RFM Segmentation**. Dataset yang digunakan adalah data publik dari Olist (E-commerce terbesar di Brasil) yang mencakup lebih dari 100 ribu transaksi nyata dari tahun 2016 hingga 2018.

## 🛠️ Tech Stack
- **Python (Pandas, Seaborn, Matplotlib)**: Digunakan untuk tahap Data Cleaning awal, transformasi tipe data, serta pembuatan visualisasi akhir.
- **SQL (SQLite murni)**: Digunakan sebagai core analysis untuk menghitung metrik Cohort (pembelian pertama vs transaksi berulang) dan ekstraksi basis data RFM (Recency, Frequency, Monetary).

## 💡 Key Insights & Business Findings
1. **Masalah Retensi Rendah**: Hasil analisis Cohort menunjukkan penurunan drastis pada bulan kedua setelah pembelian pertama. Mayoritas pelanggan di platform ini adalah *one-time buyers* (belanja sekali lalu pergi).
2. **Dominasi Segmen Pasif**: Berdasarkan segmentasi RFM, toko ini sangat didominasi oleh kelompok *Lost Customers* (36.228 pelanggan) dan *New Customers* (36.224 pelanggan). Sementara pelanggan kategori *Champions / Loyal* hanya berjumlah 1.209 pelanggan.
3. **Potensi Nilai Tinggi (Outlier Loyal)**: Meskipun rata-rata retensi rendah, ditemukan pelanggan dengan loyalitas sangat ekstrem yang melakukan transaksi hingga **15 kali** dengan pengeluaran yang besar.

## 📂 Project Structure
- `customer_analytics.ipynb`: File Jupyter Notebook utama berisi dokumentasi kode Python & SQL.
- `README.md`: Penjelasan ringkas mengenai proyek untuk stakeholder.
