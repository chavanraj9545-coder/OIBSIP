# Task 2: Customer Segmentation Analysis

## Overview
This project is part of the Data Analytics Internship at Oasis Infobyte (OIBSIP). The goal was to perform customer segmentation analysis for a mall, grouping customers into distinct segments based on their behavior and purchase patterns. This segmentation can inform targeted marketing strategies and improve overall business decisions.

## Dataset
The dataset used is the Mall Customer Segmentation Data, containing 200 records with details such as CustomerID, Gender, Age, Annual Income, and Spending Score.

## Tools and Libraries Used
- Python
- Pandas (data loading and manipulation)
- NumPy (numerical operations)
- Matplotlib (data visualization)
- Seaborn (statistical visualization)
- Scikit-learn (K-means clustering)

## Steps Performed
1. Loaded and inspected the dataset structure using `df.info()` and checked for missing values.
2. Calculated descriptive statistics for Age, Annual Income, and Spending Score.
3. Visualized the distribution of Age, Annual Income, and Spending Score using histograms.
4. Selected Annual Income and Spending Score as the two features for clustering.
5. Used the Elbow Method to determine the optimal number of clusters, which was found to be 5.
6. Applied the K-means clustering algorithm to group customers into 5 segments.
7. Visualized the resulting clusters using a scatter plot with cluster centroids.
8. Calculated the average Age, Annual Income, and Spending Score for each cluster to interpret their characteristics.
9. Summarized findings into actionable business recommendations for each segment.

## Key Insights
- Customers were grouped into 5 distinct segments: Average Customers, High Value Customers, Young Big Spenders, Untapped Potential, and Low Engagement Customers.
- The largest segment (Cluster 0) consists of average-income, average-spending customers, making up about 41% of the customer base.
- The most valuable segment (Cluster 1) is young, high-income, and high-spending — these customers should be prioritized for retention through loyalty programs and personalized offers.
- One segment (Cluster 3) has high income but low spending, representing untapped revenue potential that targeted marketing could help unlock.

## How to Run
1. Open the notebook `Task2_Customer_Segmentation.ipynb` in Google Colab or Jupyter Notebook.
2. Ensure the dataset file `Mall_Customers.csv` is in the same directory (or upload it when prompted in Colab).
3. Run each cell in order from top to bottom.

## Author
Pruthviraj Vikas Chavan — Data Analytics Intern, Oasis Infobyte

## Acknowledgment
This project was completed as part of the Oasis Infobyte Data Analytics Internship Program (OIBSIP).
