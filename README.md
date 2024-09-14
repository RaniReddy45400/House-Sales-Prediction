# House-Sales-Prediction
House Sales Price Prediction
This project focuses on predicting house sales prices using machine learning techniques. The primary objective is to analyze housing data and develop a predictive model that can estimate the price of houses based on various features.

Project Overview

Objective: Predict house sales prices using historical data and machine learning techniques.

Techniques Used:
Data preprocessing
Principal Component Analysis (PCA)
Feature scaling
Predictive modeling with Gradient Boosting Regressor

Dependencies
Ensure you have the following libraries installed:
pandas
numpy
matplotlib
seaborn
scikit-learn
You can install the necessary packages using the following command:

bash

pip install -r requirements.txt

Project Structure

Data Preprocessing:

Data cleaning and feature engineering to handle missing values, categorical data, and outliers.
Dimensionality Reduction:

Principal Component Analysis (PCA) was applied to reduce the dimensionality of the dataset while preserving variance.
Modeling:

Gradient Boosting Regressor was used as the primary machine learning algorithm to predict house prices.

Running the Project
1.Clone this repository to your local machine.
2.Install the required dependencies listed above.
3.Open the Jupyter notebook (housesales_Basic_Task 2.ipynb) and run the cells to see the analysis and prediction results.

Results
The model's performance is evaluated using common regression metrics like Mean Squared Error (MSE) and R-squared.
The dimensionality reduction via PCA helped optimize the model’s performance by reducing multicollinearity.

Future Work
1.Incorporating additional advanced algorithms like XGBoost.
2.Hyperparameter tuning to further improve model accuracy.
3.Experimenting with different feature selection methods.
