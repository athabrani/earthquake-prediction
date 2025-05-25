# Panduan Penggunaan Kode Prediksi Gempa

## Setup

### Menambahkan Dataset:
- Unduh dataset `katalog_gempa.csv` dan tempatkan di folder `/content`.

### Menjalankan Kode:
- Buka notebook Jupyter (`prediksi_gempa_Fix.ipynb`) di IDE atau lingkungan Jupyter yang Anda pilih.
- Pastikan file `katalog_gempa.csv` ada di folder yang benar: `/content`.

### Menjalankan Setiap Sel:
- Jalankan setiap sel secara berurutan. Pastikan tidak ada error sebelum melanjutkan ke sel berikutnya.
- Kode ini mencakup model regresi linear di mana Anda dapat memprediksi data gempa berdasarkan koordinat dan kedalaman.

## Regresi Linear untuk Data Baru:
Ada dua metode untuk memprediksi data baru:
1. Menggunakan dataset yang telah di set sesuai dengan dataset.
2. Memasukkan data Anda sendiri pada variabel `new_data`.

Contoh:

```python
new_data = [[-7.01, 106.63, 121 ], [-7.83, 121.07 , 10]] # Jawa Barat dan Sulawesi Selatan
