# House Price Prediction System

A machine learning project that predicts house prices using the California Housing dataset. This project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model comparison, cross-validation, and hyperparameter tuning.

## Project Overview

The goal of this project is to build a machine learning model that can predict house prices based on different housing and demographic features.

### Workflow

```text
Data Collection
      ↓
Data Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering
      ↓
ML Pipeline
      ↓
Model Training
      ↓
K-Fold Cross-Validation
      ↓
Model Comparison
      ↓
Hyperparameter Tuning
      ↓
Final Prediction
```

## Dataset

The project uses the **California Housing dataset** containing **20,000+ housing records**.

### Target Variable

* `median_house_value`

### Features

* `longitude`
* `latitude`
* `housing_median_age`
* `total_rooms`
* `total_bedrooms`
* `population`
* `households`
* `median_income`
* `ocean_proximity`

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Steps

### 1. Data Preprocessing

The dataset was checked and prepared for machine learning.

The following techniques were used:

* Handling missing values using `SimpleImputer`
* Scaling numerical features using `StandardScaler`
* Encoding categorical features using `OneHotEncoder`
* Separating numerical and categorical features using `ColumnTransformer`

### 2. Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the dataset and identify patterns.

The analysis included:

* Statistical analysis
* Feature distributions
* Correlation analysis
* Data visualization
* Relationship between features and house prices

### 3. Feature Engineering

Relevant features were prepared and transformed to improve the machine learning workflow.

### 4. ML Pipeline

A Scikit-learn pipeline was created to combine preprocessing and model training.

```text
Input Data
    ↓
Missing Value Handling
    ↓
Feature Scaling
    ↓
Categorical Encoding
    ↓
Machine Learning Model
    ↓
Prediction
```

Using a pipeline keeps the preprocessing steps consistent during training and prediction.

### 5. Machine Learning Models

Five regression models were compared:

* Linear Regression
* Ridge Regression
* Lasso Regression
* Random Forest Regressor
* Gradient Boosting Regressor

### 6. K-Fold Cross-Validation

K-Fold cross-validation was used to compare the performance of different regression models.

The models were evaluated using:

* RMSE
* MAE
* R² Score

The model with the lower RMSE and better overall cross-validation performance was selected for further tuning.

### 7. Hyperparameter Tuning

`GridSearchCV` was used for hyperparameter tuning.

It tests different combinations of model parameters and identifies a suitable combination based on cross-validation performance.

### 8. Final Model

After model comparison and hyperparameter tuning, the selected model was trained and evaluated on the test dataset.

The final model can be used to predict house prices for new housing data.

## Evaluation Metrics

### RMSE

Root Mean Squared Error measures the difference between actual and predicted house prices.

**Lower RMSE indicates better performance.**

### MAE

Mean Absolute Error measures the average absolute prediction error.

**Lower MAE indicates better performance.**

### R² Score

R² Score measures how well the model explains the variation in the target variable.

**Higher R² generally indicates better performance.**

## Project Directory

```text
House-Price-Prediction/
│
├── Dataset/
│   └── housing.csv
│
├── Notebook/
│   └── house_price_prediction.ipynb
│
├── README.md
│
└── requirements.txt
```

## Installation

### 1. Clone the repository

```bash
git clone YOUR-GITHUB-LINK
```

### 2. Navigate to the project directory

```bash
cd House-Price-Prediction
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Run Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook from the `Notebook` folder and run the cells step by step.

## Requirements

Create a `requirements.txt` file with:

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

Then install all dependencies using:

```bash
pip install -r requirements.txt
```

## Key Learning Outcomes

Through this project, I learned how to:

* Perform data cleaning and preprocessing
* Perform Exploratory Data Analysis
* Handle numerical and categorical features
* Build an ML pipeline using Scikit-learn
* Compare multiple regression models
* Apply K-Fold cross-validation
* Evaluate models using RMSE, MAE, and R²
* Perform hyperparameter tuning using GridSearchCV
* Build an end-to-end house price prediction system

## Future Improvements

* Deploy the model using Flask or FastAPI
* Create a web interface for house price prediction
* Improve feature engineering
* Experiment with additional machine learning models
* Add model monitoring and deployment

## Author

**Sakshi Jadhav**

GitHub: `Sakshi-Jadhav73`
