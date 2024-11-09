# DWR Project - Big Mart Sales Prediction

Overview :
This repository contains my solution to the BigMart Sales Prediction hackathon. The project aims to predict the sales of individual products at various BigMart outlets, based on the 2013 sales data provided. Using data science and machine learning techniques, this model identifies key product and outlet attributes that impact sales, providing BigMart with insights to drive strategic decisions.

Problem Statement :
The objective of this challenge is to develop a predictive model using historical data. BigMart data scientists have provided sales data for 1559 products across 10 stores, including attributes related to both the stores and products. By analyzing this data, the goal is to predict the sales for each product-outlet combination, even in cases where data might be missing due to technical issues.

Dataset Information :
The dataset contains sales information and related attributes for products and stores, including:
Products: 1559 unique items, with attributes like product type, weight, and visibility.
Stores: 10 stores in various cities, with unique features including location type, store size, and type.
Challenges in the Dataset
The dataset includes missing values, which may arise from technical glitches in data reporting from some stores. These missing values require appropriate handling for accurate model predictions.

Solution Approach :
Data Preprocessing: Handled missing values and performed necessary data cleaning.
Feature Engineering: Created additional features to enhance model performance.
Modeling: Implemented several machine learning models and fine-tuned them to improve accuracy.
Evaluation: Assessed model performance using metrics like RMSE to ensure robust predictions.

Results :
The final model demonstrates effective prediction capabilities, providing BigMart with insights into the product and store attributes that influence sales. The submission file, submission.csv, includes predictions for each product-outlet combination.
