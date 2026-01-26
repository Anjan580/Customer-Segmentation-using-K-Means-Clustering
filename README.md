# 📊 Customer Segmentation Using K-Means Clustering

## 📌 Project Overview
This project focuses on **customer segmentation** using the **K-Means Clustering** algorithm.
By analyzing customer purchasing behavior, businesses can identify distinct customer groups and apply targeted marketing strategies.

---

## 🧠 Problem Statement
Understanding customer behavior is crucial for business growth.
This project groups customers based on their **Annual Income** and **Spending Score** to help businesses:
- Improve decision-making
- Personalize marketing campaigns
- Increase customer retention

---

## 📁 Dataset
- **Dataset Name:** Mall_Customers.csv
- **Description:** Contains customer demographic and spending-related data.
- **Key Features:**
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Project Workflow

### 1️⃣ Import Libraries
Required libraries for data analysis, visualization, and clustering are imported.

### 2️⃣ Data Collection & Exploration
- Load dataset using Pandas
- Inspect data shape and structure
- Understand basic statistics

### 3️⃣ Feature Selection
Selected features for clustering:
- Annual Income
- Spending Score

### 4️⃣ Elbow Method
Used to determine the optimal number of clusters by analyzing WCSS values.

### 5️⃣ K-Means Clustering
- Trained the K-Means model
- Assigned cluster labels to customers

### 6️⃣ Visualization
- Visualized clusters using scatter plots
- Displayed centroids for better interpretation

---

## 📈 Results & Insights
- Customers are divided into meaningful clusters
- Each cluster represents a unique purchasing behavior
- Useful for targeted marketing and business planning

---
