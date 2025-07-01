#  K-Nearest Neighbors (KNN) Classification - Iris Dataset

## 📌 Objective
Implement and explain K-Nearest Neighbors (KNN) classification on the Iris dataset using Scikit-learn, Pandas, and Matplotlib.

---

## 📂 Project Overview
This notebook demonstrates the complete process of applying KNN classification to the Iris dataset, including:

- Data loading and exploration  
- Handling missing values and cleaning  
- Detecting and managing outliers for stability  
- Feature normalization (critical for KNN)  
- Model training with various values of `k`  
- Model evaluation with accuracy and confusion matrix  
- Decision boundary visualization for feature pairs  

---

## 📊 Dataset Description

**Iris Dataset**  
The classic Iris dataset contains flower measurements for three species:

- **Features:**  
  - Sepal length (cm)  
  - Sepal width (cm)  
  - Petal length (cm)  
  - Petal width (cm)  

- **Target:**  
  - Species (Setosa, Versicolor, Virginica)  

Total samples: 150  

---

## 🛠 Technologies Used

- Python 3.x  
- Pandas & NumPy for data manipulation  
- Matplotlib & Seaborn for visualization  
- Scikit-learn for machine learning tasks  

---

## ⚙️ Step-by-Step Process

1. **Data Import & Inspection**  
   Loaded the dataset and performed basic exploration.  

2. **Outlier Handling**  
   Detected and addressed outliers to improve model robustness.  

3. **Feature Normalization**  
   Applied StandardScaler to standardize features (KNN is distance-based, scaling is critical).  

4. **Train-Test Split**  
   Split the data for reliable model evaluation.  

5. **KNN Model Training**  
   Trained `KNeighborsClassifier` and experimented with different values of `k`.  

6. **Model Evaluation**  
   Evaluated performance using:  
   - Accuracy Score  
   - Confusion Matrix  

7. **Decision Boundary Visualization**  
   Visualized decision regions for various feature pairs to understand model behavior.  

---

## 📈 Key Insights

- Proper scaling significantly impacts KNN performance  
- Choosing the right `k` balances bias-variance trade-off  
- Visualizing decision boundaries helps interpret model decision-making  
- Outlier handling enhances stability and reliability  

---

## Author
Nishant Gupta
