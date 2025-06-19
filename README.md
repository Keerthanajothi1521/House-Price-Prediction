# Predicting-House-Prices
Overview
This project focuses on predicting house prices using a multiple linear regression model. The model analyzes various factors such as the number of rooms, distance to key facilities, accessibility, crime rates, and other socio-economic indicators to estimate house prices accurately. The goal is to provide insights into the features that most influence housing prices and evaluate the model's predictive performance.

Key Features
Data Analysis: Explores the dataset to understand distributions, correlations, and potential multicollinearity among features.
Feature Importance: Identifies the most influential variables affecting house prices using regression coefficients.
Model Evaluation: Assesses the model's performance using metrics like R-squared and Mean Squared Error (MSE).
Visualizations: Includes heatmaps, histograms, and scatter plots to illustrate data trends and model predictions.
Dataset

The dataset (house_data.csv) contains the following features:
Rooms: Number of rooms in the house.
Age: Age of the property.
Distance: Distance to key facilities.
Accessibility: Accessibility index.
Tax: Property tax rate.
DisadvantagedPosition: Socio-economic disadvantage index.
Crime: Crime rate in the area.
NitricOxides: Nitric oxide concentration.
PupilTeacher: Pupil-teacher ratio in nearby schools.
Residential: Residential land proportion.
NonRetail: Non-retail business land proportion.
Price: Target variable (house price).

Methodology
Data Preprocessing:

Checked for missing values and standardized features using StandardScaler.

Split the data into training and testing sets (80% train, 20% test).

Model Training:
Used LinearRegression from sklearn to train the model.
Evaluated feature importance through regression coefficients.

Model Evaluation:
Calculated R-squared and MSE to measure predictive accuracy.
Generated visualizations (actual vs. predicted prices, residual plots) to validate assumptions.

Results
R-squared: 0.7489 (74.89% of the variance in house prices is explained by the model).
Mean Squared Error (MSE): 20.3916.
Most Influential Feature: DisadvantagedPosition (coefficient: -4.58).

Visualizations
Correlation Heatmap: Highlights relationships between features.
Feature Importance Bar Plot: Shows the impact of each feature on house prices.
Actual vs. Predicted Prices: Compares model predictions with actual values.
Residual Plot: Checks for randomness in prediction errors.
