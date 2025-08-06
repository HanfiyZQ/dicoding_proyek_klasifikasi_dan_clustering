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
- Algoritma: Logistic Regression & Random Forest
- Evaluasi: Accuracy, F1-score, Confusion Matrix

📌 **Hasil**:
- 📈 Logistic Regression:  
  - Accuracy: **99.63%**  
  - F1 Score: **0.9963**

- 🌲 Random Forest:  
  - Accuracy: **99.92%**  
  - F1 Score: **0.9991**

### 3. 📌 Clustering
- Algoritma: KMeans
- Reduksi dimensi: PCA
- Evaluasi: Silhouette Score

📌 **Hasil**:
- Jumlah Cluster Optimal: **2**
- ⭐ Silhouette Score: **0.6125**

---
## 📈 Visualisasi

- Feature Importance (bar chart)
- PCA Cluster Plot
- Confusion Matrix Heatmap
- Elbow Method & Silhouette Score

---
## 🛠️ Tools & Teknologi

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- ML: RandomForestClassifier, KMeans, PCA
