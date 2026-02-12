# Week 2 – Day 4 Assignment  
## House Price Prediction using Multiple Linear Regression

---

## 📌 Project Overview

This project focuses on building a **Multiple Linear Regression model** to predict house prices using a real-world housing dataset. The objective was to implement a complete machine learning workflow including data splitting, model training, evaluation, visualization, and model saving.

---

## 📊 Dataset Used

**California Housing Dataset** (from sklearn library)

The dataset contains various numerical features related to housing areas such as:

- Median Income  
- House Age  
- Average Rooms  
- Average Bedrooms  
- Population  
- Latitude  
- Longitude  

Target Variable:
- Median House Value (Price)

---

## ⚙️ Methodology

### 1️⃣ Data Preparation
- Loaded dataset using sklearn
- Converted features into pandas DataFrame
- Performed train-test split (80% training, 20% testing)

### 2️⃣ Model Building
- Implemented **Multiple Linear Regression**
- Trained model using training dataset

### 3️⃣ Model Evaluation

The model performance was evaluated using:

- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**
- **R² Score**

These metrics help assess prediction accuracy and error magnitude.

---

## 📈 Visualizations

The following plots were generated:

### 🔹 Regression Relationship Plot
- Shows predicted vs actual values for a selected feature

### 🔹 Actual vs Predicted Plot
- Evaluates how closely predictions align with true values

### 🔹 Residual Plot
- Assesses model error distribution
- Helps check assumptions of linear regression

All plots were saved using:

