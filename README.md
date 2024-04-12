# Project Title: Predictive Modeling for the Copper Industry
## Overview:
This project focuses on developing predictive models for the copper industry to address challenges related to sales prediction and lead classification. The dataset contains various variables including continuous and categorical features. The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and creating a user-friendly web application using Streamlit for model prediction.
## Steps:
### Data Understanding:
  1. Identify variable types (continuous, categorical) and their distributions.
  2. Treat rubbish values in 'Material_Reference' by converting '00000' values into null.
  3. Treat reference columns as categorical variables.
### Data Preprocessing:
  1.Handle missing values using mean/median/mode.
  2.Treat outliers using IQR or Isolation Forest from the sklearn library.
  3.Identify skewness and treat it with appropriate transformations (e.g., log transformation, boxcox transformation).
  4.Encode categorical variables using suitable techniques (e.g., one-hot encoding, label encoding).
### EDA:
  1.Visualize outliers and skewness using Seaborn's boxplot, distplot, violinplot.
### Feature Engineering:
  1.Engineer new features if applicable.
  2.Drop highly correlated columns using Seaborn's heatmap.
### Model Building and Evaluation:
  1.Split the dataset into training and testing/validation sets.
  2.rain and evaluate different classification models (e.g., ExtraTreesClassifier, XGBClassifier, Logistic Regression) using appropriate evaluation metrics.
  3.ptimize model hyperparameters using techniques such as cross-validation and grid search.
  4.Interpret model results and assess performance based on the problem statement.
### Model GUI using Streamlit:
  1.Create an interactive page with task input (Regression or Classification).
  2.Provide an input field to enter each column value except 'Selling_Price' for regression model and 'Status' for classification model.
  3.Perform feature engineering, scaling, and transformation steps used for training ML model.
  4.Predict new data from Streamlit and display the output.
## Dependencies:
Python 3.x,Pandas, NumPy, Scikit-learn, Seaborn, Streamlit
