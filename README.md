# 📊 Customer Segmentation & Market Campaign Analysis

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange.svg)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Manipulation-darkblue.svg)](https://pandas.pydata.org/)

Proyek ini bertujuan untuk menganalisis perilaku pelanggan dan melakukan segmentasi menggunakan teknik **Machine Learning**. Dengan memahami karakteristik unik dari setiap kelompok pelanggan, bisnis dapat mengoptimalkan strategi kampanye pemasaran agar lebih tepat sasaran.

## 📋 Ringkasan Proyek
Analisis ini menggunakan dataset kampanye pemasaran yang mencakup profil pelanggan, pola pengeluaran, dan respons terhadap kampanye sebelumnya. Fokus utama adalah mengelompokkan pelanggan berdasarkan kemiripan perilaku (Clustering).

## 🛠️ Alur Kerja (Workflow)
1. **Data Preprocessing & Cleaning**: 
   - Menangani nilai yang hilang dan menghapus *outliers* pada data pendapatan.
   - Transformasi fitur (misal: Menghitung umur dari tahun lahir).
2. **Feature Engineering**: 
   - Membuat fitur baru seperti `TotalAmount` (total belanja) dan `TotalChildren`.
3. **Dimensionality Reduction**: 
   - Menggunakan **PCA (Principal Component Analysis)** untuk menyederhanakan fitur tanpa kehilangan informasi penting.
4. **Clustering**: 
   - Menggunakan algoritma **K-Means** untuk membagi pelanggan ke dalam beberapa segmen optimal.
5. **Data Visualization**: 
   - Visualisasi cluster menggunakan Scatter Plot dan analisis rata-rata profil per segmen.

## 📈 Temuan Utama
* **High-Value Customers**: Kelompok dengan pendapatan tinggi yang sangat loyal pada produk Wine dan Meat.
* **Family Segment**: Pelanggan dengan anak cenderung lebih sensitif terhadap promosi dan memiliki pola belanja yang berbeda.
* **Campaign Response**: Identifikasi segmen mana yang paling responsif terhadap penawaran kampanye tertentu untuk meningkatkan ROI (Return on Investment).

## 🚀 Cara Menjalankan
1. Clone repositori ini:
   ```bash
   git clone [https://github.com/Satrioz/Customer-Segment.git](https://github.com/Satrioz/Customer-Segment.git)
