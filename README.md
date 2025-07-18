# 🛍️ Customer Segmentation for Mall Marketing

A machine learning project that uses unsupervised learning (K-Means Clustering + PCA) to segment mall customers based on demographic and spending behavior, enabling businesses to run more targeted and effective marketing campaigns.

## 🎯 Objective
To identify distinct customer groups using clustering techniques so that businesses can tailor marketing strategies, offers, and services for each segment.

## 🧠 Problem Statement
Given a dataset of mall customers with features like Age, Gender, Annual Income, and Spending Score, the goal is to:
- Cluster customers into meaningful groups
- Understand behavioral patterns
- Assist in targeted marketing

## 🛠 Tools & Technologies
- **Language:** Python  
- **Libraries:** `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib`
- **Techniques:** K-Means Clustering, PCA, StandardScaler, One-Hot Encoding

## 📁 Dataset
- **Source:** [Kaggle – Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial)
- **Features:**
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

## 📊 Project Workflow
1. Load and Explore Data  
2. Data Cleaning and Encoding  
3. Feature Scaling  
4. Find Optimal Clusters (Elbow Method)  
5. Apply K-Means Clustering  
6. Dimensionality Reduction with PCA  
7. Visualize Segments  
8. Cluster Interpretation  
9. Model Saving with Joblib

## 🔍 Results & Insights
- Identified **3 unique customer segments** based on behavior
- PCA visualization clearly separated clusters in 2D space
- Insights:
  - Cluster 0: High-income, high-spending customers
  - Cluster 1: Low-income, low-spending
  - Cluster 2: Young moderate-income active shoppers

## 💾 Model Export
- Trained KMeans model saved as `customer_segmentation_model.pkl` using `joblib`
- Ready for deployment or integration into apps

## ✅ How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/customer-segmentation.git
   cd customer-segmentation

