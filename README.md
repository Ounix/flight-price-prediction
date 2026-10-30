# Flight Price Prediction

## Deskripsi Proyek
Proyek ini memecahkan masalah prediksi harga tiket pesawat menggunakan pendekatan Machine Learning. Model menganalisis berbagai fitur seperti maskapai penerbangan, kelas kabin (Economy vs Business), durasi perjalanan, jumlah transit, dan waktu keberangkatan untuk mengestimasi harga tiket secara akurat.

## Sumber Data
Data yang digunakan berasal dari dataset penerbangan EaseMyTrip yang tersedia di Kaggle, terbagi menjadi data penerbangan kelas Ekonomi dan Bisnis.

## Struktur Proyek
- `data/`: Direktori penyimpanan dataset mentah (`business.csv`, `economy.csv`) dan data bersih.
- `notebooks/`: Direktori file Jupyter Notebook yang mencakup tahap Exploratory Data Analysis (EDA), Data Preprocessing, dan Pelatihan Model.

## Cara Menjalankan Proyek
1. Clone repository ini ke mesin lokal Anda.
2. Pastikan Anda telah menginstal dependensi yang dibutuhkan:
   `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`
3. Buka file `.ipynb` di dalam folder `notebooks/` untuk melihat dan menjalankan seluruh alur pemrosesan data hingga evaluasi model.

## Kontribusi Tim
Proyek ini dikerjakan oleh tiga anggota dengan pembagian fokus tugas sebagai berikut:
1. **Muhammad Garnida Barreta Novianto**: Business Understanding dan Data Gathering & Ingestion
2. **Azarya Shalom Widura**: Exploratory Data Analysis (EDA)
3. **Muhammad Dhimas Setiaji**: Data Cleaning dan Preprocessing