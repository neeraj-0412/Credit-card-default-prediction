Here is a `README.md` file based on the provided information:

---

# Credit Card Default Prediction

## Problem Description

This project aims to predict the likelihood of customers defaulting on their credit card payments in Taiwan. From a risk management perspective, predicting the probability of default provides more valuable insights than merely classifying clients as credible or not. The K-S chart is employed to evaluate which customers are likely to default on their payments.

## Objective

The primary objective of this project is to identify which customers might default on their credit card payments in the upcoming months. Before delving into the specifics, let’s clarify what credit card default entails.

### What is Credit Card Default?

A credit card is a payment card where charges are made against a line of credit rather than the account holder's cash deposits. When a purchase is made using a credit card, the account accrues a balance that must be paid off monthly. Credit card default occurs when a cardholder becomes severely delinquent on their payments. Missing one or two payments does not constitute a default. Default happens when the Minimum Amount Due on the credit card is not paid for several consecutive months.

## Conclusion

This project evaluates the performance of various models in predicting credit card defaults. The Random Forest Classifier emerged as the top performer, achieving a recall score of 0.95 on the test set. It was closely followed by Gradient Boosting and XGBoost, with recall scores of 0.93 and 0.92, respectively. Overfitting in multiple models was mitigated through hyperparameter tuning and cross-validation, as evidenced by improved scores. Model explainability was achieved using Lime and ELI5, revealing that the most significant predictors of default were the repayment amounts in the most recent months.
