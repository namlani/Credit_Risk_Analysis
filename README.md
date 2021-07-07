# Credit_Risk_Analysis

## Overview
Created a supervised machine learning model in order to accurately predict credit risk. Using a credit card dataset from LendingClub, a peer-to-peer lending services company, the data was oversampled using the RandomOverSampler and SMOTE algorithms, and undersampled using the ClusterCentroids algorithm. Then, a combinatorial approach of over- and undersampling employing the SMOTEENN algorithm was used. Next, two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, were used to predict credit risk. Finally, the performance of these models were evaluated and a written recommendation was made on whether they should be used to predict credit risk.

## Results
### Naive Random Oversampling
* Accuracy Score: 66.7%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 68%
* Recall Low Risk: 66%
![image](https://user-images.githubusercontent.com/5934390/124789292-2b15f300-df18-11eb-8379-2d80bab4821d.png)

### SMOTE Oversampling

* Accuracy Score: 67.2%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 69%
* Recall Low Risk: 65% 
![image](https://user-images.githubusercontent.com/5934390/124789788-9233a780-df18-11eb-8ec7-4b54df431fa7.png)

### Cluster Centroid Undersampling

* Accuracy Score: 53.2%
* Precision High Risk: 0%
* Precision Low Risk: 100%
* Recall High Risk: 64%
* Recall Low Risk: 43%
![image](https://user-images.githubusercontent.com/5934390/124790852-872d4700-df19-11eb-992f-788190ffc7a2.png)

### SMOTEENN Over/Under Sampling
* Accuracy Score: 68.1%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 76%
* Recall Low Risk: 60%
![image](https://user-images.githubusercontent.com/5934390/124791196-d6737780-df19-11eb-8eba-990b66c57659.png)

### Balanced Random Forest Classifier
* Accuracy Score: 64.8%
* Precision High Risk: 56%
* Precision Low Risk: 100%
* Recall High Risk: 30%
* Recall Low Risk: 100%
![image](https://user-images.githubusercontent.com/5934390/124791689-48e45780-df1a-11eb-8b55-9cf484239ff9.png)

### Easy Ensemble Classifier
* Accuracy Score: 92.3%
* Precision High Risk: 6%
* Precision Low Risk: 100%
* Recall High Risk: 91%
* Recall Low Risk: 94%
![image](https://user-images.githubusercontent.com/5934390/124792229-d1fb8e80-df1a-11eb-8214-e2308989c193.png)

### Summary
The accuracy score could be looked as a summarizing statistic, as it can provide a general indication of how well each model performed. All models appear to have a relatively low accuracy score, except for the Easy Ensemble Classifier, which has a score of 92.3%. Based on this summary, I would recommend using the Easy Ensemble Classifier model.
