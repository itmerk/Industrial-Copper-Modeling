Project Title: Predictive Modeling for the Copper Industry

Overview:
This project focuses on developing predictive models for the copper industry to address challenges related to sales prediction and lead classification. The dataset contains various variables including continuous and categorical features. The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and creating a user-friendly web application using Streamlit for model prediction.

Steps:

Data Understanding:

Identify variable types (continuous, categorical) and their distributions.
Treat rubbish values in 'Material_Reference' by converting '00000' values into null.
Treat reference columns as categorical variables.
Data Preprocessing:

Handle missing values using mean/median/mode.
Treat outliers using IQR or Isolation Forest from the sklearn library.
Identify skewness and treat it with appropriate transformations (e.g., log transformation, boxcox transformation).
Encode categorical variables using suitable techniques (e.g., one-hot encoding, label encoding).
EDA:

Visualize outliers and skewness using Seaborn's boxplot, distplot, violinplot.
Feature Engineering:

Engineer new features if applicable.
Drop highly correlated columns using Seaborn's heatmap.
Model Building and Evaluation:

Split the dataset into training and testing/validation sets.
Train and evaluate different classification models (e.g., ExtraTreesClassifier, XGBClassifier, Logistic Regression) using appropriate evaluation metrics.
Optimize model hyperparameters using techniques such as cross-validation and grid search.
Interpret model results and assess performance based on the problem statement.
Model GUI using Streamlit:

Create an interactive page with task input (Regression or Classification).
Provide an input field to enter each column value except 'Selling_Price' for regression model and 'Status' for classification model.
Perform feature engineering, scaling, and transformation steps used for training ML model.
Predict new data from Streamlit and display the output.
Dependencies:

Python 3.x
Pandas
NumPy
Scikit-learn
Seaborn
Streamlit
