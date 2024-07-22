# Project Description:

This project aims to predict the number of goals scored by home and away teams in Euro 2024 football matches using machine learning models. The project involves data preprocessing, model training, and evaluation steps. The goal is to provide accurate predictions based on match-related features such as expected goals, total shots, shots on target, big chances, and attendance.

Dataset: Euro_2024_Matches.csv([find on Kaggle](https://www.kaggle.com/datasets/thamersekhri/euro-2024-matches))

# Project Workflow:

1. Data Preprocessing
Convert attendance column to numeric by removing commas.
Select relevant features for modeling.
Split data into training and test sets.

2. Model Training
Train separate linear regression models to predict home and away team goals.

3. Model Evaluation
Evaluate the models using metrics such as Mean Squared Error (MSE) and R-squared (R2).

4. Visualization
Visualize the correlation of features with goals using heatmaps.
Plot the distribution of features.
Compare actual vs. predicted goals with line plots.
Analyze residuals with scatter plots.

# Visualization
Correlation Heatmaps: Show the relationship between features and target variables (home and away goals).
Feature Distributions: Histograms to display the distribution of each feature.
Actual vs. Predicted Goals: Line plots to compare the actual and predicted number of goals.
Residual Plots: Scatter plots to analyze the errors in predictions.

# Results
The models' performance metrics are displayed, including MSE and R2 scores.
Visualizations provide insights into the models' accuracy and feature importance.
Future Improvements
Incorporate more features to improve prediction accuracy.
Experiment with different machine learning algorithms.
Perform hyperparameter optimization.

# Conclusion
This project demonstrates how to create a machine learning model to predict the number of goals scored by home and away teams in football matches. The model provides reasonable predictions and can be further enhanced with additional data and advanced techniques.
