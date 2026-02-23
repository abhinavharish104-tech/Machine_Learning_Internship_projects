# Machine Learning Internship Projects

## Overview

This repository contains all assignments, mini-projects, and the final capstone project completed during the Machine Learning Internship program.
The work follows a complete learning progression — starting from Python data analysis and visualization, moving to supervised learning, unsupervised learning, dimensionality reduction, and finally an end-to-end real-world ML application.

The goal of the repository is to demonstrate practical understanding of the **full machine learning workflow**:
Data → Cleaning → EDA → Modeling → Evaluation → Interpretation

---

## Skills Demonstrated

* Data preprocessing and cleaning (Pandas, NumPy)
* Exploratory Data Analysis (EDA)
* Data visualization (Matplotlib, Seaborn)
* Regression models (Simple & Multiple Linear Regression)
* Classification models (Logistic Regression, Decision Tree, Random Forest)
* Clustering (K-Means, Hierarchical Clustering)
* Dimensionality Reduction (PCA)
* Model evaluation metrics
* Hyperparameter tuning (GridSearchCV)
* Model comparison and selection
* Real-world problem solving

---

## Repository Structure

### Week 1 – Python & Data Analysis

Basic data manipulation and analysis using Pandas and NumPy.

---

### Week 2 – Supervised Machine Learning

#### Day 3 – First ML Model

* Dataset based classification/regression
* Train-test split
* Accuracy / MSE evaluation

#### Day 4 – House Price Prediction

* Multiple Linear Regression
* Residual analysis
* Actual vs Predicted plots
* Model saving using joblib

#### Student Performance Mini Project

* Predict student scores using study & sleep hours
* Feature importance interpretation
* Metrics: MAE, MSE, RMSE, R²

---

### Week 3 – Unsupervised Learning & Advanced Topics

#### Data Visualization Mini Project

* Line chart
* Bar chart
* Scatter plot
* Pie chart

#### Clustering

* K-Means clustering
* Elbow Method
* Silhouette Score
* Customer segmentation interpretation

#### Hierarchical Clustering

* Multiple linkage methods
* Dendrogram analysis
* Cluster comparison

#### PCA (Dimensionality Reduction)

* Explained variance ratio
* 2D projection
* Reconstruction error
* Impact of scaling and outliers

---

## Final Project – Loan Default Prediction System

### Objective

Predict whether a loan applicant will default using historical applicant data.

### Workflow

1. Data preprocessing
2. Encoding categorical features
3. Exploratory Data Analysis
4. Model training
5. Hyperparameter tuning
6. Model evaluation and comparison

### Models Compared

* Logistic Regression
* Decision Tree
* Random Forest (Selected Model)

### Final Model Performance (Random Forest)

* Accuracy: 0.894
* Precision: 0.90
* Recall: 0.953
* F1 Score: 0.926
* ROC-AUC: 0.878

### Best Parameters

max_depth = 5
min_samples_split = 5
n_estimators = 200

### Conclusion

Random Forest performed best due to its ability to capture nonlinear relationships and reduce overfitting through ensemble learning.
Credit history and applicant income were major predictive factors in loan approval.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Jupyter Notebook

---

## How to Run

1. Clone the repository
2. Install dependencies

   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open notebooks in Jupyter/Colab
4. Run cells sequentially

---

## Learning Outcome

This repository demonstrates the ability to:

* Build ML models from scratch
* Choose appropriate algorithms
* Evaluate and compare performance
* Interpret results in practical terms
* Apply ML concepts to real-world datasets

---

## Author

Abhinav Harish

