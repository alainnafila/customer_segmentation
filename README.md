# Customer Segmentation Analysis
Customer Segmentation using K-Means

## Overview
This project applies K-Means Clustering to segment mall customers based on demographic and spending behavior.

## Dataset
The dataset contains:
- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Methods
- Data preprocessing
- Feature scaling
- Elbow Method
- K-Means Clustering
- Data visualization

## Tools
- Python
- Pandas
- Scikit-learn
- Matplotlib

## Results

The Elbow Method indicated that the optimal number of clusters is K=5.
- **Cluster 1 (81 customers)**  
  Customers with average annual income and average spending behavior.
- **Cluster 2 (39 customers)**  
  Customers with high annual income and high spending score.  
  This cluster represents premium or highly valuable customers.
- **Cluster 3 (22 customers)**  
  Customers with low annual income but high spending score.  
  These customers tend to spend actively despite lower income levels.
- **Cluster 4 (35 customers)**  
  Customers with high annual income but low spending score.  
  They have strong purchasing potential but relatively low spending activity.
- **Cluster 5 (23 customers)**  
  Customers with low annual income and low spending score.  
  This group shows conservative spending behavior.
