# Task 3: Predicting House Prices with Linear Regression

## Overview
This project is part of the Data Analytics Internship at Oasis Infobyte (OIBSIP). The goal was to build a Linear Regression model to predict house sale prices based on various features such as overall quality, living area, garage capacity, and more.

## Dataset
The dataset used is the House Prices: Advanced Regression Techniques dataset from Kaggle, containing 1,460 house records with 81 features including the target variable SalePrice.

## Tools and Libraries Used
- Python
- Pandas (data loading and manipulation)
- NumPy (numerical operations)
- Matplotlib (data visualization)
- Seaborn (statistical visualization)
- Scikit-learn (Linear Regression model, train/test split, evaluation metrics)

## Steps Performed
1. Loaded the dataset and inspected its structure.
2. Identified and handled missing values by filling with column medians.
3. Selected numeric features for model training.
4. Calculated descriptive statistics for all numeric columns.
5. Visualized the SalePrice distribution and applied log transformation to normalize it.
6. Analyzed feature correlations with SalePrice and visualized the top 15 most correlated features.
7. Created a scatter plot of the strongest predictor (GrLivArea) vs SalePrice.
8. Split the data into 80% training and 20% testing sets.
9. Trained a Linear Regression model on the training set.
10. Evaluated the model using RMSE and R² score on the test set.
11. Visualized predicted vs actual sale prices and plotted residuals to check for model bias.

## Key Insights
- Overall Quality (OverallQual) and Above Ground Living Area (GrLivArea) are the strongest predictors of house sale price.
- Sale prices were right-skewed, so a log transformation was applied to improve model performance.
- The model achieved an R² score of [fill in your value], explaining [X]% of the variance in house prices.
- The residual plot showed errors scattered randomly around zero, confirming the model is unbiased.
- Future improvements could include feature engineering, encoding categorical variables, and trying advanced models like Random Forest or Gradient Boosting.

## How to Run
1. Open the notebook `Task3_House_Price_Prediction.ipynb` in Google Colab or Jupyter Notebook.
2. Ensure the dataset file `HousePrices.csv` is in the same directory (or upload it when prompted in Colab).
3. Run each cell in order from top to bottom.

## Author
Pruthviraj Vikas Chavan — Data Analytics Intern, Oasis Infobyte

## Acknowledgment
This project was completed as part of the Oasis Infobyte Data Analytics Internship Program (OIBSIP).
