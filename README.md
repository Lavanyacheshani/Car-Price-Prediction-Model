# 📊 Machine Learning Regression Models - Car & House Price Prediction

## 📝 Overview

This lab demonstrates two regression-based machine learning models for predicting prices:

1. **Car Price Prediction Model**  
2. **House Price Prediction Model**

Both models implement preprocessing, outlier removal, visualization, feature scaling, and linear regression using **Python (Scikit-learn, Pandas, Matplotlib, Seaborn, Statsmodels)**.

---

## 📁 Dataset

### 🚗 Car Dataset
- File: `car data.csv`
- Source: Contains used car data with features like year, fuel type, transmission, etc.
- Target: `Selling_Price`

### 🏠 House Dataset
- File: `House data.csv`
- Source: Contains house sale data with attributes like bedrooms, bathrooms, square footage, etc.
- Target: `price`

---

## 🔧 Technologies Used

- Python 3.x
- Google Colab
- Pandas
- Numpy
- Matplotlib, Seaborn
- Scikit-learn
- Statsmodels
- SciPy

---

## ⚙️ Project Workflow

### 1️⃣ **Data Preprocessing**
- Drop irrelevant columns (e.g., `Car_Name`, `date`)
- Handle missing values
- Encode categorical features
- Outlier detection & removal using **IQR**
- Label Encoding & One-Hot Encoding
- Feature scaling using **StandardScaler**

### 2️⃣ **Exploratory Data Analysis**
- Descriptive statistics
- Pairplots and boxplots
- Correlation matrix

### 3️⃣ **Model Development**
- Split data (train/test)
- Normalize features
- Train **Linear Regression** model

### 4️⃣ **Model Evaluation**
- R² Score
- Mean Squared Error (MSE)

---

## 📈 Results

### 🔹 Car Price Model
- **R² Score**: `0.91`
- **MSE**: `2.16`

### 🔹 House Price Model
- **R² Score**: `0.70` *(varies based on features and cleaning steps)*
- **MSE**: Varies

---


