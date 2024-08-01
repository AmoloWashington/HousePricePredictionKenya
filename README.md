# HousePricePredictionKenya
House Price Prediction Model
# Overview
This repository contains a machine learning model designed to predict house prices based on various features such as size, number of bedrooms, bathrooms, location, property type, and more. The goal is to create an accurate predictive model that can help users estimate the market value of a house given specific attributes.

# Features
Feature Selection: Important features are selected based on their importance in predicting house prices.
Data Scaling: The data is scaled to ensure that features contribute equally to the prediction.
Hyperparameter Tuning: GridSearchCV is used to find the optimal hyperparameters for the Random Forest Regressor, enhancing the model's performance.
Evaluation Metrics: The model is evaluated using R^2, Mean Absolute Error (MAE), and Mean Squared Error (MSE) to provide a comprehensive understanding of its accuracy and reliability.
Dataset
The dataset used for this project includes various features that influence house prices:

Size: The size of the house in square feet.
Bedrooms: The number of bedrooms in the house.
Bathrooms: The number of bathrooms in the house.
Location: Categorical data representing different locations.
Property Type: Categorical data representing the type of property (e.g., Apartment, House).
Purchase Type: Indicates whether the property is for rent or sale.
Source: The source of the data (e.g., BuyRentKenya, Propco).
Methodology
Data Preprocessing:

Handling missing values.
Encoding categorical variables.
Selecting the most important features using feature importances from an initial Random Forest model.
Data Splitting:

Splitting the dataset into training and testing sets to evaluate the model's performance on unseen data.
Data Scaling:

Scaling the features using StandardScaler to ensure they contribute equally to the prediction.
Model Training and Tuning:

Training the Random Forest Regressor with the selected features.
Tuning the hyperparameters using GridSearchCV to find the best model configuration.
Model Evaluation:

Evaluating the model's performance using R^2, MAE, and MSE.
