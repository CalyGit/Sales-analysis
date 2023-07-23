
# Forecasting Store Sales: Time Series Analysis and Predictive Modeling for Favorita Corporation

Corporation Favorita, a prominent Ecuadorian-based grocery retailer, faces the ongoing challenge of accurately predicting store sales for its vast array of products. With thousands of items sold across different Favorita stores, the need for precise unit sales forecasting has become paramount.


## Table of Contents

- [Project Overview](#project-overview)
- [File Descriptions](#file-descriptions)
- [Data Field Information](#data-field-information)
- [Data Preparation](#data-preparation)
- [Hypothesis & Questions](#hypothesis--questions)
- [What do you need?](What-do-you-need?)

## Project Overview

In this project, we embark on a journey to develop a robust model that leverages the power of time series analysis to more accurately predict store sales. By harnessing historical sales data, along with additional information on promotions, store metadata, oil prices, and holiday events, our aim is to uncover hidden patterns and relationships that contribute to sales dynamics.

## Datasets
![Static Badge](https://img.shields.io/badge/Download)

## File Descriptions

- `train.csv`: The training data, comprising time series of features store_nbr, family, onpromotion, and target sales.
- `test.csv`: The test data, having the same features as the training data, used for predicting target sales for future dates.
- `transaction.csv`: Contains date, store_nbr, and transaction information made on specific dates.
- `sample_submission.csv`: A sample submission file in the correct format for predictions.
- `stores.csv`: Store metadata, including city, state, type, and cluster information.
- `oil.csv`: Daily oil price data which includes values during both the train and test data timeframes.
- `holidays_events.csv`: Holidays and Events data, including metadata. Pay special attention to the "transferred" column to handle transferred holidays correctly.

## Data Field Information

The data fields in the training and test datasets are as follows:

- `store_nbr`: Identifies the store at which the products are sold.
- `family`: Identifies the type of product sold.
- `sales`: Gives the total sales for a product family at a particular store on a given date (fractional values possible).
- `onpromotion`: Indicates the total number of items in a product family that were being promoted at a store on a given date.

## Data Preparation

Before building the forecasting model, it is essential to perform data preparation tasks such as data cleaning, handling missing values, and preprocessing the features. Ensure that the dataset is appropriately formatted and ready for analysis.

## Hypothesis & Questions

The following questions need to be addressed during the analysis:

1. Is the train dataset complete (has all the required dates)?
2. Which dates have the lowest and highest sales for each year?
3. Did the earthquake impact sales?
4. Are certain groups of stores selling more products? (Cluster, city, state, type)
5. Are sales affected by promotions, oil prices, and holidays?
6. What analysis can we get from the date and its extractable features?
7. What is the difference between RMSLE, RMSE, MSE (or why is the MAE greater than all of them?)

## What do you need?
What do you need? Nothing!😉Just download `requirements.txt` and __RUN!!__ 🎉.


![Twitter Follow](https://img.shields.io/twitter/follow/the1_caly)
