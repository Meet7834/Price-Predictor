# Tomato Price and Demand Prediction

This project focuses on predicting tomato prices and demand using machine learning techniques. It analyzes historical data on tomato prices, seasonal variations, and other relevant factors to make predictions.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Models](#models)
- [Results](#results)
- [Visualization](#visualization)

## Introduction

The Tomato Price and Demand Prediction project uses machine learning algorithms to predict two key aspects of tomato sales: price and demand. By analyzing historical data and various features such as date, season, and month, the project aims to provide insights into tomato market trends.

## Data

The project uses a dataset that includes the following columns:

- `prod_id`: Product ID
- `avg price`: Average price of tomatoes
- `prod_name`: Product name
- `order date`: Date of the order
- `pack sold`: Quantity sold in packs
- `order`: Order number
- `Season`: Season of the year (encoded as 1 for winter, 2 for summer, and 3 for monsoon)
- `Month`: Month of the year (encoded numerically)

The data is preprocessed to prepare it for machine learning modeling, including encoding the "Season" and "Month" columns.

## Models

The project employs several machine learning models for prediction, including:

- Linear Regression
- Ridge Regression
- Lasso Regression
- K-Nearest Neighbors
- Neural Network (MLPRegressor)
- Support Vector Machine (Linear Kernel)
- Support Vector Machine (RBF Kernel)
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost
- LightGBM
- CatBoost

The models are trained and evaluated for their performance in predicting tomato prices and demand. Various metrics, including R^2 score and mean squared error, are used to assess model performance.

## Results

The project evaluates and compares the performance of the machine learning models. It includes training and testing data predictions, as well as an analysis of the R^2 scores and mean squared errors for each model.

## Visualization

The project provides visualizations to help understand the relationships between actual and predicted tomato prices and demand. Scatter plots are used to visualize the accuracy of predictions.
