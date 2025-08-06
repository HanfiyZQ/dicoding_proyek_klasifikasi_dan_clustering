# 🧠 Customer Segmentation using Classification and Clustering

Analisis dilakukan terhadap dataset perilaku pembelian pelanggan, dimulai dari klasifikasi status loyalitas, lalu dilanjutkan dengan segmentasi pelanggan menggunakan metode clustering.
> ✅ Proyek ini merupakan bagian dari **Machine Learning Engineer Path by Dicoding Indonesia**, khususnya dalam course **Belajar Machine Learning untuk Pemula**.  

---

## 📦 Dataset

Dataset diambil dari:  
**[Customer Purchases Behaviour Dataset - Kaggle](https://www.kaggle.com/datasets/sanyamgoyal401/customer-purchases-behaviour-dataset)**

- Jumlah data: 10.000 baris
- Fitur: 12 kolom
  - **Numerikal**: age, income, purchase_amount, satisfaction_score
  - **Kategorikal**: gender, education, region, loyalty_status, purchase_frequency, product_category, promotion_usage

---

## 🎯 Tujuan Proyek

1. Melakukan **klasifikasi status loyalitas** pelanggan (loyal vs not loyal)
2. Melakukan **clustering/segmentasi pelanggan** berdasarkan fitur perilaku belanja dan skor kepuasan

---

## 🔍 Tahapan Analisis

### 1. 📊 Preprocessing & Feature Engineering
- Label encoding untuk data kategorikal
- Skala numerikal menggunakan MinMaxScaler
- Pemisahan fitur dan target
- Pembagian data train/test (80:20)

### 2. ✅ Klasifikasi
- Model: Random Forest Classifier
- Evaluasi: Accuracy, F1-score, Confusion Matrix, Classification Report
- Interpretasi fitur menggunakan feature importance

### 3. 📌 Clustering
- Metode: KMeans Clustering
- Optimasi jumlah cluster dengan Elbow Method dan Silhouette Score
- Visualisasi hasil clustering menggunakan PCA dan scatter plot

---

## 📈 Hasil

- Model klasifikasi memberikan performa akurasi yang baik dalam memprediksi loyalitas pelanggan
- Clustering mengelompokkan pelanggan ke dalam beberapa segmen berdasarkan perilaku belanja dan tingkat kepuasan
- Diperoleh insight tentang segmen pelanggan loyal vs non-loyal dan bagaimana pola pembelian mereka berbeda

---

## 🛠️ Tools & Teknologi

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- ML: RandomForestClassifier, KMeans, PCA
