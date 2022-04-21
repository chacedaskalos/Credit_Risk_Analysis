# Credit_Risk_Analysis
Supervised Machine Learning

## Overview

This project used scikit-learn and imbalanced-learn to train and evaluate models to determine credit card risk. Oversampling with the RandomOverSampler and SMOTE algorithms, Undersampling with the ClusterCentroids algorithm, a combination of over and under sampling with the SMOTEENN algorithm, and two machine learning models BalancedRandomForestClassifer and EasyEnsembleClassifier were used.

## Results

### Naive Random Oversampling 
![Naive Random Oversampling](https://user-images.githubusercontent.com/96211484/164553028-55f5a14b-dbfc-4227-ae23-94a32d7e9c96.png)
* The balanced accuracy score is 64.1%, which means the model predicted the credit risk accurately 64.1% of the time
* The precision score for low_risk loans was perfect, but only 0.01 for high_risk loans
* The recall scores show how this model is better at predicting low_risk (0.68) than high_risk (0.60)

### SMOTE Oversampling
![SMOTE Oversampling](https://user-images.githubusercontent.com/96211484/164554172-406acada-5998-46e0-b96c-18a60c97149f.png)
* The balanced accuracy score is 63.7%, which means the model predicted the credit risk accurately 63.7% of the time
* The precision score for low_risk loans was perfect, but only 0.01 for high_risk loans
* The recall scores show how this model is better at predicting low_risk (0.68) than high_risk (0.60)



## Summary

