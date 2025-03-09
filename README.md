# 📊 Proyek Analisis Data E-Commerce

## 🌟 Gambaran Proyek

Proyek ini melibatkan analisis dataset e-commerce untuk mendapatkan wawasan tentang perilaku pelanggan, performa penjualan, dan metrik-metrik penting lainnya. Analisis dilakukan dengan menggunakan Python dan berbagai pustaka analisis data.

---

## 📑 Daftar Isi

- [Gambaran Proyek](#-gambaran-proyek)
- [Instalasi](#-instalasi)
- [Penggunaan](#-penggunaan)
- [Struktur Proyek](#-struktur-proyek)
- [Sumber Data](#-sumber-data)
- [Analisis dan Visualisasi](#-analisis-dan-visualisasi)
- [Kesimpulan](#-kesimpulan)

---

## 💻 Instalasi

Untuk menjalankan proyek ini, Anda memerlukan Conda yang sudah terinstall di sistem Anda. Ikuti langkah-langkah berikut untuk menyiapkan proyek:

1. Kloning repositori:

   ```sh
   git clone https://github.com/yourusername/ecommerce-data-analysis.git
   cd ecommerce-data-analysis
   ```

2. Buat environment Conda:

   ```sh
   conda create --name ecommerce-analysis python=3.8
   ```

3. Aktifkan environment Conda:

   ```sh
   conda activate ecommerce-analysis
   ```

4. Install paket-paket yang diperlukan:
   ```sh
   pip install -r requirements.txt
   ```

---

## 🚀 Penggunaan

Untuk menjalankan analisis dan menghasilkan dashboard, ikuti langkah-langkah berikut:

1. Pastikan environment Conda sudah diaktifkan.
2. Jalankan aplikasi Streamlit:

   ```sh
   streamlit run dashboard/main.py
   ```

3. Buka browser web Anda dan akses `http://localhost:8501` untuk melihat dashboard.

---

## 📂 Struktur Proyek

Direktori proyek berisi file dan folder berikut:

- `dashboard/`: Berisi aplikasi dashboard Streamlit.
  - `main.py`: Script utama untuk dashboard.
- `data/`: Berisi file dataset.
- `notebooks/`: Berisi notebook Jupyter untuk analisis data.
- `README.md`: File README ini.
- `requirements.txt`: Daftar paket Python yang diperlukan.

---

## 📄 Sumber Data

Proyek ini menggunakan dataset berikut:

- `customers_dataset.csv`
- `geolocation_dataset.csv`
- `order_items_dataset.csv`
- `order_payments_dataset.csv`
- `order_reviews_dataset.csv`
- `orders_dataset.csv`
- `product_category_name_translation.csv`
- `products_dataset.csv`
- `sellers_dataset.csv`

---

## 📈 Analisis dan Visualisasi

Analisis meliputi poin-poin utama berikut:

1. **Analisis Penjualan Produk** 📦:

   - Identifikasi produk yang paling banyak dan paling sedikit terjual.
   - Visualisasi performa penjualan dari waktu ke waktu.

2. **Analisis Pengeluaran Pelanggan** 💰:

   - Menghitung total dan rata-rata pengeluaran pelanggan.
   - Visualisasi tren pengeluaran dari waktu ke waktu.

3. **Analisis Item Pesanan** 🛒:

   - Analisis jumlah item yang terjual.
   - Visualisasi kategori produk teratas dan terbawah berdasarkan penjualan.

4. **Analisis Skor Ulasan** ⭐:

   - Menghitung rata-rata skor ulasan.
   - Identifikasi skor ulasan yang paling umum.
   - Visualisasi distribusi skor ulasan.

5. **Demografi Pelanggan** 👥:

   - Analisis distribusi pelanggan berdasarkan negara bagian dan kota.
   - Visualisasi jumlah pelanggan dari setiap negara bagian dan kota.

6. **Analisis Status Pesanan** 📋:

   - Identifikasi status pesanan yang paling umum.
   - Visualisasi distribusi status pesanan.

7. **Analisis Geolokasi** 🗺️:
   - Plot distribusi geografis pelanggan pada peta.

---

## 🎯 Kesimpulan

Analisis ini memberikan wawasan berharga tentang perilaku pelanggan, performa penjualan, dan metrik penting lainnya. Wawasan ini dapat membantu meningkatkan strategi bisnis dan proses pengambilan keputusan.

### Temuan Utama:

- Kategori produk yang paling banyak terjual adalah `bed_bath_table` (tempat tidur, kamar mandi, meja).
- Kategori produk yang paling sedikit terjual adalah `auto` (otomotif).
- Performa penjualan stabil dari Januari hingga Mei, dengan fluktuasi signifikan pada bulan-bulan berikutnya.
- Tren pengeluaran pelanggan mengikuti pola yang mirip dengan performa penjualan.
- Pelanggan umumnya puas dengan layanan, dengan jumlah penilaian bintang 5 yang tinggi.
- Mayoritas pelanggan berada di wilayah tenggara dan selatan negara, terutama di kota-kota besar seperti São Paulo dan Rio de Janeiro.

Untuk analisis dan visualisasi yang lebih detail, silakan lihat notebook Jupyter dan dashboard Streamlit.
