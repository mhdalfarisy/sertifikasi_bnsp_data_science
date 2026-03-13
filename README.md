# 🏠 Prediksi Harga Rumah dengan Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![XGBoost](https://img.shields.io/badge/XGBoost-Regression-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Deskripsi Proyek

Proyek ini merupakan implementasi **Machine Learning** untuk memprediksi harga rumah menggunakan **California Housing Dataset**.

Model dikembangkan untuk membantu menentukan harga rumah secara **lebih akurat dan berbasis data**.

---

# 📊 Dataset

Dataset yang digunakan adalah **California Housing Dataset** yang berisi informasi geografis dan demografi wilayah perumahan.

### Fitur yang digunakan

- 🌍 longitude
- 🌍 latitude
- 🏠 housing_median_age
- 🏢 total_rooms
- 🛏 total_bedrooms
- 👨‍👩‍👧 population
- 🏘 households
- 💰 median_income
- 🌊 ocean_proximity

### 🎯 Target Prediksi



Target tersebut merepresentasikan **harga median rumah** pada suatu wilayah di California.

---

# ⚙️ Tahapan Proyek Data Science

Tahapan yang dilakukan dalam proyek ini:

1️⃣ Data Understanding  
2️⃣ Data Cleaning  
3️⃣ Exploratory Data Analysis (EDA)  
4️⃣ Feature Engineering  
5️⃣ Model Training  
6️⃣ Model Evaluation  
7️⃣ Model Selection  

---

# 🤖 Algoritma Machine Learning

Model yang diuji dalam proyek ini:

- 📈 Linear Regression
- 🔍 K-Nearest Neighbors Regressor
- 🌳 Decision Tree Regressor
- 🌲 Random Forest Regressor
- 🚀 XGBoost Regressor

---

# 📉 Evaluasi Model

Model dievaluasi menggunakan:

- **MAE (Mean Absolute Error)**
- **MAPE (Mean Absolute Percentage Error)**

| Model | MAE | MAPE |
|------|------|------|
| Linear Regression | 42984 | 0.267 |
| KNN | 36684 | 0.211 |
| Decision Tree | 42409 | 0.251 |
| Random Forest | 30915 | 0.184 |
| XGBoost | **29607** | **0.177** |

🏆 **XGBoost memberikan performa terbaik.**

---

# 🏆 Model Terbaik

Model terbaik setelah tuning adalah:

**XGBoost Regressor**

Hasil evaluasi:

- **MAE ≈ 28,293 USD**
- **MAPE ≈ 16%**

Artinya rata-rata selisih antara prediksi harga rumah dan harga sebenarnya sekitar **28 ribu USD**.

---

# 🔎 Insight Penting

Fitur paling berpengaruh terhadap harga rumah:

- 💰 **median_income**
- 🌊 **ocean_proximity**

Hal ini menunjukkan bahwa **kondisi ekonomi wilayah dan kedekatan dengan pantai sangat mempengaruhi harga properti**.

---

# 💼 Manfaat Bisnis

Model ini dapat membantu:

- 📊 Menentukan harga rumah lebih akurat
- 📉 Menghindari overpricing atau underpricing
- 🏠 Membantu agen properti menentukan harga jual
- 📈 Memberikan rekomendasi harga berbasis data

---

# 🛠 Teknologi yang Digunakan

| Tools | Keterangan |
|------|------|
| 🐍 Python | Bahasa pemrograman utama |
| 📊 Pandas | Data manipulation |
| 🔢 NumPy | Numerical computing |
| 🤖 Scikit-Learn | Machine learning library |
| 🚀 XGBoost | Boosting algorithm |
| 📈 Matplotlib | Visualisasi data |
| 📊 Seaborn | Statistical visualization |

---

# 👨‍💻 Author

**Muhammad Alfarisy**  
Ujian Sertifikasi **BNSP Data Science**

📌 GitHub  
https://github.com/mhdalfarisy