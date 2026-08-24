# NBA-Player-Performance-Prediction
NBA player season analysis and point per game prediction using Python, Panda and scikit-learn
# NBA Player Performance Prediction

## Overview

This project analyzes NBA player season statistics and builds machine learning models to predict a player's points per game using other statistics from the same season.

The dataset contains more than 12,000 player-season observations and includes variables such as usage percentage, true shooting percentage, assists, rebounds, games played, age, height, and weight.

# Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- scikit-learn

# Project Workflow

1. Load and inspect the NBA player dataset
2. Clean and transform the data
3. Engineer additional features
4. Perform exploratory data analysis
5. Analyze correlations with scoring
6. Train Linear Regression and Random Forest models
7. Compare model performance
8. Analyze feature importance

# Prediction Target

The models predict:

**Points per game for a player during the same season**

This is not a future-season forecasting model.

# Model Results

# Linear Regression

- RMSE: 1.959
- R²: 0.895

# Random Forest

- RMSE: 1.542
- R²: 0.935

# Key Finding

Usage percentage was the most important predictor of points per game, followed by variables such as rebounds and assists.

# Future Improvements

- Store the data in PostgreSQL
- Query and transform the dataset with SQL
- Build an automated Python ETL pipeline
- Add cloud storage and processing with AWS
- Explore true future-season forecasting
