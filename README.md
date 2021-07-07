# Credit_Risk_Analysis

## Overview
Created a supervised machine learning model in order to ccurately predict credit risk. Using a credit card credit dataset from LendingClub, a peer-to-peer lending services company, the data was oversampled using the RandomOverSampler and SMOTE algorithms, and undersampled using the ClusterCentroids algorithm. Then, used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Finally, evaluated the performance of these models and made a written recommendation on whether they should be used to predict credit risk.

## Results
### Naive Random Oversampling
* Accuracy Score: 67.4%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 72%
* Recall Low Risk: 63%
![image](https://user-images.githubusercontent.com/5934390/124789292-2b15f300-df18-11eb-8379-2d80bab4821d.png)
