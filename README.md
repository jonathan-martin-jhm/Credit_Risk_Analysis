# Credit_Risk_Analysis

## Overview
### Background
Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

* Deliverable 1: Use Resampling Models to Predict Credit Risk.
* Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk.
* Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk.
* Deliverable 4: A Written Report on the Credit Risk Analysis (README.md).

## Results
### Deliverable 1: Use Resampling Models to Predict Credit Risk.
Using your knowledge of the imbalanced-learn and scikit-learn libraries, you’ll evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. First, you’ll use the oversampling RandomOverSampler and SMOTE algorithms, and then you’ll use the undersampling ClusterCentroids algorithm. Using these algorithms, you’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

Notebook: [credit_risk_resampling.ipynb](https://github.com/jonathan-martin-jhm/Credit_Risk_Analysis/blob/main/Starter_Code%20(1)/Starter_Code/credit_risk_resampling.ipynb)

#### RandomOverSampler Algorithm
* Accuracy Score

![RandomOverSampler Accuracy Score](https://github.com/jonathan-martin-jhm/Credit_Risk_Analysis/blob/main/Starter_Code%20(1)/images/RandomOverSampler_AS.png)

* Confusion Matrix

![RandomOverSampler CM](https://github.com/jonathan-martin-jhm/Credit_Risk_Analysis/blob/main/Starter_Code%20(1)/images/RandoOverSampler_CM.png)

* Imbalanced Classification report

![RandomOverSampler ICR](https://github.com/jonathan-martin-jhm/Credit_Risk_Analysis/blob/main/Starter_Code%20(1)/images/RandoOverSampler_ICR.png)

#### SMOTE Algorithm
* Accuracy Score

![SMOTE AS](https://github.com/jonathan-martin-jhm/Credit_Risk_Analysis/blob/main/Starter_Code%20(1)/images/SMOTE_AS.png)

* Confusion Matrix

![SMOTE CM](https://github.com/jonathan-martin-jhm/Credit_Risk_Analysis/blob/main/Starter_Code%20(1)/images/SMOTE_CM.png)

* Imbalanced Classification report

![SMOTE ICR](https://github.com/jonathan-martin-jhm/Credit_Risk_Analysis/blob/main/Starter_Code%20(1)/images/SMOTE_ICR.png)

#### Cluster Centroids Algorithm
* Accuracy Score

![CC AS](https://github.com/jonathan-martin-jhm/Credit_Risk_Analysis/blob/main/Starter_Code%20(1)/images/CC_AS.png)

* Confusion Matrix

![CC CM](https://github.com/jonathan-martin-jhm/Credit_Risk_Analysis/blob/main/Starter_Code%20(1)/images/CC_CM.png)

* Imbalanced Classification report

![CC ICR](https://github.com/jonathan-martin-jhm/Credit_Risk_Analysis/blob/main/Starter_Code%20(1)/images/CC_ICR.png)



### Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk.
Using your knowledge of the imbalanced-learn and scikit-learn libraries, you’ll use a combinatorial approach of over- and undersampling with the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms from Deliverable 1. Using the SMOTEENN algorithm, you’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

### Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk.
Using your knowledge of the imblearn.ensemble library, you’ll train and compare two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model. Using both algorithms, you’ll resample the dataset, view the count of the target classes, train the ensemble classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.
credit_risk_ensemble.ipynb
## Summary
