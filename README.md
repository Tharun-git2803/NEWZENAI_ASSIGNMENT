
## Document: https://drive.google.com/drive/folders/1_Kyh4qa3CbftPlpwGu1JMwyQymk8xegq?usp=sharing 

### Overview

This project presents an end-to-end Machine Learning solution for forecasting weekly retail sales using the Walmart Store Sales dataset. The objective is to accurately predict future weekly sales by utilizing historical sales records along with external factors such as holidays, markdowns, fuel prices, CPI, unemployment, temperature, and store information.

The project follows a complete Machine Learning workflow including:

- Data Loading
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Development
- Hyperparameter Tuning
- Model Evaluation
- Model Comparison
- Feature Importance Analysis

---

## Project Objective

The goal of this project is to develop an accurate demand forecasting model that helps retail businesses:

- Improve inventory planning
- Reduce stock shortages
- Reduce overstocking
- Increase operational efficiency
- Support business decision making

---

## Dataset

The project uses the Walmart Store Sales Forecasting Dataset.

Files used:

- train.csv
- features.csv
- stores.csv
- test.csv

Target Variable:

- Weekly_Sales

---

## Technologies Used

Programming Language

- Python 3.11

Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib

Development Environment

- Jupyter Notebook

---

## Project Workflow

```
Load Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Missing Value Handling
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Model Training
      │
      ▼
Hyperparameter Tuning
      │
      ▼
Model Evaluation
      │
      ▼
Best Model Selection
      │
      ▼
Prediction
```

---

## Data Preprocessing

The following preprocessing steps were performed:

- Loaded all datasets
- Merged datasets
- Removed duplicates
- Filled missing values
- Converted Date column into datetime
- Created Year, Month and Week features
- Encoded categorical variables

---

## Exploratory Data Analysis

EDA includes:

- Sales Distribution
- Holiday Sales Analysis
- Correlation Heatmap
- Monthly Sales Trend
- Store-wise Sales
- Department-wise Sales

---

## Feature Engineering

Created features include:

- Year
- Month
- Week
- Holiday Indicator
- Store Type
- Lag Features
- Rolling Mean Features

---

## Models Implemented

1. Linear Regression
2. Random Forest Regressor
3. XGBoost Regressor

---

## Hyperparameter Tuning

GridSearchCV was used to optimize:

- n_estimators
- max_depth
- learning_rate
- min_samples_split
- min_samples_leaf

---

## Evaluation Metrics

Models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Best Model

After evaluating all models, the Random Forest Regressor provided the best overall performance with improved prediction accuracy and better generalization.

---



### Step 1

Clone the repository

```bash
git clone <repository_url>
```

### Step 2

Install dependencies

```bash
pip install -r requirements.txt
```

### Step 3

Run the notebook

```bash
jupyter notebook
```

Open

```
Retail_Demand_Forecasting.ipynb
```

Execute all cells.

---

## Results

The developed forecasting models successfully predict weekly retail sales with high accuracy.

The trained model can assist retailers in:

- Inventory Optimization
- Demand Planning
- Holiday Sales Forecasting
- Business Decision Making

---

## Future Improvements

- SHAP Explainability
- LSTM Forecasting
- Prophet Forecasting
- Model Deployment using FastAPI
- Streamlit Dashboard
- Real-time Forecasting API

---

## Author

Kiran Tharun

