# 🏥 Health Insurance Cost Predictor

A user-friendly Streamlit web application that predicts a person's **health insurance premium** based on various demographic, lifestyle, and health-related factors.

---

## 🚀 Demo

> **Predicted Health Insurance Cost:** `5905`  
> Example input: 18-year-old male, freelancer, with obesity and high blood pressure.

---

## 📌 Features

- 🔢 Predicts insurance cost based on 13 input factors
- 📊 Uses trained machine learning models with `joblib`
- 🎨 Interactive UI built using **Streamlit**
- 🧠 Supports predictions for both *young* and *rest* age groups
- 🌙 Dark theme layout for better readability

---

## 🧠 Model Inputs

- Age
- Number of Dependents
- Income (in Lakhs)
- Genetical Risk (0–10 scale)
- Insurance Plan (Bronze, Silver, Gold, etc.)
- Employment Status
- Gender
- Marital Status
- BMI Category (Underweight, Normal, Overweight, Obesity)
- Smoking Status (Non-Smoker, Regular, Chain Smoker)
- Region (Northeast, Northwest, Southeast, Southwest)
- Medical History (e.g., Diabetes, High Blood Pressure)

---

## 🛠️ Tech Stack

| Tool        | Purpose                     |
|-------------|-----------------------------|
| `Python`    | Core programming language   |
| `Streamlit` | Web UI development          |
| `scikit-learn` | ML modeling and preprocessing |
| `joblib`    | Model serialization         |
| `pandas`    | Data handling and input prep |

---

## 📂 Folder Structure

ML-premium-prediction/
├── artifacts/
│ ├── model_rest.joblib
│ ├── model_young.joblib
│ ├── scaler_rest.joblib
│ └── scaler_young.joblib
├── main.py
├── prediction_helper.py
├── requirements.txt
└── README.md

