# ❤️ Heart Disease Risk Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict the likelihood of heart disease using Machine Learning techniques. By analyzing patient health indicators such as age, cholesterol level, blood pressure, and heart rate, the models can assist in identifying individuals at risk of cardiovascular disease.

The project includes Exploratory Data Analysis (EDA), feature analysis, model training, performance evaluation, cross-validation, and ROC-AUC analysis.

---

## 🎯 Objectives

* Explore and understand heart disease data.
* Identify important factors associated with heart disease.
* Build predictive Machine Learning models.
* Compare model performance using multiple evaluation metrics.
* Visualize results through charts and performance curves.

---

## 📊 Dataset

Dataset: Heart Disease Dataset

Features include:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate Achieved
* Exercise-Induced Angina
* ST Depression
* Number of Major Vessels
* Thalassemia

Target Variable:

* 0 → No Heart Disease
* 1 → Heart Disease

---

## 🔍 Exploratory Data Analysis

Key analyses performed:

* Dataset overview
* Missing value inspection
* Statistical summary
* Feature distribution visualization
* Correlation analysis
* Target variable distribution

---

## 🤖 Machine Learning Models

The following models were implemented and evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K-Nearest Neighbors (KNN)

---

## 📈 Model Evaluation

Evaluation techniques:

* Accuracy Score
* Cross Validation (5-Fold)
* ROC Curve
* AUC Score
* Model Comparison Visualization

---

## 🏆 Results

Random Forest achieved the best overall performance among the tested models and demonstrated strong classification capability based on ROC-AUC analysis.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 📂 Project Structure

heart-disease-prediction-ml/

├── data/

│ └── heart.csv

├── notebooks/

│ └── Heart_Disease_Analysis_Portfolio.ipynb

├── images/

│ ├── correlation_heatmap.png

│ ├── roc_curve.png

│ └── model_comparison.png

│ └── feature_importance.png

├── requirements.txt

└── README.md

---

## 🚀 How to Run

Clone repository:

git clone https://github.com/tntnammm/heart-disease-prediction-ml.git

Install dependencies:

pip install -r requirements.txt

Launch Jupyter Notebook:

jupyter notebook

Open:

Heart_Disease_Analysis.ipynb

---

## 📌 Future Improvements

* Hyperparameter Tuning
* Feature Engineering
* XGBoost Implementation
* Deployment using Streamlit
* Explainable AI (SHAP)

---

## 👨‍💻 Author

**Tran Nguyen Thanh Nam**

Data Science Student

GitHub:
https://github.com/tntnammm
