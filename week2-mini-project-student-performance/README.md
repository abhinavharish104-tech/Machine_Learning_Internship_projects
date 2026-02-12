# Week 2 Mini Project  
## Predicting Student Performance using Multiple Linear Regression

---

## 📌 Project Overview

This mini project focuses on predicting students' final scores using multiple linear regression. The goal was to analyze how different factors such as study hours, sleep hours, and previous scores influence academic performance.

---

## 📊 Dataset Description

The dataset includes the following features:

- **Study_Hours** – Number of hours spent studying
- **Sleep_Hours** – Number of hours slept per day
- **Previous_Score** – Student’s prior academic score
- **Final_Score** – Target variable (Predicted outcome)

A synthetic dataset of 100 observations was generated to simulate realistic student performance data.

---

## ⚙️ Methodology

### 1️⃣ Data Preparation
- Generated synthetic dataset
- Performed Exploratory Data Analysis (EDA)
- Visualized relationships using pairplot

### 2️⃣ Train-Test Split
- Split data into 80% training and 20% testing

### 3️⃣ Model Training
- Applied **Multiple Linear Regression**
- Trained model using Study_Hours, Sleep_Hours, and Previous_Score

### 4️⃣ Model Evaluation

The model was evaluated using the following regression metrics:

- **MAE (Mean Absolute Error):** 5.34  
- **MSE (Mean Squared Error):** 52.54  
- **RMSE (Root Mean Squared Error):** 7.25  
- **R² Score:** 0.863  

---

## 📈 Visualizations

The following plots were generated:

### 🔹 Regression Relationship (Study Hours vs Final Score)
- Shows positive correlation between study hours and performance

### 🔹 Actual vs Predicted Plot
- Demonstrates strong alignment between predicted and actual scores

### 🔹 Residual Plot
- Residuals are randomly distributed
- Indicates good model fit with no major bias patterns

---

## 🧠 Feature Importance Interpretation

Based on regression coefficients:

- **Study Hours** had the strongest positive impact on Final Score.
- **Previous Score** also significantly influenced performance.
- **Sleep Hours** showed a smaller but positive contribution.

This indicates that academic effort (study time) plays the most critical role in performance prediction.

---

## 📊 Results Interpretation

- The model explains approximately **86.3% of the variance** in student performance.
- Prediction errors are relatively low (RMSE ≈ 7.25).
- The model demonstrates strong predictive capability for a linear regression approach.

---

## ✅ Conclusion

This project successfully demonstrates:

- Implementation of both simple and multiple regression
- Proper evaluation using regression metrics
- Visualization of prediction accuracy and residual analysis
- Interpretation of feature importance

The model provides meaningful insights into how study habits and prior performance influence academic outcomes.

