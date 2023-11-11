# Data Story: Predicting Absenteeism from Work

## Introduction

Workplace absenteeism is a significant concern for organizations, affecting productivity and overall efficiency. In this project, we aim to explore whether specific known reasons for absence can predict excessive absenteeism from work. The analysis involves preprocessing data, exploring key features, and building a predictive model using logistic regression.

## Data Exploration

We start by loading the raw data from 'Absenteeism_data.csv' and inspecting the initial records.

The dataset includes various features such as transportation expense, distance to work, age, and the reason for absence. We focus on known reasons for absence, excluding cases with an unknown reason.

## Feature Engineering

To enhance our model, we encode the reasons for absence into binary columns, creating 'Reason_1', 'Reason_2', 'Reason_3', and 'Reason_4'. We also extract the month and weekday from the date column. Educational levels are mapped, and the dataset is preprocessed.

## Target Definition

We create a target variable, 'Excessive Absenteeism,' by classifying individuals with absenteeism time greater than the median as 1, and others as 0.

## Model Building

We scale the inputs using a custom scaler and split the dataset into training and testing sets. A logistic regression model is then trained on the data.

## Model Evaluation

We evaluate the model's performance on the test set and analyze the coefficients to understand the impact of each feature.

## Predictions

We create an Absenteeism Model class for easy loading, cleaning, and making predictions. The model is applied to new data from 'Absenteeism_new_data.csv,' and the predictions are saved.

## Conclusion

This project provides insights into absenteeism prediction using logistic regression. The model can be a valuable tool for organizations to identify potential excessive absenteeism and take proactive measures.

By leveraging known reasons for absence, the model contributes to a more informed and data-driven approach to workforce management. Further refinements and extensions of the model can enhance its predictive power, supporting better decision-making in the workplace
