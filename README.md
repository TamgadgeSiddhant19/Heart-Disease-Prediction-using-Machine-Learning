❤️ Heart Disease Prediction using Machine Learning

A Machine Learning project that predicts the 10-year risk of Coronary Heart Disease (CHD) using the Framingham Heart Study dataset.
This project compares two supervised ML models — Logistic Regression and Random Forest — and evaluates their performance on various metrics like Accuracy, Precision, Recall, F1-Score, and ROC-AUC.# Heart-Disease-Prediction-using-Machine-Learning

📌 Project Overview

Heart disease is one of the leading global causes of death. Early prediction can support preventative healthcare and timely intervention.
This project aims to build a predictive model that identifies individuals at risk of developing heart disease within 10 years using demographic, lifestyle, and clinical features.

📊 Dataset

This project uses the Framingham Heart Study dataset containing 4,240 observations and 16 features, including:
Demographics: age, gender
Lifestyle: smoking status, cigarettes per day
Clinical: cholesterol, systolic/diastolic BP, BMI, glucose
Medical history: hypertension, diabetes, stroke
Target: TenYearCHD (1 = disease, 0 = no disease)

🔧 Tech Stack

Python
Pandas, NumPy – data preprocessing
Matplotlib, Seaborn – EDA & data visualization
Scikit-Learn – ML model building & evaluation

🧮 Model Performance Results

⭐ Logistic Regression
Metric	Score
Accuracy	84.67%
Precision	0.81
Recall	0.81
F1-Score	0.82
ROC-AUC	0.641

⭐ Random Forest Classifier
Metric	Score
Accuracy	85.38%
Precision	0.83
Recall	0.82
F1-Score	0.82
ROC-AUC	0.70

🏆 Comparison Summary

Random Forest slightly outperforms Logistic Regression in accuracy and ROC-AUC, indicating better generalization.
Logistic Regression provides better interpretability, making it useful for clinical insights.
Random Forest handles non-linear relationships and feature interactions more effectively.
