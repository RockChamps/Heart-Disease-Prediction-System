# Heart-Disease-Prediction-System
A System which tells whether you have a heart disease based on your reports.
# ❤️ Heart Disease Prediction System

A Machine Learning–based system to predict the presence of heart disease using clinical patient data.  
The project includes **data preprocessing, model training, evaluation, and deployment using FastAPI**.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide.  
This project uses a **Decision Tree Classifier** to predict whether a patient has heart disease based on medical attributes such as age, cholesterol level, blood pressure, heart rate, etc.

---

## 🚀 Features

- Data preprocessing & cleaning
- Feature scaling using StandardScaler
- Decision Tree classification
- Model evaluation (Accuracy, Confusion Matrix, Classification Report)
- Cross-validation
- Model persistence using Joblib
- REST API deployment using FastAPI

---

## 🧠 Machine Learning Workflow

1. Load dataset (`heart.csv`)
2. Handle missing values
3. Split features and target variable
4. Apply feature scaling
5. Train Decision Tree model
6. Evaluate model performance
7. Save trained model & scaler
8. Deploy prediction API using FastAPI

---

## 📊 Dataset Information

The dataset contains the following features:

| Feature | Description |
|-------|------------|
| age | Age of the patient |
| sex | Gender (1 = male, 0 = female) |
| cp | Chest pain type |
| trestbps | Resting blood pressure |
| chol | Serum cholesterol |
| fbs | Fasting blood sugar |
| restecg | Resting ECG results |
| thalach | Maximum heart rate achieved |
| exang | Exercise-induced angina |
| oldpeak | ST depression |
| slope | Slope of peak exercise ST segment |
| ca | Number of major vessels |
| thal | Thalassemia |
| target | 1 = Heart Disease, 0 = No Disease |

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- FastAPI
- Joblib
- Google Colab

---

## 📈 Model Performance

- **Accuracy:** ~88.5%
- **Cross-validation Accuracy:** ~77.8%
- Evaluation Metrics:
  - Confusion Matrix
  - Precision
  - Recall
  - F1-score

---
<img width="3106" height="1516" alt="image" src="https://github.com/user-attachments/assets/c75f6fd7-e6d5-4213-8253-7eb502562552" />

## 🧪 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
