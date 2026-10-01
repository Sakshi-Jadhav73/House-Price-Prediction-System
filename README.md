# 🏠 House Price Prediction System

A machine learning project that predicts house prices using the **California Housing dataset**. This project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model comparison, cross-validation, and hyperparameter tuning.

---

## 📌 Project Overview

The goal of this project is to build a machine learning model that predicts house prices based on different housing and demographic features.

### 🔄 Workflow

```text
📂 Data Collection
       ↓
🧹 Data Preprocessing
       ↓
📊 Exploratory Data Analysis
       ↓
⚙️ Feature Engineering
       ↓
🔗 ML Pipeline
       ↓
🤖 Model Training
       ↓
🔄 K-Fold Cross-Validation
       ↓
📈 Model Comparison
       ↓
🎯 Hyperparameter Tuning
       ↓
🏆 Final Prediction
```

---

## 📊 Dataset

The project uses the **California Housing dataset** containing **20,000+ housing records**.

### 🎯 Target Variable

* `median_house_value`

### 📋 Features

* `longitude`
* `latitude`
* `housing_median_age`
* `total_rooms`
* `total_bedrooms`
* `population`
* `households`
* `median_income`
* `ocean_proximity`

---

## 🛠️ Technologies Used

| Technology          | Purpose              |
| ------------------- | -------------------- |
| 🐍 Python           | Programming          |
| 🐼 Pandas           | Data Analysis        |
| 🔢 NumPy            | Numerical Operations |
| 📊 Matplotlib       | Data Visualization   |
| 📈 Seaborn          | Data Visualization   |
| 🤖 Scikit-learn     | Machine Learning     |
| 📓 Jupyter Notebook | Development          |

---

## 🔍 Project Steps

### 1️⃣ Data Preprocessing

The dataset was prepared for machine learning using:

* 🧹 Missing value handling with `SimpleImputer`
* 📏 Feature scaling with `StandardScaler`
* 🔤 Categorical encoding with `OneHotEncoder`
* 🔀 Feature transformation using `ColumnTransformer`

---

### 2️⃣ Exploratory Data Analysis

EDA was performed to understand the dataset and identify important patterns.

The analysis included:

* 📊 Statistical analysis
* 📈 Feature distributions
* 🔗 Correlation analysis
* 📉 Data visualization
* 🏠 Relationship between features and house prices

---

### 3️⃣ ⚙️ Feature Engineering

Relevant features were prepared and transformed to improve the machine learning workflow.

---

### 4️⃣ 🔗 ML Pipeline

A Scikit-learn pipeline was created to combine preprocessing and model training.

```text
📥 Input Data
     ↓
🧹 Missing Value Handling
     ↓
📏 Feature Scaling
     ↓
🔤 Categorical Encoding
     ↓
🤖 Machine Learning Model
     ↓
🎯 Prediction
```

The pipeline keeps preprocessing consistent during model training and prediction.

---

### 5️⃣ 🤖 Machine Learning Models

Five regression models were compared:

* 📌 Linear Regression
* 📌 Ridge Regression
* 📌 Lasso Regression
* 🌳 Random Forest Regressor
* 🚀 Gradient Boosting Regressor

---

### 6️⃣ 🔄 K-Fold Cross-Validation

K-Fold cross-validation was used to compare model performance.

The models were evaluated using:

* 📉 RMSE
* 📉 MAE
* 📈 R² Score

The models were compared based on their cross-validation results.

---

### 7️⃣ 🎯 Hyperparameter Tuning

`GridSearchCV` was used for hyperparameter tuning.

It tests different combinations of model parameters and identifies a suitable combination based on cross-validation performance.

---

### 8️⃣ 🏆 Final Model

After model comparison and hyperparameter tuning, the selected model was trained and evaluated on the test dataset.

The final model can be used to predict house prices for new housing data.

---

## 📏 Evaluation Metrics

### 📉 RMSE — Root Mean Squared Error

Measures the difference between actual and predicted house prices.

**Lower RMSE = Better performance**

### 📉 MAE — Mean Absolute Error

Measures the average absolute prediction error.

**Lower MAE = Better performance**

### 📈 R² Score

Measures how well the model explains the variation in house prices.

**Higher R² = Better performance**

---
## 📁 Project Directory

```text
House-Price-Prediction-System/
│
├── 📓 15_4_house_price_prediction.ipynb
├── 📄 housing.csv
└── 📄 README.md

## 🎓 Key Learning Outcomes

Through this project, I learned how to:

* 🧹 Perform data cleaning and preprocessing
* 📊 Perform Exploratory Data Analysis
* 🔤 Handle numerical and categorical features
* 🔗 Build ML pipelines using Scikit-learn
* 🤖 Compare multiple regression models
* 🔄 Apply K-Fold cross-validation
* 📏 Evaluate models using RMSE, MAE, and R²
* 🎯 Perform hyperparameter tuning using GridSearchCV
* 🏠 Build an end-to-end house price prediction system

---

## 🔮 Future Improvements

* 🌐 Deploy the model using Flask or FastAPI
* 🖥️ Create a web interface for house price prediction
* ⚙️ Improve feature engineering
* 🤖 Experiment with additional ML models
* 📊 Add model monitoring and deployment

---

## 👩‍💻 Author

**Sakshi Jadhav**

🔗 GitHub: **Sakshi-Jadhav73**
