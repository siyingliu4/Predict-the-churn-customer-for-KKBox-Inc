## Predict the Churn Customer for KKBox Inc.
This readme file is written by one of the team members Gongna.

## Background
KKBOX is Asia’s leading music streaming service, holding the world’s most comprehensive Asia-Pop music library with over 30 million tracks. They offer a generous, unlimited version of their service to millions of people, supported by advertising and paid subscriptions. This delicate model is dependent on accurately predicting churn of their paid users.

## Task Description
build an algorithm that predicts whether a user will churn after their subscription expires. Currently, the company uses survival analysis techniques to determine the residual membership life time for each subscriber. By adopting different methods, KKBOX anticipates they’ll discover new insights to why users leave so they can be proactive in keeping users dancing.

## Dataset
Provided by KKBox company
https://www.kaggle.com/c/kkbox-churn-prediction-challenge/data

## Solution
**Step 1**: Data exploration and preprocessing
- cut data size
- handle large amount of missing value
- handle outlier
- decide prediction target
- standardization or normalization

**Step 2**: Feature Engineering
- create new features based on historical listening logs
- feature selection

**Step 3**: Classical Prediction Model
- KNN, LogRegression, DT, ANN, NB, Nearst_Centroid, SVM
- Parameter tunning via GridSearch

## Result
![result](https://github.com/Gooongna/Predict-the-Churn-Customer-for-KKBox-Inc.-/blob/master/result_1.PNG)

## Usage
This repos is used to store the code without the raw dataset. To show the final proccessed data, there are two sample dataset are provided.
So the code is runnable with sample dataset but cannot get the shown result. All intermediate results maintained inside the jupyter notebook are trained from fully dataset.

## Learnings
Besides the task of churn prediction, this project also aims to explore as many as possible the classicial ML model to handle binary classification problem and the standard ML lifecycle 

