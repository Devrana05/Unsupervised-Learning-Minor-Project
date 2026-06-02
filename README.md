# SmartCart — E-commerce Customer Segmentation System

An Unsupervised Machine Learning project that segments e-commerce customers based on their purchasing behavior and demographic information. Built as part of my study of clustering techniques, this project covers the complete workflow from data preprocessing to customer segmentation and cluster analysis.

---

## Project Overview

SmartCart uses clustering algorithms to group customers with similar characteristics and shopping patterns. The project aims to help businesses better understand their customers and create targeted marketing strategies.

The workflow includes data cleaning, feature engineering, exploratory data analysis, dimensionality reduction, clustering, and cluster interpretation.

---

## Dataset

> **Note:** The dataset is not included in this repository. To run the notebook, you will need to provide the customer dataset and place it in the project root directory. Can find on kaggle.

### Features Used

| Feature Category   | Examples                                        |
| ------------------ | ----------------------------------------------- |
| Demographics       | Age, Education, Marital Status                  |
| Financial          | Income                                          |
| Family Information | Number of Children                              |
| Customer Activity  | Website Visits, Purchases                       |
| Product Spending   | Wine, Fruits, Meat, Fish, Sweets, Gold Products |
| Customer History   | Customer Tenure                                 |

---

## Notebook Workflow

### 1. Load & Inspect Data

* Import dataset
* Check data types
* Identify missing values
* Review descriptive statistics

### 2. Data Cleaning

* Handle missing values
* Remove inconsistent records
* Detect and remove outliers

### 3. Feature Engineering

Created new features such as:

* **Age**
* **Customer Tenure**
* **Total Spending**
* **Total Children**

These features help capture customer behavior more effectively.

### 4. Exploratory Data Analysis (EDA)

* Distribution analysis
* Correlation heatmaps
* Spending pattern analysis
* Customer behavior visualization

### 5. Data Encoding & Scaling

* One-Hot Encoding for categorical variables
* Standardization using StandardScaler

### 6. Dimensionality Reduction

Applied **Principal Component Analysis (PCA)** to reduce feature dimensions while preserving important information.

### 7. Customer Segmentation

#### K-Means Clustering

* Used the Elbow Method to find the optimal number of clusters
* Evaluated clustering performance

#### Agglomerative Hierarchical Clustering

* Generated dendrograms
* Compared results with K-Means clustering

### 8. Cluster Analysis

Analyzed customer groups based on:

* Income
* Spending behavior
* Purchase frequency
* Customer engagement

---

## Clustering Models Used

### K-Means Clustering

A centroid-based clustering algorithm that partitions customers into distinct groups based on similarity.

### Agglomerative Hierarchical Clustering

A bottom-up clustering approach that builds clusters by merging similar customer groups step by step.

---

## Why Customer Segmentation?

Customer segmentation helps businesses:

* Identify high-value customers
* Create personalized marketing campaigns
* Improve customer retention
* Understand purchasing behavior
* Optimize business strategies

---

## Key Takeaways

* Data preprocessing plays a major role in clustering quality.
* PCA helps reduce dimensionality while maintaining useful information.
* K-Means efficiently groups customers into distinct segments.
* Agglomerative Clustering provides a hierarchical view of customer relationships.
* Customer segmentation can generate actionable business insights from raw customer data.

---

## Tech Stack

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Scikit-learn` · `PCA` · `K-Means` · `Agglomerative Clustering`

---

## Future Improvements

* Try DBSCAN for density-based clustering.
* Deploy the model as a web application.
* Build an interactive dashboard for business users.
* Perform advanced cluster profiling and recommendations.

---

## Author

**Dev Rana**

B.Tech Computer Science Engineering Student

This project was developed as part of my learning journey in Machine Learning, focusing on Unsupervised Learning and Customer Segmentation.
