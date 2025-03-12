# Clustering E-Commerce Data

## Overview
In this project, we aim to cluster e-commerce agent data based on factors such as reviews, delivery time, location, and other relevant features. We will apply **Principal Component Analysis (PCA)** for dimensionality reduction and use the Silhouette Score to evaluate clustering performance and identify the best algorithm. Additionally, we will analyze the impact of outlier removal on clustering by comparing the **Silhouette Score** before and after eliminating anomalies to determine if it improves the clustering quality.

## Features
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features.
- **Dimensionality Reduction**: Using **Principal Component Analysis (PCA)** for better visualization and analysis.
- **Clustering Algorithms**: Applying **K-Means** and **DBSCAN** clustering.
- **Evaluation Metrics**: Measuring **Silhouette Score** to determine the best clustering approach.
- **Anomaly Detection**: Removing anomalies and observing the impact on clustering performance.

## Results
- **Before Removing Anomalies**:
  - K-Means Silhouette Score: `0.2079`
  - DBSCAN Silhouette Score: `0.0804`
- **After Removing Anomalies**:
  - K-Means Silhouette Score: `0.6080` (Improved)
  - DBSCAN Silhouette Score: `-0.8008` (Decreased)

**Note:** This project is intended to demonstrate the technical skills used in clustering and e-commerce data analysis.
