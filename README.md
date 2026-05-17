# Student Exam Score Prediction System  
**Introduction to Data Science — Fall 2025**

This project predicts a student’s **final exam score** using socio-academic factors and a **Multiple Linear Regression** model. A simple **Streamlit web application** is also included to allow real-time score prediction.

---

# Web App Link:
*(https://edu-analytics.streamlit.app/
)*
---
## Project Overview

- **Domain:** Education Analytics  
- **Objective:** Predict student exam performance using machine learning  
- **Model Used:** Multiple Linear Regression  
- **Frontend:** Streamlit Web App  
- **Programming Language:** Python  
- **Tools & Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Joblib, Streamlit  

---



---

## Project Features

- Data loading & preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature encoding  
- Machine learning model training  
- Model evaluation using MAE & R²  
- Model saving using Joblib  
- Real-time predictions using Streamlit  

---

## Input Features Used

| Feature Name | Description |
|--------------|-------------|
| `Hours_Studied` | Weekly study hours |
| `Attendance` | Attendance percentage |
| `Previous_Scores` | Past academic performance |
| `Motivation_Level` | Low / Medium / High |
| `Parental_Involvement` | Low / Medium / High |

**Target Variable:** `Exam_Score`

---

## Machine Learning Model

- **Algorithm:** Multiple Linear Regression  
- **Why this model?**
  - Output is continuous (numeric)
  - Easy to interpret
  - Fast and suitable for IDS-level projects

---

## Model Performance

| Metric | Value |
|--------|--------|
| **MAE** | **1.19** |
| **R² Score** | **0.67** |

The model predicts exam scores with an average error of **only ~1.2 marks**, and explains **67% of the variance** in student performance.

---

## Streamlit Web App Features

- Interactive sliders for input values  
- Dropdowns for categorical features  
- One-click **"Predict Exam Score"** button  
- Displays predicted exam result instantly  

---


