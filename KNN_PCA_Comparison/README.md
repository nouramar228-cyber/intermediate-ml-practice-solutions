# KNN PCA Comparison
# KNN & PCA Practice Projects

This folder contains machine learning practice projects focused on:

- Principal Component Analysis (PCA)
- KMeans Clustering
- K-Nearest Neighbors (KNN)
- Dimensionality Reduction
- Model Performance Comparison
- Data Visualization

---

# Projects Included

## 1. PCA to Visualize Clusters

This project uses PCA with KMeans clustering to visualize customer segmentation data in both 2D and 3D.

### Objectives

- Load and clean the credit card customer dataset
- Remove unnecessary columns
- Handle missing values
- Scale the data
- Apply KMeans clustering
- Determine the optimal number of clusters using:
  - Elbow Method
  - Silhouette Score
- Reduce dimensions using PCA
- Visualize clusters using:
  - 2D scatter plots
  - 3D Plotly scatter plots

### Technologies Used

- Python
- Pandas
- Scikit-learn
- PCA
- KMeans
- Matplotlib
- Plotly

---

## 2. KNN PCA Speed and Performance Comparison

This project compares the speed and performance of a default `KNeighborsClassifier` on:

- Original dataset (without PCA)
- PCA-transformed dataset

### Objectives

- Load and preprocess the NHANES dataset
- Train a KNN model without PCA
- Apply PCA transformation
- Train a KNN model using PCA-transformed data
- Compare:
  - Accuracy
  - Prediction speed
  - Number of features/components used

### Questions Answered

1. How many features were used in the original model?
2. How many principal components (PCs) were used in the PCA model?
3. Which model performed best on the test set?
4. Which model made predictions faster?

### Technologies Used

- Python
- Pandas
- Scikit-learn
- PCA
- KNeighborsClassifier
- Jupyter Notebook

---

# Folder Structure

```text
KNN_PCA_Comparison/
│
├── PCA_to_Visualize_Clusters_(Practice).ipynb
├── KNN_PCA_Speed_and_Performance.ipynb
└── README.md
