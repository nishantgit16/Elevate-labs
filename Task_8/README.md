# K-Means Clustering for Customer Segmentation

## Project Overview

This project applies **K-Means Clustering** to segment customers based on demographics and spending behavior from the Mall Customer Segmentation dataset. The goal is to identify distinct customer groups to enable data-driven marketing and business decisions.

## Dataset

- **Source:** Mall Customer Segmentation Dataset (Kaggle)
- **Features:**
  - CustomerID: Unique customer identifier
  - Gender: Male/Female
  - Age: Age of the customer
  - Annual Income (k\$): Income in thousands
  - Spending Score (1-100): Customer's spending behavior rating

## Objective

- Perform Exploratory Data Analysis (EDA) to understand customer characteristics
- Preprocess the dataset for clustering
- Identify the optimal number of customer segments using the Elbow Method
- Apply K-Means Clustering to group customers
- Visualize clusters using PCA-reduced features
- Evaluate clustering performance using Silhouette Score

## Tools and Libraries

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Workflow Summary

1. **Data Loading & Inspection**

   - Imported dataset and checked for missing values, data types, and descriptive statistics.

2. **Exploratory Data Analysis (EDA)**

   - Visualized distributions of Age, Annual Income, and Spending Score to understand spread and identify patterns.

3. **Data Preprocessing**

   - Converted Gender into numerical format using one-hot encoding.
   - Scaled numerical features to ensure uniformity during clustering.

4. **Optimal Cluster Identification**

   - Used the Elbow Method to determine the ideal number of clusters (k).

5. **K-Means Clustering**

   - Applied K-Means with the chosen k value to segment customers.

6. **Dimensionality Reduction & Visualization**

   - Reduced features to 2D using Principal Component Analysis (PCA) for visualization.
   - Plotted clusters to visually interpret customer segments.

7. **Cluster Evaluation**

   - Calculated Silhouette Score to assess clustering quality and separation.

## Insights & Conclusion

- Customers were segmented into distinct groups based on their spending patterns and demographics.
- PCA visualization demonstrated visible cluster separation.
- Silhouette Score indicated moderately good clustering performance.
- The clustering insights can be leveraged for targeted marketing and customer relationship strategies.

## Author

Nishant Gupta
