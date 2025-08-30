# Proyek Data Engineering: Analisis Data Transaksi

## 📂 Struktur Direktori
- **data_pelanggan.csv**  
  Dataset pelanggan yang berisi informasi dasar pelanggan.

- **data_produk.csv**  
  Dataset produk yang berisi detail produk yang dijual.

- **data_transaksi.csv**  
  Dataset transaksi yang berisi catatan pembelian pelanggan.

- **MasterData.csv**  
  Gabungan dari berbagai dataset (pelanggan, produk, transaksi) sebagai master data untuk analisis.

- **data_processing.ipynb / data_processing.html**  
  Notebook untuk melakukan *data cleaning*, *data preprocessing*, beserta analisis yang detail.

- **resellerinsight.ipynb / resellerinsight.html**  
  Notebook untuk menyajikan insight praktis dari data yang sudah diproses:
  - Produk dengan penjualan tertinggi  
  - Segmentasi pelanggan  
  - Rekomendasi stok  

- **Studi Kasus.docx**  
  Dokumen yang berisi tugas yang harus dilaksanakan.  

- **README.md**  
  Dokumentasi proyek ini.

---

## 🎯 Tujuan Proyek
Proyek ini dibuat untuk mengelola data pelanggan, produk, dan transaksi dari reseller, kemudian mengolahnya agar dapat digunakan untuk analisis bisnis. Dengan pipeline sederhana ini, data mentah dapat dibersihkan, digabungkan, lalu menghasilkan insight praktis untuk pengambilan keputusan.

---

## 🔧 Alur Pengerjaan
1. **Persiapan Data**  
   - Dataset pelanggan, produk, dan transaksi disiapkan dalam format CSV.  

2. **Data Processing**  
   - Notebook `data_processing.ipynb` digunakan untuk:  
     - Membersihkan data (handling missing values, duplikasi, format tanggal).  
     - Menggabungkan data menjadi `MasterData.csv`.  
     - Menyediakan dataset siap pakai untuk analisis.  
     - Analisis detail sesuai yang diminta.

3. **Analisis & Insight**  
   - Notebook `resellerinsight.ipynb` digunakan untuk:  
     - Menyajikan hasil analisis secara ringkas sehingga reseller mudah untuk membacanya.  

---

## 📊 Output yang Dihasilkan
- Daftar produk berdasarkan urutan jumlah pembelian.  
- Segmentasi pelanggan berdasarkan perilaku transaksi.  
- Rekomendasi stok, minimum stock, dan reorder point untuk reseller.  

---

## 🚀 Cara Menjalankan
1. Clone repositori ini.  
2. Pastikan Python dan Jupyter Notebook sudah terpasang.  
3. Jalankan `data_processing.ipynb` terlebih dahulu untuk menghasilkan `MasterData.csv`.  
4. Lanjutkan dengan menjalankan `resellerinsight.ipynb` untuk melihat insight ringkas.  

---

## 📝 Catatan
- File dengan ekstensi `.Zone.Identifier` adalah metadata dari Windows dan tidak digunakan dalam analisis.  
- Semua hasil analisis dapat diekspor ke format HTML atau disertakan dalam laporan studi kasus.  
