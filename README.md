# Student Dropout Prediction

## Overview
This project predicts the likelihood of a student dropping out of university 
using academic performance and financial data. It also explores how student 
habits impact exam scores.

## Datasets
- **Student Habits & Performance** — 1000 students, 16 features including 
study hours, sleep, social media usage and exam scores
- **Student Dropout** — 4424 students, 35 features including academic 
performance, financial status and demographic information

## Key Findings
- Study hours is the strongest predictor of exam performance (0.83 correlation)
- Mental health rating is the second most important habit factor
- Tuition fees and academic performance are the strongest dropout indicators
- Logistic Regression outperformed complex models with 92% accuracy

## Tools Used
- Python, Pandas, Matplotlib, Seaborn
- Scikit-learn, XGBoost
- SHAP for model explainability

## Models Built
- Linear Regression for exam score prediction (R2: 0.90)
- Logistic Regression for dropout prediction (Accuracy: 92%)
