# ❤️ Heart Disease Predictor

A machine learning project that predicts the likelihood of heart disease based on medical data using **Logistic Regression** and the **scikit-learn** library.

## 📌 Project Overview

This project uses a dataset of patient health records to train a machine learning model that predicts whether a person is likely to have heart disease. It involves data preprocessing, exploratory data analysis, model training, evaluation, and deployment.

- **Algorithm Used:** Logistic Regression
- **Tech Stack:** Python, Pandas, scikit-learn
- **Goal:** Binary classification – Predict presence or absence of heart disease

---

## 📁 Dataset

The dataset contains 14 features such as:
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Max Heart Rate Achieved
- Exercise Induced Angina
- ST depression
- Target

✅ You can find the dataset here: [Heart Disease Dataset](https://www.kaggle.com/datasets/arezaei81/heartcsv)

---

## 🔧 Features

- Data Cleaning & Preprocessing
- Model Building using `LogisticRegression`
- Model Evaluation using accuracy, precision, recall, F1-score, ROC-AUC
- Train/Test Split using `train_test_split`

---

## 🧰 Installation

```bash
# Clone the repository
git clone https://github.com/k201751/Heart-Disease-Predictor.git
cd Heart-Disease-Predictor

# (Optional) Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
