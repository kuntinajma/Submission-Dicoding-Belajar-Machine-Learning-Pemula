# README - Submission Belajar Machine Learning Pemula

## 📌 Deskripsi Proyek
Submission ini mencakup dua tahap utama dalam Machine Learning, yaitu **Clustering** dan **Klasifikasi**, dengan menggunakan dataset **[Beverage Sales](https://www.kaggle.com/datasets/sebastianwillmann/beverage-sales)**. Karena ukuran dataset yang besar, hanya **100.000 data** yang diambil secara acak untuk proses clustering.

## 📂 Struktur File
```
├── Submission Belajar Machine Learning Pemula.zip
    ├── [Clustering] Submission Akhir BMLP_Kunti_Najma.ipynb
    ├── [Klasifikasi] Submission Akhir BMLP_Kunti_Najma.ipynb
    ├── Dataset_clustering.csv
    ├── Dataset_inisiasi.csv
```

## 🔍 Tahapan Proyek

### 1️⃣ Clustering (Unsupervised Learning)
#### ✅ Kriteria yang Dipenuhi:
- **Menggunakan minimal 5 fitur** (kombinasi numerikal dan kategorikal).
- **Menggunakan dataset tanpa label** sebanyak **≥ 2500 data**.
- **Menggunakan K-Means** sebagai metode clustering.
- **Mengevaluasi jumlah cluster** dengan **Silhouette Score**.
- **Melakukan Feature Selection** dan membandingkan **Silhouette Score sebelum dan sesudah seleksi fitur**.
- **Melakukan interpretasi cluster** dengan cara:
  - Inversi data fitur dan target ke versi asli.
  - Melakukan agregasi data berdasarkan cluster.
  - Menjelaskan pola dari tiap cluster.
- **Hasil Evaluasi**: Silhouette Score mencapai **0.86**.

### 2️⃣ Klasifikasi (Supervised Learning)
#### ✅ Kriteria yang Dipenuhi:
- **Menggunakan dataset dari hasil clustering** sebagai label target.
- **Menggunakan dua algoritma klasifikasi**:
  - **Random Forest**
  - **Naive Bayes**
- **Menampilkan akurasi dan F1-Score pada testing set**:
  - **Random Forest**: Akurasi **0.999074**, F1-Score **0.999074**
  - **Naive Bayes**: Akurasi **0.988773**, F1-Score **0.988762**
- **Membandingkan performa model berdasarkan hasil evaluasi**.

## 📊 Hasil Analisis
- **Random Forest memiliki performa lebih tinggi** dibanding Naive Bayes dengan **F1-Score 0.999074**.
- **Naive Bayes tetap memiliki hasil yang baik** dengan **F1-Score 0.988762**, namun lebih rentan terhadap fitur tertentu.
- Model **tidak mengalami overfitting**, karena hasil akurasi tinggi baik di training maupun testing set.
- Clustering berhasil membentuk kelompok dengan karakteristik yang berbeda, yang berguna untuk klasifikasi lanjutan.