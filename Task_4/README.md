# 📊 Logistic Regression - Binary Classification (Task 4)

## 📝 Overview
This task involves implementing Logistic Regression for binary classification using a real-world dataset. The focus is on proper preprocessing, model training, evaluation, and interpretation.

---

## ⚙️ Steps Performed

- Data Preprocessing:
  - Checked for missing values
  - Handled outliers
  - Handled categorical features with encoding
  - Standardized numerical features with `StandardScaler`
- Train-test split for unbiased evaluation
- Trained a Logistic Regression model using Scikit-learn
- Evaluated model performance using:
  - Confusion Matrix
  - Accuracy, Precision, Recall
  - ROC-AUC Curve and Score
- Explored threshold tuning and its impact on classification outcomes
- Visualized decision boundary and sigmoid function interpretation

---

## 📁 Dataset
- Breast Cancer Wisconsin Dataset
- Features include mix of numeric and categorical variables
- Target variable represents binary class (0/1)

---

## 📦 Technologies Used
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🚀 How to Run the Project

1. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
2. Place the dataset CSV in the working directory.
3. Run the notebook to execute all steps from preprocessing to evaluation.

---

## 📊 Key Insights

- Logistic Regression effectively models binary outcomes using the sigmoid activation function
- Threshold tuning allows control over sensitivity vs specificity based on business needs
- ROC-AUC provides a robust metric to assess overall model discrimination
- Proper feature scaling is critical for model convergence and performance

---

## 🧠 Sigmoid Function Explanation

The sigmoid function converts raw output values from the logistic regression model into probabilities between 0 and 1.

### 🔣 Mathematical Formula:

```text
Sigmoid(z) = 1 / (1 + e^(-z))
```

### 📐 LaTeX Format (for documentation or reports):

```latex
\sigma(z) = \frac{1}{1 + e^{-z}}
```

---

## 🔗 Author

**Nishant Gupta** 
