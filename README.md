# Airbnb Price Prediction in NYC
## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model](#model)
- [Evaluation](#evaluation)
- [Results](#results)

## Introduction
This project aims to predict the rental price of Airbnb listings in New York City using machine learning techniques. Accurate price predictions can help hosts set competitive prices and assist potential renters in identifying good deals.

## Dataset
The dataset used for this project is sourced from [Course Webiste](https://www.dropbox.com/scl/fo/vhf0wa7555c0058017529/h?rlkey=mcpb2kbng1iom10c246vcye9v&e=1&dl=0). It contains various features about the listings, including:
- `id`: Listing ID
- `name`: Listing name
- `summary`: Summary of the listing
- `space`: Space details
- `description`: Description of the listing
- `neighborhood_overview`: Overview of the neighborhood
- `notes`: Additional notes
- `transit`: Transit information
- `access`: Access information
- `interaction`: Host interaction details
- etc
  
## Model
The model used for prediction is based on machine learning algorithms such as CatBoost, GradientBoost, lgb, or XGBoost. Feature engineering and hyperparameter tuning were performed to optimize the model performance.

## Evaluation
The model is evaluated using metrics Root Mean Squared Error (RMSE).

## Results
The final model achieves a Root Mean Squared Error (RMSE) of 81.12619 on the test set. The performance metrics indicate that the model is effective in predicting Airbnb listing prices within a reasonable error margin.
