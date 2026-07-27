# ❤️ Heart Disease Prediction using Logistic Regression

A machine learning project that predicts the presence of heart disease using **Logistic Regression**. This project demonstrates a complete binary classification workflow, including data preprocessing, feature engineering, model training, regularization techniques, and evaluation.

## 📌 Project Overview

The objective of this project is to classify whether a patient has heart disease based on various medical attributes.

The project includes:
- Data preprocessing
- Feature engineering
- One-Hot Encoding
- Feature Scaling
- Logistic Regression
- L1 (Lasso) Regularization
- L2 (Ridge) Regularization
- Model evaluation using multiple classification metrics

---

## 📂 Dataset

The dataset contains medical information about patients, including:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- ST Depression (Oldpeak)
- Slope
- Number of Major Vessels
- Thalassemia
- Target (Heart Disease)

**Target**
- 0 → No Heart Disease
- 1 → Heart Disease

---

## ⚙️ Feature Engineering

The following feature engineering techniques were applied:

- Created Age Groups using `pd.cut()`
- One-Hot Encoding for categorical features
- Interaction Features:
  - Blood Pressure × Cholesterol
  - Age × Oldpeak
- Standard Feature Scaling using `StandardScaler`

---

## 🤖 Models Used

- Logistic Regression
- Logistic Regression with L1 Regularization (Lasso)
- Logistic Regression with L2 Regularization (Ridge)

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

```
heart_logistic_reg/
│
├── heart_logReg.ipynb
├── heart.csv
├── requirements.txt
└── README.md
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/Ashwakkattubadi/heart_logistic_reg.git
```

Move into the project directory:

```bash
cd heart_logistic_reg
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## 🎯 Learning Outcomes

This project helped in understanding:

- Binary Classification
- Logistic Regression
- Regularization (L1 & L2)
- Feature Engineering
- Data Preprocessing
- Model Evaluation
- Classification Metrics

---

## 📚 Future Improvements

- Hyperparameter Tuning using GridSearchCV
- Cross Validation
- ROC-AUC Curve
- Feature Selection
- Model Deployment using Streamlit or Flask

---

## 👨‍💻 Author

**Ashwak Kattubadi**

GitHub: https://github.com/Ashwakkattubadi