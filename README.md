# BYTEUPRISE_ML_04

## California Housing Price Prediction
This repository contains a project for predicting housing prices in California using a linear regression model. The dataset used is the California Housing Dataset.

## Overview
The main objective of this project is to build a regression model that predicts the median house value in California districts based on various features like housing median age, total rooms, total bedrooms, population, households, median income, and proximity to the ocean.

## Dataset
The dataset used in this project is the California Housing Dataset, which includes the following features:

housing_median_age
total_rooms
total_bedrooms
population
households
median_income
ocean_proximity (categorical feature)
The target variable is median_house_value.

## Project Structure
The project is structured as follows:

data/: Contains the dataset (if applicable).
notebooks/: Contains Jupyter notebooks with the analysis and model development.
scripts/: Contains the Python scripts for preprocessing, model training, and evaluation.
README.md: Project documentation.

## Results
The performance of the linear regression model is as follows:

Mean Absolute Error (MAE): 457.78
Mean Squared Error (MSE): 376961.55
Root Mean Squared Error (RMSE): 613.97
R-squared score: 0.635
