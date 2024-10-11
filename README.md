# Clustering-Analysis-Project
Shopping Customer Segmentation (Unsupervised Machine Learning Project) USING K-MEANS CLUSTERING.
This project uses **KMeans Clustering**, an unsupervised machine learning model, to perform customer segmentation. The goal is to classify customers into distinct groups based on their spending behavior and income levels.

## Project Overview

In this analysis, the data was preprocessed, scaled, and then clustered using the **KMeans algorithm**. The primary focus was on identifying customer segments to help businesses understand customer behavior and tailor their marketing strategies accordingly.

### Key Steps:
1. **Data Preprocessing**:
   - Scaled continuous variables (Income and Spending) using Standardization to ensure equal contribution to clustering.
2. **Exploratory Data Analysis**:
   - obtained the descriptives and visualized the distribution of the dataframe
   - Conducted a univariate, bivariate and multivariate analysis on the data
   - obtained the the correlation matrix and visualized using the heat map from **seaborn** 

3. **KMeans Clustering**:
   - Used the **KMeans algorithm** to group customers into clusters.
   - Applied the **Elbow Method** to determine the optimal number of clusters.
   - Visualized the clusters using a scatter plot to gain insights into the customer segments.

4. **Results**:
   - Identified distinct customer segments based on their income and spending behavior.
   - These segments can help businesses target customers more effectively and understand customer needs.

## Files in this Repository

- `Clustering.ipynb`: The Jupyter Notebook containing the full analysis, including preprocessed data, scaling, EDA, and KMeans clustering.
- `Mall_Customers.csv: The dataset used for the analysis.

## How to Run This Project

To replicate this analysis, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/@Omenihu1/Clustering-Analysis-project.git
   
## Key Libraries Used
- *pandas*: For data manipulation and analysis.
- *numpy*: For numerical computations.
- *matplotlib and seaborn*: For data visualization.
- *scikit-learn*: For scaling the data and implementing the KMeans clustering algorithm.

## Insights from the Clustering Analysis
Optimal Number of Clusters: Based on the elbow method, we determined the optimal number of clusters for segmenting the customer base.
Customer Segments: Customers were segmented into groups based on their Income and Spending levels. The visualizations helped in understanding the distinct nature of each segment, making it easier to target marketing efforts and adjust business strategies.

## Conclusion
This analysis provides valuable insights into customer segmentation using KMeans clustering. By identifying customer groups, businesses can enhance their marketing, product development, and customer service strategies.
