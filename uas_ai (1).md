# UAS Kecerdasan Buatan

## 1. Judul Proyek
**Klasifikasi Jenis Bunga Iris Menggunakan Berbagai Algoritma Machine Learning**

## 2. Business Understanding
- Permasalahan: Identifikasi otomatis jenis bunga berdasarkan panjang dan lebar sepal serta petal.
- Tujuan: Membangun model klasifikasi untuk mengklasifikasikan bunga Iris ke dalam tiga jenis.
- Pengguna: Peneliti botani, pengajar, dan sistem klasifikasi otomatis.
- Manfaat: Mempermudah klasifikasi bunga secara cepat dan akurat.

## 3. Data Understanding
- Sumber data: Dataset publik "Iris"
- Fitur:
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm
  - Species (target)
- Ukuran data: 150 baris, 5 fitur + 1 target
- Tipe data: Numerik dan kategorikal

## 4. Exploratory Data Analysis (EDA)
- Visualisasi distribusi fitur dilakukan dengan pairplot dan heatmap.
- Ditemukan korelasi tinggi antara panjang dan lebar petal.
- Kelas target seimbang (masing-masing 50 data).

## 5. Data Preparation
- Kolom `Id` dihapus karena tidak relevan.
- Label encoding digunakan untuk kolom `Species`.
- Data dinormalisasi menggunakan `StandardScaler`.
- Data dibagi 80% untuk training dan 20% untuk testing.

## 6. Modeling
- Model yang digunakan:
  - Decision Tree
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Naive Bayes
- Implementasi dilakukan di notebook Jupyter.

## 7. Evaluation
- Evaluasi menggunakan confusion matrix, accuracy, precision, recall, f1-score.
- Semua model memiliki performa tinggi pada dataset ini karena dataset bersih dan jelas terpisah antar kelas.

## 8. Kesimpulan dan Rekomendasi
- Tujuan proyek tercapai: model berhasil mengklasifikasikan jenis bunga dengan akurasi tinggi.
- Kelebihan: dataset sederhana dan bersih, performa model tinggi.
- Keterbatasan: dataset kecil, bisa dikembangkan dengan fitur tambahan.
- Rekomendasi: uji dengan data real-world, tambah algoritma ensemble.

## 9. Referensi
Zhang, Z. (2016). Introduction to machine learning: k-nearest neighbors. *Annals of Translational Medicine*, 4(11), 218. https://doi.org/10.21037/atm.2016.03.37
