# Credit_Risk_Analysis

## Overview of analysis:
Analyzing a credit card credit data set from LendingClub, a peer to peer lending services company, we will use different approaches of machine learning to train and evaluate models with unbalanced classes using imbalanced-learn and scikit-learn libraries. We will also use different algorithms to predict credit risk:
- RandomOverSampler
- SMOTE
- ClusterCentroids
- SMOTEEN
- BalancedRandomForestClassifier
- EasyEnsembleClassifier

## Results: Balanced Accuracy scores and precision of each algorithm model
### RandomOverSampler
![image](https://user-images.githubusercontent.com/96352427/167324024-02b6a31c-afab-48de-a770-38276d4596ac.png)
The balanced accuracy score is 65%.
![image](https://user-images.githubusercontent.com/96352427/167335777-21e9acc6-5dc6-426a-8862-14c310c0342c.png)
The precision for the high risk is at 1% while the low risk is at 100% and with recall scores at 63% for high risk and 68% for low risk.

### SMOTE
![image](https://user-images.githubusercontent.com/96352427/167336117-2a008c84-13be-488d-ae26-3c5a19aef29c.png)
The balanced accuracy score is 63%.
![image](https://user-images.githubusercontent.com/96352427/167336173-a1137b59-9aae-481d-9e80-8d1a3b32f275.png)
The precision for high risk is at 1% and 100% for low risk and recall scores for high risk is 57% and 68% for low risk.

### ClusterCentroids
![image](https://user-images.githubusercontent.com/96352427/167336629-47bfb257-1947-4037-a4a2-ebff13e43fbe.png)
The balanced accuracy score is 63%.
![image](https://user-images.githubusercontent.com/96352427/167336696-61567fa9-d072-476e-8383-14eaaf1c6230.png)
The precision for high risk is at 1% and 100% for low risk and recall scores for high risk is 59% and 43% for low risk.

### SMOTEEN
![image](https://user-images.githubusercontent.com/96352427/167336779-4aa287cf-c203-4254-b0a7-4b2f8a9adf10.png)
The balanced accuracy score is 51%.
![image](https://user-images.githubusercontent.com/96352427/167336814-c3a03a95-4148-4119-9ab8-14f0cc0d867a.png)
The precision for high risk is at 1% and 100% for low risk and recall scores for high risk is 70% and 57% for low risk.

### BalancedRandomForestClassifier
![image](https://user-images.githubusercontent.com/96352427/167336913-d88e651e-15ea-4952-9b6e-429eff1976fd.png)
The balanced accuracy score is 79%.
![image](https://user-images.githubusercontent.com/96352427/167336943-8d9c824e-e1fc-47c4-a8af-8512e5377c5e.png)
The precision for high risk is at 3% and 100% for low risk and recall scores for high risk is 70% and 87% for low risk.

### EasyEnsembleClassifier
![image](https://user-images.githubusercontent.com/96352427/167336993-2b4725e5-c3f8-4607-ba69-bce58dffe92d.png)
The balanced accuracy score is 93%.
![image](https://user-images.githubusercontent.com/96352427/167337033-3bfbbad2-5d46-4a1b-8282-82f5937e7761.png)
The precision for high risk is at 9% and 100% for low risk and recall scores for high risk is 92% and 94% for low risk.

## Summary:
All machine learning algorithms had low precision scores for high risk credit and 100% scores for low risk credits. This does not show an accurate representation of true positive scores. However, among all methods, the EasyEnsembleClassifier algorithm did seem to show the highest recall scores for low and high risk credit. This shows that this method may be the best algorithm to use when trying to predict true credit risks. 

