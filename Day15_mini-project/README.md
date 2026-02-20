# Customer Segmentation using Machine Learning

## Overview
This project performs end-to-end customer segmentation using unsupervised machine learning to identify distinct customer groups based on purchasing behavior and demographics.

The objective is to help businesses understand customer behavior and take data-driven marketing decisions.

Pipeline followed:
Data Cleaning → EDA → Feature Engineering → Clustering → Interpretation → Business Strategy

---

## Business Objective
Most businesses market to all customers equally, which wastes budget.

This project identifies:
- High value customers
- Potential premium customers
- Discount sensitive customers
- Low engagement customers

---

## Dataset
Mall Customers Dataset

| Feature | Description |
|------|------|
| Age | Customer age |
| Gender | Male/Female |
| Annual Income (k$) | Income level |
| Spending Score (1-100) | Purchase behavior score |

---

## Project Workflow

### Data Preprocessing
- Removed ID column
- Handled missing values
- Encoded categorical variable (Gender)
- Feature scaling using StandardScaler
- Outlier removal using IQR method

### Exploratory Data Analysis
- Histograms
- Boxplots
- Correlation heatmap
- Pairplots

### Feature Engineering
Created behavioral score similar to RFM concept.

### Model Selection
K-Means clustering used.

Optimal number of clusters chosen using:
- Elbow Method
- Silhouette Score

### Visualization
PCA used to visualize clusters in 2D space.

### Cluster Profiling
Customers grouped and interpreted into business personas.

---

## Results (Example Interpretation)

| Cluster | Meaning | Action |
|------|------|------|
| High Income High Spend | Premium customers | Loyalty rewards |
| High Income Low Spend | Upsell target | Personalized marketing |
| Low Income High Spend | Price sensitive | Discounts |
| Average Customers | Regular buyers | Standard campaigns |
| Low Engagement | Inactive users | Retention campaigns |

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Output
The project generates:
- Cluster visualization plots
- Cluster statistics
- Segmented dataset

`segmented_customers.csv`

---


---

## Business Impact
Helps businesses:
- Personalize marketing
- Improve retention
- Identify valuable customers
- Increase revenue

---

## Limitations
- Small static dataset
- Offline clustering
- Limited features

---

## Future Work
- Add transaction history (true RFM)
- Apply Gaussian Mixture Model
- Predict customer behavior
- Deploy real-time segmentation

---

## Author
Abhinav Harish_Machine Learning Internship Project

