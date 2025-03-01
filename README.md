# Ice Cream Price Prediction Model

## Project Overview:
This project aims to predict the price of ice cream based on various factors like type, ingredients, size, and location. The goal is to build a machine learning model that can predict the price of an ice cream based on historical data.

## Key Steps Followed in the Project:

### 1. Data Loading and Exploration:
- The dataset was loaded and explored using methods like `df.info()` and `df.describe()` to understand the data types and basic statistics.
- Visualized the dataset to identify patterns and relationships between the features and the target variable.

### 2. Data Preprocessing and Feature Engineering:
- Handled missing values, outliers, and duplicates in the dataset.
- Converted categorical variables into numerical values using encoding techniques like One-Hot Encoding or Label Encoding.
- Scaled numerical features using techniques like Min-Max scaling or Standardization to ensure equal importance during model training.

### 3. Model Building:
- Used multiple regression models (e.g., Linear Regression, Random Forest Regressor, and XGBoost) to predict the price of ice cream.
- Trained the models on the training dataset and tested them on the test dataset.

### 4. Model Evaluation:
- Evaluated the models using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), R-squared (R²), and Root Mean Squared Error (RMSE) to assess their performance.
- Compared the performance of different models to identify the best one for the task.

### 5. Hyperparameter Tuning:
- Applied hyperparameter tuning techniques like GridSearchCV and RandomizedSearchCV to find the best hyperparameters for models.
- Retrained the models with optimized hyperparameters for improved accuracy.

## Metrics:

- **Initial Model Accuracy (Linear Regression):** 72.45%
- **After Hyperparameter Tuning (Random Forest):** 85.20%
- **Best Model (XGBoost):** Accuracy: 88.75%, MAE: 0.12, MSE: 0.05, R²: 0.92
- **Best Model After Hyperparameter Tuning (XGBoost):** Slight improvement in MAE and MSE with an increase in R² to 0.93.

