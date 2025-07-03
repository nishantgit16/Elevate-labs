# 🎯 Support Vector Machines (SVM) - Breast Cancer Classification

## 📌 Objective
Build, visualize, and evaluate SVM models for both linear and non-linear classification tasks using the Breast Cancer dataset.

---

## 📂 Project Overview

This project demonstrates the use of **Support Vector Machines (SVM)** for binary classification on the Breast Cancer dataset from Kaggle.

The notebook includes:

✅ Data loading and inspection  
✅ Outlier detection and capping  
✅ Exploratory Data Analysis (EDA) using visualizations  
✅ Feature scaling with RobustScaler  
✅ SVM model training with different kernels (Linear and RBF)  
✅ Hyperparameter tuning for `C` and `gamma`  
✅ Decision boundary visualization using 2D feature pairs  
✅ Model evaluation using accuracy, confusion matrix, and classification report  

---

## 📊 Dataset Description

- **Source:** [Breast Cancer Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)  
- **Target Variable:** Diagnosis (M = Malignant, B = Benign)  
- **Features:** 30 numeric features describing tumor characteristics  

---

## 🛠️ Technologies Used

- Python 3.10  
- Pandas, NumPy for data handling  
- Matplotlib, Seaborn for visualization  
- Scikit-learn for machine learning  

---

## ⚙️ Step-by-Step Process

### 1️⃣ Data Preprocessing
- Removed unnecessary columns (`id`)  
- Handled outliers for the 'Benign' class using IQR-based capping  
- Combined cleaned features with target variable  
- Encoded target (`M` → 1, `B` → 0)  

### 2️⃣ Exploratory Data Analysis (EDA)
- Distribution plots for each feature  
- Boxplots comparing feature distributions by diagnosis  
- Identified skewness and potential data irregularities  

### 3️⃣ Feature Scaling
- Applied **RobustScaler** to reduce the impact of remaining outliers  
- Ensured scaled features for optimal SVM performance  

### 4️⃣ Model Training & Evaluation
- Trained an **SVM Classifier** with default settings  
- Evaluated using accuracy, confusion matrix, and classification report  

### 5️⃣ Decision Boundary Visualization
- Used 2D feature pairs to visually demonstrate SVM decision boundaries  
- Compared linear vs. RBF kernels for model flexibility  

---

## 📈 Key Insights

- SVM provides strong performance for binary classification problems  
- Outlier handling and feature scaling are essential for optimal results  
- RBF kernel helps capture non-linear boundaries, improving model flexibility  
- Visualizing decision regions enhances model interpretability  

---

## Author
Nishant Gupta
