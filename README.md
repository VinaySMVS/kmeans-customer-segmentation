# 🧠 KMeans Customer Segmentation – Elevant Labs Task 8

This repository contains a machine learning project focused on **unsupervised clustering** using the **K-Means algorithm**. The goal is to segment customers into meaningful groups based on their characteristics, such as income and spending score.


## 🎯 Task Objective

Perform **customer segmentation** using **KMeans clustering** to:
- Group customers with similar behavior
- Help businesses identify high-value and low-value customers
- Enable data-driven targeted marketing

---

## 📁 Dataset

- The dataset includes features like:
  - Customer ID
  - Gender
  - Age
  - Annual Income
  - Spending Score

---

## 🔍 Task Steps

### 1. Load and Explore Dataset
- Loaded CSV using `pandas`
- Performed initial inspection with `.head()` and `.info()`

### 2. Preprocessing
- Checked for missing values
- Selected numeric features for clustering (e.g., `Annual Income`, `Spending Score`)
- Applied **feature scaling** using `StandardScaler`

### 3. Elbow Method
- Used inertia scores to determine the **optimal number of clusters (k)**
- Visualized the elbow curve to find the "elbow point"

### 4. Train KMeans Clustering Model
- Applied KMeans with optimal number of clusters (e.g., `k = 4`)
- Predicted cluster labels and added them to the original DataFrame

### 5. Visualize Clusters
- Used `Seaborn` and `Matplotlib` to plot clusters
- Each cluster visualized in 2D space using selected features

### 6. Interpret Results
- Observed meaningful segmentation patterns (e.g., high income, low spenders)
- Each cluster represents a customer group with unique traits

---

## 📈 Visualizations Included

- 📊 Elbow Curve to select optimal `k`
- 🎨 Cluster scatter plot (Annual Income vs Spending Score)

---

## 🧪 Technologies Used

| Tool          | Use Case                          |
|---------------|-----------------------------------|
| Python        | Core programming language         |
| Pandas        | Data handling and processing      |
| scikit-learn  | KMeans, scaling, model fitting    |
| Matplotlib    | Visualizing elbow plot, clusters  |
| Seaborn       | Advanced cluster plotting         |
| JupyterLab    | Interactive notebook environment  |

---

## 📬 Output Summary

- Model segmented customers into **4 distinct clusters**
- Clusters revealed key business insights (e.g., luxury spenders vs budget-conscious)

---

## 🚀 Run This Project

### Clone the repository
```bash
git clone https://github.com/VinaySMVS/kmeans-customer-segmentation.git
cd kmeans-customer-segmentation
