# Skin Cancer Classification using HAM10000 Dataset
# Project Overview
Project ini bertujuan untuk membangun model machine learning / deep learning dalam mengklasifikasikan citra lesi kulit ke dalam berbagai jenis kanker kulit menggunakan dataset HAM10000.

Dataset ini berisi lebih dari 10.000 gambar dermatoskopi yang merepresentasikan berbagai kondisi kulit, termasuk kanker dan non-kanker.

# Sumber Data
Dataset HAM10000 berasal dari penelitian medis yang dipublikasikan oleh tim dermatologi dari MEDICAL UNIVERSITY OF VIENNA dan MEDICAL UNIVERSITY OF GRAZ
Dataset ini dikembangkan untuk mendukung riset diagnosis kanker kulit berbasis machine learning.

Dapat diakses melalui:
- Harvard Dataverse (https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T)
- kaggle (https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)

# Objectives
- Mengembangkan model klasifikasi citra kanker kulit
- Mendukung deteksi dini kanker kulit
- Menganalisis pola visual lesi kulit
- Mengevaluasi performa model
- Mengembangkan model yang interpretatif

# Tujuan Analisis
Tujuan analisis adalah membangun model klasifikasi citra kanker kulit yang akurat, membantu deteksi dini, memahami pola visual penyakit, Analisis tidak hanya berfokus pada klasifikasi, tetapi juga pada interpretability model dan robustness terhadap variasi data medis.

# Dataset
Dataset yang digunakan adalah Skin Cancer MNIST: HAM10000, dengan karakteristik:
- 10.015 gambar dermatoskopi
- 7 kelas penyakit kulit
- Metadata tambahan

# Big Data Characteristics (5V + 3V)
- Volume
Dataset terdiri dari lebih dari 10.000 citra medis beresolusi tinggi.
Meskipun tidak berskala petabyte, ukuran ini cukup besar untuk analisis citra berbasis deep learning.
- Velocity
Dataset bersifat statis (tidak real-time).
Namun dalam implementasi nyata, data citra medis dapat berkembang menjadi sistem streaming (real-time diagnosis).
- Variety
Memiliki variasi tinggi:
-  7 kelas penyakit kulit
-  Data berupa citra + metadata
- Veracity
Data berasal dari diagnosis medis ahli, namun tetap memiliki tantangan seperti:
-  Noise pada label
-  Class imbalance
- Value
Memiliki nilai tinggi karena dapat digunakan untuk:
-  Deteksi dini kanker kulit
-  Pengembangan sistem AI di bidang kesehatan
- Variability
Variasi tinggi pada:
-  Bentuk dan warna lesi
-  Kondisi pencahayaan
-  Perbedaan alat pengambilan gambar
- Visualization
Dataset berbasis citra memungkinkan:
-  Visualisasi langsung
-  Heatmap (Grad-CAM)
-  Analisis distribusi kelas
- Validity
Data dikumpulkan dari sumber medis terpercaya, namun tetap memerlukan:
-  Validasi model
-  Evaluasi performa yang ketat
