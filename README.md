![Credit Risk](Images/credit-risk.jpg)
# Week 11 Classification Assignment: Risky Business

In this assignment you will build and evaluate several machine learning models to predict credit risk using data you'd typically see from peer-to-peer lending services. Credit risk is an inherently imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans), so you will need to employ different techniques for training and evaluating models with imbalanced classes. You will use the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the two following techniques:

1. Resampling
 
2. Ensemble-Learning

## Resampling

* Which model had the best balanced accuracy score?

SMOTE Oversampling has the best balanced accuracy score of 0.9948 whereas Combination Sampling provided the balanced accuracy score of 0.9947.

* Which model had the best recall score?

Most models have the recall score of 0.99

* Which model had the best geometric mean score?

Apart from Undersampling and logistical regression, all models have a geometric mean score of 0.99

## Ensemble Learning

* Which model had the best balanced accuracy score?

Balanced Random Forest provided a balanced accuracy score of 76.7%

* Which model had the best recall score?

Random Forest Classifier provided an average recall score of 1.0

* Which model had the best geometric mean score?


Balanced Random Forest provided a balanced accuracy score of 76.0%

* What are the top three features?

These are the top three features in our dataset:

1) 'total_rec_prncp' 2) 'total_rec_int' 3) 'total_pymnt_inv'
