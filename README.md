# Fraud detection in bank transactions
by Giacomo Benvenuti

![Summary_fig](./figures/Cartoon_fraud.png)

---


[OPEN THE NOTEBOOK BY CLICKING HERE](https://github.com/GiacomoBenvenuti/Banking_Fraud_Detection/blob/9b534679b42236a5caa908f85fc6f7e764dbab04/Fraud_detection_Main.ipynb)


---

## Motivation
The customer is an issuing bank seeking a machine learning solution to solve a growing fraud problem.

The bank’s customers are having their cards defrauded and their money is being spent by fraudsters. This is causing customer dissatisfaction, so the bank is looking into introducing better transactional monitoring on activity on their customers’ cards. 

They plan to have a small team of fraud analysts who review risky-looking purchases and decide whether to allow or block the transaction. This team will have the capacity to review 400 transactions a month. The scores from my model will be used to decide which transactions the fraud analysts should review. 

**The bank has provided 1 year of historical transactional data and fraud flags and asked me to build a model which predicts the likelihood that a transaction is later marked as fraud**. 

---

## Approach

1) Data importation and formatting

2) Data exploration and visualization 

3) Data splitting and feature engineering 

4) Testing of 5 different classifiers and selection of the best model

6) Hyperparameter optimization 

5) Estimation of best model performance on test set 

6) Testing of a Neural Network

## Conclusion
By randomly selecting 400 transactions out of 10.000 each month, the client was able to detect less than the 2% of the total frauds, on average. 

Using the ML pipeline I provide, the costumer will be able to detect 15 times more frauds (30% of the total). 

These results are pretty good considering that the fraudsters constantly optimize their strategies to escape anomaly detection algorithms. 




