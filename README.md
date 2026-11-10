# SmartCart – Customer Segmentation Using Clustering

## Project Overview

SmartCart is a growing e-commerce platform that serves customers across multiple countries. With a dataset containing 2,240 customer records and 22 attributes, the company has access to valuable information about customer demographics, purchasing habits, spending patterns, and website engagement.

However, using the same marketing strategy for every customer makes it difficult to understand individual customer needs, identify high-value customers, and recognize customers who may be at risk of disengaging.

The **SmartCart Clustering System** aims to solve this problem using **unsupervised machine learning**. By applying clustering algorithms, this project groups customers with similar behaviours into meaningful segments.

These segments can help businesses better understand their customers and make data-driven decisions about personalized marketing, customer engagement, and retention strategies.

## Project Objectives

- Identify distinct customer segments based on purchasing behaviour and engagement.
- Understand customer spending patterns across different product categories.
- Analyse purchase frequency across web, catalog, and physical stores.
- Identify high-value and highly engaged customer groups.
- Explore customer loyalty and potential disengagement patterns.
- Support more targeted marketing and customer retention strategies.

## Dataset Description

The dataset contains **2,240 customer records and 22 attributes**. Each row represents an individual customer.

The features are divided into the following categories:

### 1. Customer Demographics

| Feature | Description |
|---|---|
| ID | Unique customer identifier |
| Year_Birth | Customer's year of birth |
| Education | Highest education level achieved |
| Marital_Status | Customer's marital status |
| Income | Yearly household income |
| Kidhome | Number of small children in the household |
| Teenhome | Number of teenagers in the household |
| Dt_Customer | Date the customer enrolled with SmartCart |

### 2. Purchase Behaviour – Amount Spent

| Feature | Description |
|---|---|
| MntWines | Amount spent on wine products |
| MntFruits | Amount spent on fruit products |
| MntMeatProducts | Amount spent on meat products |
| MntFishProducts | Amount spent on fish products |
| MntSweetProducts | Amount spent on sweet products |
| MntGoldProds | Amount spent on gold products |

### 3. Purchase Behaviour – Frequency

| Feature | Description |
|---|---|
| NumDealsPurchases | Purchases made using discounts |
| NumWebPurchases | Purchases made through the website |
| NumCatalogPurchases | Purchases made through catalogs |
| NumStorePurchases | Purchases made in physical stores |
| NumWebVisitsMonth | Number of website visits per month |

### 4. Customer Feedback and Loyalty

| Feature | Description |
|---|---|
| Recency | Number of days since the last purchase |
| Complain | Whether the customer complained in the last two years (1 = Yes, 0 = No) |

## Technologies and Libraries

- **Python** – Main programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Scikit-learn** – Machine learning and clustering
- **Jupyter Notebook** – Development and experimentation

## Machine Learning Approach

This project uses **unsupervised learning**, where the algorithm identifies patterns and groups customers without predefined labels.

The customer segmentation workflow includes:

1. **Data Understanding:** Explore the dataset, inspect data types, understand feature distributions, and identify missing values.
2. **Data Cleaning:** Handle missing values, duplicates, and inconsistent data.
3. **Exploratory Data Analysis (EDA):** Analyse customer demographics, spending habits, purchase frequency, and engagement patterns.
4. **Feature Engineering:** Create meaningful features where appropriate to improve customer behaviour analysis.
5. **Data Preprocessing:** Encode categorical variables and scale numerical features before clustering.
6. **Dimensionality Reduction:** Apply Principal Component Analysis (PCA), where appropriate, to reduce dimensionality and visualize customer patterns.
7. **Optimal Cluster Selection:** Use the Elbow Method and other evaluation techniques to determine a suitable number of clusters.
8. **Customer Segmentation:** Apply clustering algorithms to group customers based on similarities.
9. **Cluster Analysis:** Compare cluster characteristics to understand spending, purchasing frequency, and engagement levels.

## Business Applications

The resulting customer segments can help SmartCart:

- **Personalized Marketing:** Create targeted campaigns based on customer spending and purchasing preferences.
- **Customer Retention:** Identify customers with low engagement or long periods since their last purchase.
- **High-Value Customer Identification:** Recognize customers with higher spending and frequent purchases.
- **Product Recommendations:** Understand product preferences across different customer groups.
- **Marketing Optimization:** Develop suitable discount and promotional strategies for different segments.


## Key Learnings

Through this project, I explored:

- Unsupervised machine learning and customer segmentation.
- Exploratory data analysis and feature engineering.
- Data preprocessing and feature scaling.
- Clustering algorithms and cluster evaluation.
- PCA for dimensionality reduction and visualization.
- Interpreting customer behaviour using cluster profiles.
- Translating machine learning results into business insights.

## Future Improvements

- Experiment with additional clustering algorithms such as DBSCAN and hierarchical clustering.
- Compare clustering quality using appropriate evaluation metrics.
- Develop a customer segmentation dashboard using Power BI or Tableau.
- Build a recommendation strategy based on identified customer segments.
- Explore methods to identify customers at risk of disengagement.

## Conclusion

The SmartCart Clustering System demonstrates how unsupervised machine learning can uncover hidden patterns in customer behaviour.

By grouping customers based on their spending habits, purchasing frequency, and engagement levels, businesses can move beyond generic marketing strategies and make more informed decisions about customer targeting, loyalty, and retention.

**The ultimate goal is to transform customer data into meaningful business insights through machine learning.**