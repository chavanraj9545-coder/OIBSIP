# Task 1: Exploratory Data Analysis (EDA) on Retail Sales Data

## Overview
This project is part of the Data Analytics Internship at Oasis Infobyte (OIBSIP). The goal was to perform Exploratory Data Analysis (EDA) on a retail sales dataset to uncover patterns, trends, and insights that could help a retail business make informed decisions.

## Dataset
The dataset used is the Superstore Sales dataset, containing 9,800 records of retail orders with details such as order date, customer segment, product category, and sales value.

## Tools and Libraries Used
- Python
- Pandas (data loading and manipulation)
- NumPy (numerical operations)
- Matplotlib (data visualization)
- Seaborn (statistical visualization)

## Steps Performed
1. Loaded and inspected the dataset structure using `df.info()` and `df.head()`.
2. Checked for missing values using `df.isnull().sum()`.
3. Calculated descriptive statistics (mean, median, mode, standard deviation) for the Sales column.
4. Converted the Order Date column to a proper datetime format and extracted Year and Month.
5. Analyzed monthly sales trends using a time series line chart.
6. Compared total sales across product categories and customer segments using bar charts.
7. Built a correlation heatmap to examine relationships between numeric columns.
8. Identified the top 10 best-selling products using a horizontal bar chart.
9. Summarized findings into actionable business recommendations.

## Key Insights
- Sales follow a clear seasonal pattern, dipping every January-February and peaking around November-December each year.
- Technology is the top-performing category by revenue, closely followed by Furniture and Office Supplies.
- Consumer is the most valuable customer segment, generating significantly more revenue than Corporate or Home Office.
- The average sale value is much higher than the median, indicating a small number of large orders pull the average upward.
- A single product, the Canon imageCLASS 2200 Advanced Copier, generated more than double the sales of any other individual product.
- The dataset required minimal cleaning, with only a small number of missing values in the Postal Code column.

## How to Run
1. Open the notebook `Task1_EDA_Retail_Sales.ipynb` in Google Colab or Jupyter Notebook.
2. Ensure the dataset file `Superstore.csv` is in the same directory (or upload it when prompted in Colab).
3. Run each cell in order from top to bottom.

## Author
Pruthviraj Vikas Chavan — Data Analytics Intern, Oasis Infobyte

## Acknowledgment
This project was completed as part of the Oasis Infobyte Data Analytics Internship Program (OIBSIP).
