# Projects
A collection of practical projects demonstrating data analysis, machine learning, and real-world problem solving. Each project includes clean, documented code with datasets and results to help build skills and portfolios efficiently. Ideal for learners and practitioners alike.
# Boston Housing Price Prediction

## Overview
This project involves analyzing the Boston Housing dataset and building regression models to predict median house prices (MEDV) based on various housing and environmental features. The project includes data exploration, cleaning, model training, evaluation, and saving the trained model.

## Dataset
The Boston Housing dataset contains 506 records with 14 features such as crime rate, average number of rooms, distance to employment centers, property tax rate, and others. The target variable is the median value of owner-occupied homes (MEDV).

## Project Steps

1. **Load and Explore the Dataset**  
   - Load data using Pandas and inspect key statistics and data types.  
   - Check for missing values and handle by dropping rows with missing data.

2. **Data Preparation**  
   - Define features (all columns except MEDV) and target variable (MEDV).  
   - Split the dataset into training and testing sets (80/20 split).

3. **Model Training**  
   - Train a Linear Regression model on the training data.  
   - Optionally, explore advanced models such as Random Forest Regressor.

4. **Model Evaluation**  
   - Evaluate models using RMSE and R² score metrics on the test set.

5. **Model Saving**  
   - Save the trained linear regression model to a file (`boston_house_price_model.pkl`) for future use.

## Results

- Linear Regression achieved:  
  - RMSE: ~4.55  
  - R² Score: ~0.72

- Random Forest Regressor achieved:  
  - R² Score: ~0.88

## Requirements

- Python 3.x  
- Libraries: pandas, scikit-learn, joblib

Install dependencies via:

