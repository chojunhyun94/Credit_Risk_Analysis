# Credit_Risk_Analysis

## Overview
This project is designed to find the best model to determine credit risk. Using imbalanced-learn and scikit-learn, I am building and evaluating models that can be used to determine the credit risk using resampling. 

The data is trained from credit card credit dataset from LendingClub, a peer-to-peer lending services company. The following supervised machine learning models will be used:
- RandomOverSampler
- SMOTE 
- ClusterCentroids
- SMOTEENN
- BalancedRandomForestClassifier
- EasyEnsembleClassifier

The first 3 is a focus on oversampling data, followed by an over- and undersampling appraoch with SMOTEEN and finally the last 2 reduce bias.

To reduce variability over testing data, I used a consistent random_state of 1, which can easily be changed later on to train the models further.

## Results


## Summary