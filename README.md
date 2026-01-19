#  Exploratory Data Analysis (EDA)



This repository contains the **Exploratory Data Analysis (EDA)** performed as part of the **AI & ML Internship Task 3**.  
The goal of this task is to understand the dataset, identify patterns, detect outliers, and analyze feature relationships using visualizations.

---



### Iris Dataset
- Source: UCI Machine Learning Repository / sklearn
- Total Records: 150
- Features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
  - Species (Target variable)

---

## 🛠 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 What is Exploratory Data Analysis (EDA)?

Exploratory Data Analysis (EDA) is the process of analyzing datasets to summarize their main characteristics using:
- Statistical methods
- Visualizations
- Correlation analysis
- Outlier detection

EDA helps in understanding data behavior before building machine learning models.

---

## 📊 EDA Steps Performed

### 1️⃣ Data Loading & Inspection
- Loaded the dataset using `sklearn`
- Checked data shape, columns, and data types
- Verified missing values

### 2️⃣ Statistical Summary
- Used `describe()` to understand:
  - Mean
  - Standard deviation
  - Min & max values

### 3️⃣ Distribution of Numerical Features
- Used **histograms** to analyze feature distributions
- Observed that petal features show better separation

### 4️⃣ Categorical Feature Analysis
- Used **count plot** for species distribution
- Dataset is balanced across all species

### 5️⃣ Outlier Detection
- Used **box plots**
- Minor outliers detected in sepal width
- No extreme outliers affecting performance

### 6️⃣ Correlation Analysis
- Used **heatmap**
- Strong correlation between:
  - Petal Length & Petal Width
- Weak correlation for Sepal Width

---

## ⭐ Feature Importance (Observation Based)

Most important features:
- Petal Length
- Petal Width

Least important feature:
- Sepal Width

These observations help in feature selection for machine learning models.

---

## 📝 Conclusion  

This Exploratory Data Analysis (EDA) project provided a clear understanding of the dataset and its underlying patterns. Through various visualizations and statistical techniques, important insights were derived regarding feature distributions, correlations, and outliers.

---
