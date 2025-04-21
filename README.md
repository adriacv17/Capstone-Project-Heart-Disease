# 🫀 Heart Disease Prediction Using Machine Learning

[![View on GitHub](https://img.shields.io/badge/GitHub-View%20Repository-blue?logo=github)](https://github.com/adriacv17/Capstone-Project-Heart-Disease)

## Overview
This project focuses on the early detection of heart disease using predictive analytics. Leveraging open-source healthcare data and machine learning models, the goal is to create a reliable, interpretable system that can assist in identifying individuals at risk for heart disease — a leading cause of death worldwide.

## 📊 Objective
To build and evaluate machine learning models capable of predicting the presence of heart disease using patient health attributes. The project emphasizes data preprocessing, exploratory data analysis (EDA), and model evaluation to ensure trustworthy outcomes.

## 🔍 Dataset
- **Source:** [Kaggle - Heart Disease Prediction](https://www.kaggle.com/datasets/rashadrmammadov/heart-disease-prediction)
- **Origin:** UCI Machine Learning Repository
- **Format:** CSV
- **Filtered:** Only data from the Cleveland location was used due to completeness

Key attributes include:
- Age, Sex
- Chest pain type (`cp`)
- Resting blood pressure (`trestbps`)
- Serum cholesterol (`chol`)
- Fasting blood sugar (`fbs`)
- Resting electrocardiographic results (`restecg`)
- Maximum heart rate achieved (`thalach`)
- Exercise-induced angina (`exang`)
- ST depression (`oldpeak`)
- Number of major vessels (`ca`)
- Thalassemia (`thal`)
- Target (`num` - heart disease presence)

## 🧹 Data Preprocessing
- Missing values imputed using mean strategy
- Categorical features encoded numerically
- Outliers removed using IQR method
- Data normalized and transformed
- Dataset split: **80% train / 20% test**

## 📈 Exploratory Data Analysis (EDA)
- Descriptive statistics for understanding spread and shape of data
- Histograms, box plots for distribution and outliers
- Correlation matrix for feature relationships

## 🧠 Machine Learning Models
Two models were evaluated:
- **Logistic Regression**
- **Random Forest Classifier**

### Logistic Regression (Preferred Model)
- **Accuracy:** 85%
- **F1-score:** 0.88 (disease class)
- **Pros:** Simpler, interpretable, lower computational cost

### Random Forest Classifier
- **Accuracy:** 87%
- **F1-score:** 0.84 (disease class)
- **Pros:** Slightly higher accuracy, handles non-linearity well

## 📊 Evaluation Metrics
- Confusion matrix
- Precision, Recall, F1-score
- Classification report

## ⚠️ Limitations
- Class imbalance between “disease” and “no disease” cases
- Lack of external lifestyle or environmental factors
- Gender imbalance in dataset
- Removal of extreme but potentially valid outlier cases

## 🔧 Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn, Missingno

## 👨‍💻 Author
**Adrian C. Vega**  
Northwest Missouri State University  
📧 S567246@nwmissouri.edu  
📧 AdrianCVega@yahoo.com

## 🔗 Repository
📂 [GitHub – Capstone-Project-Heart-Disease](https://github.com/adriacv17/Capstone-Project-Heart-Disease)
