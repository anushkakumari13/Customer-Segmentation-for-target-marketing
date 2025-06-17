# Customer-Segmentation-for-target-marketing


##  Project Overview

This project applies **K-Means Clustering** to perform **customer segmentation**. The goal is to group customers based on features like spending behavior and income level to help businesses tailor marketing strategies.

---

## Dataset

**Dataset Used**: [Mall Customers Dataset (Kaggle)](https://www.kaggle.com/vjchoudhary7/customer-segmentation)

Features included:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

## Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **Libraries**:  
  pandas, numpy, matplotlib, seaborn, scikit-learn

---

## Key Steps

1. **Data Preprocessing**
   - Checked and handled missing values
   - Selected numeric features for clustering
2. **Exploratory Data Analysis (EDA)**
   - Pairplots and histograms to understand distribution
   - Spending behavior visualization
3. **Clustering with K-Means**
   - Used the Elbow Method to find the optimal number of clusters
   - Fitted KMeans and predicted labels
4. **Result Visualization**
   - 2D and 3D cluster visualizations using matplotlib

---

##  Results

- Segmented customers into meaningful clusters:
  - **High income, high spenders**
  - **Low income, high spenders**
  - **Moderate income, moderate spenders**
- These segments can help target promotions and allocate resources more effectively.

---



