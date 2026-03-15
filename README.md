# 🏠 House Price Prediction using Machine Learning
**BNSP Data Science Certification Project**

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![XGBoost](https://img.shields.io/badge/XGBoost-Regression-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📊 Project Preview
![California House Price Prediction](https://raw.githubusercontent.com/mhdalfarisy/mhdalfarisy.github.io/main/src/assets/images/california_predict_house.png)

---

## 📌 Project Description
This project implements **Machine Learning** to predict housing prices using the **California Housing Dataset**. The model was developed to provide a **data-driven approach** for accurately determining property values, minimizing human error in real estate appraisal.

---

## 📊 Dataset Overview
The dataset contains geographic and demographic information from various housing districts in California.

### Features Used:
* 🌍 **Location:** `longitude`, `latitude`
* 🏠 **Property Specs:** `housing_median_age`, `total_rooms`, `total_bedrooms`
* 👨‍👩‍👧 **Demographics:** `population`, `households`, `median_income`
* 🌊 **Proximity:** `ocean_proximity`

### 🎯 Prediction Target
The target variable is **`median_house_value`**, representing the median house price for a specific California district.

---

## ⚙️ Data Science Workflow
The project follows a structured methodology:
1.  **Data Understanding**
2.  **Data Cleaning**
3.  **Exploratory Data Analysis (EDA)**
4.  **Feature Engineering**
5.  **Model Training**
6.  **Model Evaluation**
7.  **Model Selection**

---

## 🤖 Machine Learning Algorithms
The following regression models were tested and compared:
* 📈 Linear Regression
* 🔍 K-Nearest Neighbors (KNN) Regressor
* 🌳 Decision Tree Regressor
* 🌲 Random Forest Regressor
* 🚀 **XGBoost Regressor**

---

## 📉 Model Evaluation
Evaluation was conducted using **MAE** (Mean Absolute Error) and **MAPE** (Mean Absolute Percentage Error):

| Model | MAE | MAPE |
| :--- | :--- | :--- |
| Linear Regression | 42,984 | 0.267 |
| KNN | 36,684 | 0.211 |
| Decision Tree | 42,409 | 0.251 |
| Random Forest | 30,915 | 0.184 |
| **XGBoost** | **29,607** | **0.177** |

🏆 **XGBoost delivered the best overall performance.**

---

## 🏆 Final Model Results
After hyperparameter tuning, the final **XGBoost Regressor** achieved:
* **MAE:** ≈ $28,293
* **MAPE:** ≈ 16%

*Insight: On average, the model's predictions deviate by approximately $28k from the actual market price.*

---

## 🔎 Key Insights
Based on the analysis, the most influential features affecting house prices are:
1.  💰 **Median Income:** The strongest predictor of property value.
2.  🌊 **Ocean Proximity:** Locations near the coast significantly command higher premiums.

---

## 💼 Business Benefits
Implementing this predictive model provides several advantages:
* **Accuracy:** More precise property valuation.
* **Risk Mitigation:** Avoiding overpricing or underpricing in the market.
* **Efficiency:** Helping real estate agents set data-backed listing prices.
* **Strategic Decisions:** Providing data-driven recommendations for investors.

---

## 🛠 Tech Stack
| Tools | Description |
| :--- | :--- |
| **Python** | Primary Programming Language |
| **Pandas / NumPy** | Data Manipulation & Computing |
| **Scikit-Learn** | Machine Learning Framework |
| **XGBoost** | Gradient Boosting Library |
| **Matplotlib / Seaborn** | Data Visualization |

---

## 👨‍💻 Author
**Muhammad Alfarisy**
*Certified Data Scientist - BNSP Certification Exam*

📌 [GitHub Profile](https://github.com/mhdalfarisy)
