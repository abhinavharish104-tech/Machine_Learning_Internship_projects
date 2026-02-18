# Week 3 – Day 14
## Principal Component Analysis (PCA) on Wine Dataset

### Objective
To perform dimensionality reduction using PCA and analyze the impact of scaling and outliers on feature variance and reconstruction ability.

---

## Dataset
Wine Dataset from Scikit-learn

Contains 13 chemical features of wines belonging to different classes.

---

## Steps Performed

1. Loaded dataset
2. Standardized features
3. Applied PCA
4. Plotted explained variance ratio
5. Visualized first two principal components
6. Reconstructed original data and computed reconstruction error
7. Compared PCA behavior:
   - With scaling
   - Without scaling
   - With outliers

---

## Key Observations

- First few components captured most variance
- Scaling significantly improved PCA performance
- Outliers distorted component directions
- Reconstruction error increased when fewer components used

---

## Conclusion
PCA effectively reduced dimensionality while preserving information. However, results depend strongly on feature scaling and presence of outliers.

---

## Files Included
- pca_wine.ipynb
- explained_variance.png
- pca_2d_projection.png
- no_scaling_variance.png
- outlier_variance.png
