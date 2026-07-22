# Clustering Mini Project

## Overview

This project demonstrates the implementation and comparison of three popular unsupervised machine learning clustering algorithms using Python and Scikit-learn. The goal is to group similar data points into clusters and evaluate the performance of each algorithm using the **Silhouette Score**.

---

## Project Objective

The objective of this project is to explore different clustering techniques and compare their performance to determine which algorithm produces the best clustering results for the dataset.

---

## Dataset

The project uses the **Wholesale Customers Dataset**, which is a clean and well-structured dataset.

The dataset did not contain missing values or duplicate records, so only minimal preprocessing was required before training the models.

The preprocessing steps included:

* Checking for missing values.
* Checking for duplicate records.
* Selecting the numerical features.
* Standardizing the data using **StandardScaler**, which is an essential step for distance-based clustering algorithms.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Workflow

### 1. Data Preprocessing

The dataset was inspected to ensure data quality. Since it was already clean, only feature scaling was performed using **StandardScaler** to place all features on the same scale before clustering.

### 2. K-Means Clustering

* Trained the K-Means algorithm.
* Assigned cluster labels.
* Evaluated the clustering quality using the Silhouette Score.

### 3. Hierarchical Clustering

* Applied Agglomerative (Hierarchical) Clustering.
* Generated cluster labels.
* Evaluated the clustering performance using the Silhouette Score.

### 4. DBSCAN

* Applied the DBSCAN clustering algorithm.
* Removed noise points before evaluation.
* Calculated the Silhouette Score for valid clusters.

### 5. Model Comparison

The three clustering algorithms were compared based on their **Silhouette Scores** to determine which model produced the best cluster separation.

---

## Evaluation Metric

The project uses the **Silhouette Score** to evaluate clustering performance.

A higher Silhouette Score indicates:

* Better separation between clusters.
* Higher similarity among data points within the same cluster.

---

## Skills Demonstrated

* Data Preprocessing
* Feature Scaling
* Unsupervised Machine Learning
* Clustering Techniques
* Model Evaluation
* Data Visualization

---

## Key Takeaways

* Different clustering algorithms produce different cluster structures.
* Feature scaling is essential for distance-based clustering methods.
* The Silhouette Score provides an effective way to compare clustering performance.
* Selecting the appropriate clustering algorithm depends on the characteristics of the dataset.

---

**Author:** Sumaya Hassan
