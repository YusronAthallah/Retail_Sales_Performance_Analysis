# 🛍️ Analisis Kinerja Penjualan Ritel Superstore (2014-2017)

## Ringkasan Proyek

Proyek ini bertujuan untuk menganalisis data transaksi global Superstore selama empat tahun (2014-2017) untuk memberikan **rekomendasi strategis** yang dapat ditindaklanjuti.

Fokus utama adalah mengidentifikasi **pola kerugian (Loss-Drivers)**, **efisiensi margin**, dan peluang pertumbuhan pada segmen pelanggan yang tepat. Output proyek ini memberikan dasar bagi pengambilan keputusan bisnis yang berorientasi pada profitabilitas.

***

## 🛠️ Metodologi dan Tools

Metode yang digunakan adalah **Exploratory Data Analysis (EDA)** untuk menemukan anomali dan pola, diikuti dengan perhitungan metrik bisnis penting seperti **Profit Margin (%)**.

### Tools yang Digunakan

* **Bahasa Pemrograman:** Python
* **Library:** `Pandas` (Data Cleaning & Manipulasi), `Matplotlib` & `Seaborn` (Visualisasi Data).
* **Dokumentasi:** Jupyter Notebook (`.ipynb`)
* **Data Source:** **`Sample - Superstore.csv`** (Diunggah ke Repositori Ini)

***

## 📈 Key Findings & Rekomendasi Bisnis

Analisis kode menghasilkan temuan kunci yang didukung oleh data:

### 1. Efisiensi Kategori Produk (Margin Profit)

Visualisasi ini menunjukkan margin keuntungan aktual yang dihasilkan oleh setiap kategori produk, metrik yang paling penting untuk mengukur efisiensi bisnis.



* **Insight Utama:** Kategori **Technology** adalah kategori yang paling efisien dengan Margin Keuntungan tertinggi.
* **Perhatian Kerugian:** Sub-kategori seperti **Tables** dan **Bookcases** dari kategori Furniture adalah penyumbang kerugian terbesar, yang harus segera diaudit.
* **Rekomendasi:** **Fokus pada Technology.** Tingkatkan anggaran promosi dan inventaris pada produk Technology. Lakukan peninjauan ulang pada kebijakan harga dan diskon untuk produk Furniture yang merugi.

### 2. Tren Penjualan Musiman

Grafik di bawah mengonfirmasi pola penjualan dari tahun ke tahun.



* **Insight:** Terdapat pola peningkatan penjualan yang jelas dan substansial pada **Kuarta IV (Q4)** setiap tahun (Oktober-Desember), yang merupakan puncak penjualan Superstore.
* **Rekomendasi:** **Optimalkan Sumber Daya Q4.** Sumber daya (stok, SDM, pemasaran) harus disiapkan dan dialokasikan secara maksimal sebelum awal Q4 untuk menangkap lonjakan permintaan.

### 3. Segmentasi Pelanggan dan Wilayah

#### Segmen Pelanggan yang Menguntungkan



* **Insight:** Segmen **Corporate** menghasilkan keuntungan total tertinggi. Berdasarkan perhitungan rata-rata profit per pesanan, segmen **Home Office** juga sangat efisien.
* **Rekomendasi:** **Targeting B2B.** Tingkatkan upaya akuisisi pelanggan yang menargetkan segmen bisnis (Corporate dan Home Office).

#### Kinerja Regional dan Kota Kerugian



[Image of Total Sales by Region]


* **Insight:** Wilayah **West** adalah pendorong penjualan utama, diikuti oleh East. Namun, analisis kode menemukan bahwa beberapa kota besar yang memiliki volume penjualan tinggi juga menyumbang kerugian terbesar (seperti Philadelphia dan Houston).
* **Rekomendasi:** **Mitigasi Kerugian Lokal.** Selidiki mengapa kota-kota besar tersebut merugi. Kemungkinan masalah ada pada biaya pengiriman yang tinggi atau pemberian diskon yang berlebihan.

***

## 🔗 Tautan Kode & Hasil

### 📄 Jupyter Notebook (Kode Lengkap)
Lihat semua langkah pembersihan data, *feature engineering*, dan kode visualisasi yang digunakan dalam proyek ini:
[Lihat Kode Lengkap (Jupyter Notebook)](Retail_Sales_Performance_Analysis.ipynb)

### 📈 Ringkasan Angka Kunci

* **Total Penjualan Keseluruhan:** \$ 2,297,200.86
* **Total Keuntungan Keseluruhan:** \$ 286,397.02
* **Rata-rata Profit Margin:** 12.47%

***
*Anda dapat menghubungi saya di [Masukkan Tautan LinkedIn atau Kontak Fastwork Anda] untuk pertanyaan atau peluang kerja freelance.*
