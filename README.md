
# Analisis dan Prediksi Penjualan Sablon HAGA

### Introduction

Projek ini merupakan final project Big Data Analytics for Bussiness LB-20 terhadap analisa data untuk Sablon HAGA.

### File Structure

Terdapat 2 file dalam repository ini, yaitu:

- datasetsablonbulanan.csv
    - Merupakan dataset yang sudah melalui preprocessing.
- main.ipynb
    - Merupakan kode untuk jupyter notebook menggunakan colab

### Persyaratan

- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Prophet
- Matplotlib
- Scipy

Anda bisa menginstal semua pustaka yang diperlukan dengan menjalankan perintah berikut:

```bash
pip install pandas numpy scikit-learn prophet matplotlib scipy
```

### Cara Instalasi

1. Clone repositori ini ke mesin lokal Anda:

```bash
git clone https://github.com/ajinata84/sablon-ml.git
cd sablon-ml
```

2. Instal pustaka yang diperlukan:

```bash
pip install pandas numpy scikit-learn prophet matplotlib scipy
```

### Cara Penggunaan

1. Buka file `main.ipynb` menggunakan Jupyter Notebook atau Google Colab.
2. Jalankan setiap sel (cell) dalam notebook untuk melakukan analisis dan prediksi penjualan.
3. Notebook ini mencakup analisis data penjualan, prediksi pendapatan menggunakan Prophet, dan optimisasi stok menggunakan EOQ (Economic Order Quantity).

### Kode

- Pada Blok ke 4, terdapat kode untuk analisis data terhadap dataset. Terdapat beberapa analisis yaitu seperti Total Revenue By Shirt Type, Monthly Sales By Shirt Type, Total Sales Volume By Shirt Type.
- Pada Blok ke 5, terdapat implementasi Prophet terhadap prediksi income.
- Pada Blok ke 6, terdapat implementasi optimisasi stok menggunakan EOQ (Economic Order Quantity).
