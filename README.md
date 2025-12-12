# ❤️ Heart Disease Prediction using Machine Learning

A Machine Learning project that predicts the 10-year risk of Coronary Heart Disease (CHD) using the Framingham Heart Study dataset. The repository trains and compares two supervised models — Logistic Regression and Random Forest — and reports standard evaluation metrics (Accuracy, Precision, Recall, F1-Score, ROC-AUC).

---

## 📌 Project Overview

Heart disease is a leading cause of death worldwide. Early prediction enables targeted preventive care and timely clinical intervention. This project builds models to identify individuals at risk of developing CHD within 10 years using demographic, lifestyle, clinical, and medical history features.

---

## 📊 Dataset

- Source: Framingham Heart Study
- Observations: ~4,240
- Features (examples): age, gender, currentSmoker, cigsPerDay, totChol, sysBP, diaBP, BMI, glucose, prevalentHyp, diabetes, prevalentStroke
- Target: TenYearCHD (1 = disease, 0 = no disease)

Preprocessing steps used:
- Handling missing values
- Encoding categorical variables
- Feature scaling (where applicable)
- Train/test split with stratification

---

## 🔧 Tech Stack

- Python 3.8+
- pandas, numpy — data manipulation
- matplotlib, seaborn — plotting & EDA
- scikit-learn — modeling & evaluation
- jupyter notebook — experiments & visualization

---

## 🧪 Reproduce / Run

1. Clone repository
   git clone https://github.com/TamgadgeSiddhant19/Heart-Disease-Prediction-using-Machine-Learning.git
2. Create virtual environment and install
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   pip install -r requirements.txt
3. Explore data and notebooks
   jupyter notebook
4. Run training script (example)
   python src/train.py --model random_forest --config configs/rf_config.yaml

Adjust paths and flags as needed — see scripts and notebooks in the repo for detailed usage.

---

## 🧮 Model Performance (reported)

Logistic Regression
- Accuracy: 84.67%
- Precision: 0.81
- Recall: 0.81
- F1-Score: 0.82
- ROC-AUC: 0.641

Random Forest Classifier
- Accuracy: 85.38%
- Precision: 0.83
- Recall: 0.82
- F1-Score: 0.82
- ROC-AUC: 0.70

---

## 🏆 Summary & Interpretation

- Random Forest achieves slightly higher accuracy and ROC-AUC than Logistic Regression, suggesting better ability to capture non-linearities and interactions.
- Logistic Regression remains valuable for interpretability and clinical explainability.
- Consider class imbalance mitigation, calibration, and external validation before any clinical use.

---


## 🙋 Contact

Created by TamgadgeSiddhant19 — contributions and feedback welcome.
