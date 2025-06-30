# 🌲 Heart Disease Prediction using Decision Trees & Random Forest

## 📌 Project Overview
This project explores tree-based machine learning models to predict the presence of heart disease. It includes model training, evaluation, visualization, and interpretation using the Heart Disease dataset.

---

## 🗂 Dataset
- Source: [Heart Disease Dataset on Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- Contains medical and demographic attributes for binary classification (Heart Disease: Yes/No)

---

## 🛠 Tools & Libraries
- Python (Pandas, Numpy)
- Seaborn, Matplotlib, Plotly
- Scikit-learn
- Graphviz (for tree visualization)

---

## 🔍 Key Concepts
- Decision Tree Classifier: Intuitive, interpretable model for classification
- Random Forest: Ensemble method reducing overfitting and improving accuracy
- Feature Importance: Identify key health indicators
- Cross-Validation: Reliable performance estimation

---

## ⚙️ Workflow Steps

1. Load and explore dataset
2. Categorize features (Continuous vs. Categorical)
3. Visualize data (Pie charts, Histograms, Correlation Heatmap)
4. Train-Test Split (70%-30%)
5. Train Decision Tree, visualize structure
6. Evaluate using Accuracy, Confusion Matrix, Precision, Recall, F1-Score
7. Tune `max_depth` to prevent overfitting
8. Train and compare Random Forest
9. Analyze feature importance
10. Perform Cross-Validation

---

## ✅ Results & Insights

- Decision Tree achieved high initial accuracy, but risked overfitting
- Applying `max_depth` improved generalization at slight accuracy trade-off
- Random Forest provided improved stability and robustness
- Feature Importance revealed key predictors for heart disease

---

## Author
- Nishant Gupta
