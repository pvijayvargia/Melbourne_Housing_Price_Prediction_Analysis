# Melbourne Housing Price Prediction Analysis

This repository contains an analysis of the Melbourne Housing Dataset, focusing on predicting house prices using linear regression models, regularization techniques and evaluating model performance.

## Contents

1. [Data Exploration and Visualization](#data-exploration-and-visualization)
2. [Linear Regression Model Development](#linear-regression-model-development)
3. [Model Evaluation](#model-evaluation)
4. [Regularization](#regularization)
5. [Out-of-sample Performance](#out-of-sample-performance)

## Data Exploration and Visualization

Explored the Melbourne Housing dataset and provided visualizations such as histograms, scatter plots, or box plots to understand the distribution of different features. Included interpretations of the plots.

## Linear Regression Model Development

Developed a Linear regression model to predict the price of houses in Melbourne. Preprocessed the data as necessary, explaining the steps taken in preparing the data and developing the model. Encoded values for prediction as required.

## Model Evaluation

Evaluated the linear regression model using appropriate metrics. Split the dataset into training and testing sets to perform this evaluation. Interpreted these metrics to assess the performance of the model, discussing whether it is good and why.

## Regularization

Determined if there is a need for Lasso regularization and explained the comparison between test and training results. Set up a Lasso regression model with specified parameters and fit it to the training data. Performed Lasso regression on both training and test data, analyzing and explaining how the results change from the previous answer.

## Out-of-sample Performance

Ignored all previously trained models and split the data into a new training and test set in an 80-20 ratio. Newly trained (fit) the linear regression model on the training data and the Lasso regression model on the training data. Estimated AIC, AICc, BIC, as well as 5-fold CV for both models using only the training data. Estimated the models' true out-of-sample performance by computing their deviance on the test data. Compared all (deviance) values and discussed which Information Criterion (IC) is most similar to the model's true out-of-sample performance and how 5-fold CV compares.

---

This document serves as a comprehensive analysis of predicting house prices in Melbourne using linear regression models, including data exploration, model development, evaluation, regularization, and out-of-sample performance assessment.
