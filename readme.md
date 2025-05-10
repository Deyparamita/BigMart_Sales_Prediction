#  Big Mart Sales Prediction

This project involves building a machine learning model to predict the sales of products at various Big Mart outlets using historical sales data. It applies data preprocessing, feature engineering, and model optimization techniques to improve accuracy.

##  Project Structure

- `Big_Mart_Sale_Prediction.ipynb`: Clean and organized notebook with final analysis and modeling.
- `Big_Mart_Sale_Prediction_Part2.ipynb`: Experimental notebook where various approaches were tested.
- `big_mart_data.csv`: Contains the csv dataset file.
- `README.md`: Project documentation.
- `requirements.txt`: List of required Python packages.

##  Dataset Overview

The dataset contains information such as:

- Item characteristics (weight, type, MRP)
- Outlet characteristics (location, type, establishment year)
- Sales data for each product-outlet combination

##  Preprocessing Steps

- Handled missing values using mean/mode imputation
- Encoded categorical variables using Label Encoding
- Feature engineered new columns (e.g., Outlet age)
- Removed or replaced zero values in `Item_Visibility`

##  Models Used

- **XGBoost Regressor**
  - Parameters tuned: `n_estimators`, `max_depth`, `learning_rate`, `subsample`, etc.
- Evaluated using **R² Score**

###  Best Model Performance

| Metric         | Train R² | Test R²  |
|----------------|----------|----------|
| XGBoostRegressor | ~0.62    | ~0.61  
