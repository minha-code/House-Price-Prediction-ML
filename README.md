# House Price Prediction using Machine Learning

## Project Overview
This project focuses on predicting house prices using Machine Learning. The Ames Housing dataset is used to analyze housing features and build a regression model to estimate house prices.

## Dataset
- Dataset: Ames Housing Dataset
- Total Records: 1,460
- Original Features: 81
- Target Variable: `SalePrice`

## Technologies & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## Project Workflow

### 1. Data Cleaning
- Checked missing values and duplicate records.
- Handled missing numerical and categorical values.
- Removed unnecessary `Id` column.
- Verified that no missing values remained.

### 2. Exploratory Data Analysis (EDA)
- Analyzed SalePrice distribution.
- Explored relationships between house features and prices.
- Used histograms, boxplots, scatterplots and correlation analysis.
- Identified right-skewness in the target variable.

### 3. Feature Engineering & Encoding
- Applied ordinal encoding to ordered categorical features.
- Applied one-hot encoding to nominal categorical features.
- Prepared numerical features for model training.

### 4. Model Building
- Linear Regression
- Log-Transformed Linear Regression

### 5. Model Evaluation
Evaluated models using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Model Performance

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 20,663.24 | 31,828.42 | 0.8679 |
| Log Linear Regression | 15,820.70 | 23,690.29 | 0.9268 |

## Best Model
Log-Transformed Linear Regression achieved better performance, with an R² score of approximately 0.927 on the test set.

## Key Learnings
- Data cleaning and preprocessing
- Exploratory Data Analysis
- Categorical feature encoding
- Regression modeling
- Log transformation
- Model evaluation and residual analysis

## Project Status
Initial model development completed. Further improvements, including a leakage-safe preprocessing pipeline and additional model comparisons, are planned.