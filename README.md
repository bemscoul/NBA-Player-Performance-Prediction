# NBA Player Performance Prediction

NBA player-season analysis and points-per-game prediction using Python, Pandas, and scikit-learn.

## Overview

This project analyzes NBA player-season statistics and builds machine learning models to predict a player's points per game (PPG) using performance statistics from the same season.

The project includes data cleaning, feature engineering, exploratory data analysis, correlation analysis, predictive modeling, model evaluation, and feature importance analysis.

## Dataset

This project uses the NBA Players Dataset from Kaggle.

Dataset Source: https://www.kaggle.com/datasets/justinas/nba-players-data

The dataset contains more than 12,000 player-season observations and includes variables such as usage percentage, true shooting percentage, assists, rebounds, games played, age, height, and weight.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- scikit-learn

## Project Workflow

1. Load and inspect the NBA player dataset
2. Clean and transform the data
3. Engineer additional features
4. Perform exploratory data analysis
5. Analyze correlations with scoring
6. Train Linear Regression and Random Forest models
7. Evaluate and compare model performance
8. Analyze feature importance

## Prediction Target

The models predict a player's **points per game (PPG)** using other player statistics from the same season.

This is a same-season prediction task, not a future-season forecasting model.

## Model Results

### Linear Regression

- RMSE: 1.959
- R²: 0.895

### Random Forest

- RMSE: 1.542
- R²: 0.935

The Random Forest model achieved the stronger predictive performance of the two models.

## Key Finding

Usage percentage was the most important predictor of points per game in the Random Forest model, followed by variables including rebounds and assists.

## Future Improvements

- Store the dataset in PostgreSQL
- Query and transform the data using SQL
- Build an automated Python ETL pipeline
- Add cloud storage and processing with AWS
- Explore true future-season forecasting
