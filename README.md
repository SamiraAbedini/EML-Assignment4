# Assignment 4: Unsupervised Learning - Dimensionality Reduction and Clustering

This repository contains the Jupyter Notebook for **Assignment 4** of the **Elements of Machine Learning** course. The assignment focuses on **unsupervised learning techniques**, specifically clustering and dimensionality reduction.

## Contents

### 1. Clustering
- **Dataset**: Digits dataset from scikit-learn (8x8 pixel images of handwritten digits).
- **Objective**: Cluster the data into groups without using the labels.
- **Key Tasks**:
  - Visualizing sample digits.
  - Using the **k-means clustering** algorithm to group the data.
  - Determining the optimal number of clusters using the **elbow method**.
  - Exploring clustering as a preprocessing step for **semi-supervised learning**.

### 2. Dimensionality Reduction (PCA)
- **Objective**: Apply **Principal Component Analysis (PCA)** to reduce the dimensionality of the data while retaining maximum variance.
- **Key Tasks**:
  - Perform PCA on the Digits dataset.
  - Train and evaluate a **Logistic Regression** model with different numbers of PCA components.
  - Identify the optimal number of PCA components for a balance between performance and complexity.

## Dependencies
The following Python libraries are required to run the notebook:
- `numpy`
- `matplotlib`
- `scikit-learn`

