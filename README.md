# Ice Cream Sales Prediction using Linear Regression

## Project Overview

This project aims to predict ice cream sales based on different factors such as temperature, rainfall, day of the week, and month.

I developed a Machine Learning model using Linear Regression to understand the relationship between these features and ice cream sales.

## Dataset Information

- Dataset Name: Ice Cream Demand Dataset
- Total Records: 200
- Total Original Columns: 6
- Target Variable: `IceCreamsSold`

### Features Used

- `Temperature`
- `Rainfall`
- `DayOfWeek`
- `Month`

The target variable is `IceCreamsSold`, which the model predicts.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Joblib

## Project Workflow

1. Data Loading
2. Data Inspection
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Data Visualization
6. Feature Selection
7. Train-Test Split
8. Categorical Encoding using One-Hot Encoding
9. Model Training using Linear Regression
10. Model Prediction
11. Model Evaluation
12. Residual Analysis
13. Prediction using New Input Data
14. Model Saving using Joblib

## Model Used

**Linear Regression**

Linear Regression is a supervised Machine Learning algorithm used to predict continuous numerical values.

In this project, it is used to predict the number of ice creams sold based on the selected features.

## Model Evaluation

The model was evaluated using the following metrics:

| Evaluation Metric | Result |
|---|---:|
| MAE | 5.14 |
| MSE | 40.10 |
| RMSE | 6.33 |
| R² Score | 0.9862 (98.62%) |

The model achieved an R² score of approximately 98.62% on the test dataset.

## New Data Prediction

The trained model was tested using new input data.

**Input:**
- Temperature: 85.0
- Rainfall: 0.2
- DayOfWeek: Sunday
- Month: June

**Predicted Ice Cream Sales:** Approximately 195 ice creams.

## Project Files

- `ice_cream_prediction.ipynb` – Jupyter Notebook containing the complete project.
- `ice_cream_sales.csv` – Dataset used for the project.
- `preprocessor.pkl` – Saved preprocessing object.
- `linear_regression_model.pkl` – Saved trained Linear Regression model.

## Conclusion

In this project, I developed a Linear Regression model to predict ice cream sales using temperature, rainfall, day of the week, and month.

I learned the complete Machine Learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, residual analysis, and prediction using new input data.

**Note:** This is a synthetic educational dataset, and the model results should not be considered a guarantee of real-world sales performance.