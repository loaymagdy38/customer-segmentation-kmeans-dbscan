# 💳 Customer Credit Card Segmentation

## 📌 Project Overview

End-to-End **Unsupervised Machine Learning pipeline** for customer segmentation using **KMeans** and **DBSCAN** clustering algorithms.

The objective is to uncover hidden customer behavior patterns to support:
- Targeted marketing strategies
- Customer profiling
- Risk analysis
- Data-driven business decisions

---

## 📂 Dataset

- **Source:** Kaggle Credit Card Dataset
- **Total Customers:** 8,950
- **Number of Features:** 18
- Dataset includes transactional and behavioral credit card metrics

---

## 🔎 Workflow

### 1️⃣ Data Understanding & EDA

- Summary statistics
- Distribution analysis
- Outlier visualization
- Missing value inspection

### 2️⃣ Data Preprocessing

- Handling missing values using **Median Imputation**
- Outlier detection using **IQR (Interquartile Range)**
- Outlier treatment using **Clipping**
- Feature scaling using **StandardScaler**
- Removed identifier column (`CUST_ID`)

---

## 🤖 Clustering Algorithms

### 🔹 KMeans

- Optimal K selected using **Elbow Method**
- Final clusters: **4**
- Silhouette Score: **0.19**
- Produced stable and interpretable customer segments

### 🔹 DBSCAN

- Density-based clustering
- Handles noise detection
- Silhouette Score: **-0.25**
- Sensitive to hyperparameters (`eps`, `min_samples`)

---

## 📊 Visualizations

- Elbow Method Plot
- Boxplots (Before & After Outlier Treatment)
- PCA 2D Cluster Visualization
- KMeans vs DBSCAN Comparison

---

## 🏆 Conclusion

- KMeans provided clearer segmentation and better cluster quality.
- DBSCAN was effective in detecting noise and anomalies.
- KMeans is more suitable for business segmentation in this dataset.

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 Project Highlights

- End-to-End ML Workflow
- Advanced Data Cleaning & Preprocessing
- IQR-Based Outlier Treatment
- Cluster Evaluation using Silhouette Score
- Dimensionality Reduction using PCA
- Business Interpretation of Clusters
