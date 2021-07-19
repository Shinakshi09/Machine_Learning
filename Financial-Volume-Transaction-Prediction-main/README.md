# Financial-Volume-Transaction-Prediction

Project is aimed at predicting financial transaction volumes:

  1. Transactions is the Response Variable.
  2. Prediction either for Individual Payment Type or Total Transactions
  3. Data set has 5 variables and 60 records
  4. Project time line is 14 calendar days
  5. Application of multiple techniques to access best model

Dataset contains Time Series hence two approaches used:

  1. First approach is prediction of “Total Transaction” which is sum of an Individual Payment Type i.e. NEFT, RTGS, Debit / Credit Card
  2. Second approach is prediction of Individual Payment Type
  3. Null values have been replaced with mean of the rest of the data
  4. Heatmap Matrix shows high correlation between Debit Card,Credit Card Transaction and Total Transactions

Five models have been used for approach 1

  1. AR
  2. MA
  3. ARMA
  4. ARIMA
  5. SARIMA
  
Two models have been used for approach 2

  1. AR
  2. MA

• Mean Absolute Error have been considered as criteria to judge
best model

**Best Model**

Approach 1

  1. ARIMA model has the lowest MAE of 8545596.045 hence ARIMA
  model is chosen as the best model.

Approach 2
  1. Payment Type Best Model MAE
  2. NEFT AR 2147112.4291
  3. RTGS ARIMA 152995.14
  4. Debit Card AR 7046382.4136
  5. Credit Card ARIMA 3797136.5481



