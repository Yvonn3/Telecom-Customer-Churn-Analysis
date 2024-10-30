# Telecom-Customer-Churn-Analysis

## Overview
This project focuses on performing exploratory data analysis (EDA) and predictive modeling to identify customers at risk of churn in a telecom company. We use a dataset of telecom customer data and apply several preprocessing techniques, clustering methods, and predictive modeling approaches to address customer churn.

## Project Objectives
1. **Exploratory Data Analysis (EDA)**: Investigate and clean the data, handling missing values, outliers, and scaling numeric variables.
2. **Clustering**: Apply PCA and K-Means to group customers into segments based on their behavior and service usage.
3. **Churn Prediction Models**: Build and compare two machine learning models—Logistic Regression and Random Forest—to predict customer churn and identify the top factors contributing to it.
4. **Insights and Recommendations**: Based on model results and customer segmentation, recommend actionable strategies to reduce churn.

## Data
The dataset contains multiple features related to customer demographics, service usage, and billing. Important columns include:
- **Demographics**: Age, number of dependents, marital status
- **Service Usage**: Internet service type, monthly GB usage, streaming services
- **Billing Information**: Monthly charge, total revenue, refunds, and extra charges
- **Target Variable**: `viewer_status` indicating whether a customer churned or stayed

## Project Structure

## Requirements
To run this project, you will need the following libraries:
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

You can install them using:

## Steps to Run
1. **Data Preprocessing**:
   - Load the dataset and perform exploratory analysis to understand the data distribution, handle missing values, and create dummy variables for categorical features.
   

2. **Clustering**:
- Apply PCA to reduce dimensionality and use K-Means clustering to segment customers based on their usage patterns.


3. **Churn Prediction Models**:
- Build two models (Logistic Regression and Random Forest) to predict churn and evaluate their accuracy.


4. **Visualizations**:
- Correlation heatmaps, box plots for outlier detection, and PCA variance plots are generated during EDA and clustering for better understanding.


## Key Findings
- The top features influencing customer churn were: `tenure_in_months`, `subscription_type_Month-to-Month`, and `monthly_charge`.
- Random Forest performed better than Logistic Regression with a mean accuracy of 85%.
- Cluster 2 customers, who have high monthly charges and tend to use more internet services, are most at risk of churn.

## Recommendations
To reduce churn, focus on:
- Offering targeted subscription plans with flexible pricing for high-risk customer segments.
- Improving customer satisfaction by addressing service-related complaints, especially for those using Offers C, D, and E.
