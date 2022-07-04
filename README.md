# Credit_Risk_Analysis

## Overview of the analysis: 

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results: 

### Random Oversampling: 
- Accuracy Score: 0.645
![oversampling](https://github.com/Lesliec87/Credit_Risk_Analysis/blob/main/Resources/oversampling.png)

### Smote Oversampling:
- Accuracy Score: 0.619
![smote](https://github.com/Lesliec87/Credit_Risk_Analysis/blob/main/Resources/smote.png)

### Undersampling (ClusterCentroids):
- Accuracy Score: 0.529
![undersampling](https://github.com/Lesliec87/Credit_Risk_Analysis/blob/main/Resources/Undersampling.png)

### Combination Sampling (Smoteen):
- Accuracy Score: 0.529
![smoteen](https://github.com/Lesliec87/Credit_Risk_Analysis/blob/main/Resources/Smooten.png)

### Balance Random Forest Classifier:
- Accuracy Score: 0.995
![forest](https://github.com/Lesliec87/Credit_Risk_Analysis/blob/main/Resources/forest%20classifier.png)


## Summary: 


