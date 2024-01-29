# Customer Segmentation Analysis 

## Overview

This project focuses on analyzing customer segmentation using a dataset obtained from Kaggle. Customer segmentation involves categorizing customers based on various characteristics, enabling businesses to tailor marketing strategies to different groups. The analysis includes exploratory data analysis (EDA), statistical analysis, and k-means clustering.

## Purpose

The primary goal is to gain insights into customer behavior and preferences by identifying distinct customer segments based on spending habits. The project aims to provide valuable information for businesses to make data-driven decisions, enhance customer satisfaction, and improve marketing strategies.

## Data

- **Source:** Kaggle
- **Dataset:** Customer personality data
- **Variables:**
  - Personal Information (Age, Income, Education, Marital Status)
  - Channels of Purchase (Web, Store, Deals, Catalog)
  - Product Categories (Fruits, Wines, Meat, Fish, Sweets, Gold)
  
## Methodology

1. **Exploratory Data Analysis (EDA):**
   - Analyzed average spending on products based on relationship status and education level.
   - Explored the impact of age and combined age with income on purchasing behavior.
   - Studied customer preferences for channels of purchase based on education and relationship status.

2. **Customer Segmentation:**
   - Preprocessed data by handling missing values, outliers, and removing highly correlated features.
   - Utilized k-means clustering algorithm with PCA for dimensionality reduction.
   - Determined the optimal number of clusters using the elbow method (k=3).
   - Identified and analyzed three customer segments: Impulsive Spenders, Loyal Customers, and Surfers.

## Results

1. Customer education and relationship status significantly impact income, spending habits, and purchasing behavior.
2. Three distinct customer segments were identified:
   - Impulsive Spenders: High income, high spending across all categories.
   - Loyal Customers: Average income, moderate spending, loyal to the brand.
   - Surfers: Lowest income, young, visit website frequently, lowest spending.

## Conclusion

Understanding customer segmentation allows companies to tailor marketing strategies to different customer groups. Impulsive Spenders may respond well to promotions, Loyal Customers benefit from personalized services, and Surfers need targeted promotions to convert them into actual customers.

## Future Scope

- Conduct additional surveys to gather more data on customer needs and motivations.
- Explore the impact of gender and combined relationship status with qualifications on customer behavior.
- Examine the influence of customer satisfaction on spending habits for product and service improvements.
