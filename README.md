# Prediction of Cruide Oil prices using Machine Learning Techniques 

## Objective 

This project focuses on predicting crude oil prices using machine learning techniques. By analyzing a comprehensive dataset comprising parameters such as total crude oil supply, demand, USD and Ruble exchange rates, and gas prices, the objective is to develop accurate predictive models. Leveraging advanced regression algorithms including Random Forest, Support Vector Regression, Lasso, and Ridge, the project aims to forecast spot crude oil prices with precision. Through rigorous analysis and optimization of model performance, this project seeks to contribute valuable insights into crude oil market dynamics, enabling informed decision-making in the energy sector.

## Variables Used 

Variable Name   | Units                  | Explanation
----------------|------------------------|-------------------------
FWTI            | Dollars per barrel     | WTI Crude oil spot price
SWTI            | Dollars per barrel     | WTI Crude oil spot price
PRO             | Thousand barrels/day   | Total crude oil supply
COM             | Thousand barrels/day   | Total crude oil demand
GAS             | Dollars per million BTU| Gas price
RDL             | Unitless               | Dollar exchange rate
RUB             | Unitless               | Ruble exchange rate
GOLD            | Dollars per ounce      | Price of gold
SIL             | Dollars per ounce      | Price of silver

## Model Performance Summary

| Model Name    | R2       | MAPE   | MSE    | RMSE  |
|---------------|----------|--------|--------|-------|
| RandomForest  | 0.99665  | 2.396  | 2.91   | 1.71  |
| SVR - rbf     | 0.9865   | 3.498  | 11.75  | 3.42  |
| Lasso         | 0.87     | 18.40  | 113.85 | 10.67 |
| Ridge         | 0.8691   | 18.36  | 113.7  | 10.66 |

## Data Overview 

