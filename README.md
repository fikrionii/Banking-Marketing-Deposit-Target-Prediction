# Banking-Marketing-Deposit-Target-Prediction
* Build model to predict whether a customer will subscribe to term deposit or not.
* This dataset is obtained from [Banking Dataset - Marketing Targets | Kaggle](https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets)
* Handling outliers using Z-score
* Handling imbalance class using SMOTE
* Train model using 9 algorithm, and choose the top alogrithm performance for next hyperparameter tuning

## Problem
* Currently, telemarketing team is targeting customer to give term deposito campaign by *random*.
* This random selection method inefficient and will cause *high marketing cost in the long run*.

## Purpose
Reduce the flow of processing & analysis to filter which customer is more likely to subscribe to term deposit and gives *accurate target to telemarketing team*

## Insight from Data
1. Distribution of subscribed customer is not balanced.
![alt text](https://github.com/fikrionii/Banking-Marketing-Deposit-Target-Prediction/blob/main/fig/Target%20ratio.png "Target Ratio")
2. Customer with higher duration during call is more likely to subscribe to term deposito.
![alt text](https://github.com/fikrionii/Banking-Marketing-Deposit-Target-Prediction/blob/main/fig/Effect%20of%20duration%20on%20target.png "Effect of duration on target")
3. Customer without housing loan is more likely to subscribe to term deposito.
![alt text](https://github.com/fikrionii/Banking-Marketing-Deposit-Target-Prediction/blob/main/fig/Effect%20of%20housing%20on%20target.png "Effect of housing on target")
4. Customer with succesful result on previous campaign is more likely to subscribe to term deposito.
![alt text](https://github.com/fikrionii/Banking-Marketing-Deposit-Target-Prediction/blob/main/fig/Effect%20of%20poutcome%20on%20target.png "Effect of previous campaign outcome on target")

## ML Modeling
