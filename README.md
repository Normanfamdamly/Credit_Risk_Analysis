# Credit_Risk_Analysis- Challenge Module 17
---

## Overview

Financial institutions must always be concerned with credit risk if they are in the business of loaning money to clients.  So, they need a way to estimate which clients are the better risk to loan funds too.  This project is designed to apply machine learning to help predict which applicants have high or low credit risk.  Allowing Lending Club to make informed decision on offering credit to their clients and hopefully limit any losses in the future due to default in payments.

### Results
---
This project will utilize 6 specific libraries from imbalanced-learn and scikit-learn models to help evaluate through resampling, oversampling, randomsampling, and undersampling of the data.  It will also include algorithms that include SMOTE, SMOTEENN and clustercentroid, along with two machine learning models that should help to minimize any bias such as balancedrandomforsedtclassifier and AdaBoost Classifier.

#### Naive Random Oversampling

      - Balanced Accuracy Score is 63%
      - High Risk has a low positivity at 1% 
      - Recall is at 57%  

![naive_random_oversampling.png](https://github.com/Normanfamdamly/Credit_Risk_Analysis/blob/main/images/naive_random_oversampling.png)

### SMOTE Oversampling

      -  Balanced Accuracy Score is 63%
      -  High Risk has a low positivity at 1% 
      -  Recall is at 62%
      
![smote_oversampling.png](https://github.com/Normanfamdamly/Credit_Risk_Analysis/blob/main/images/smote_oversampling.png)

### Undersampling

      -  Balanced Accuracy Score is 63%
      -  High Risk has a low positivity at 1% 
      -  Recall is at 57%
     
![undersampling.png](https://github.com/Normanfamdamly/Credit_Risk_Analysis/blob/main/images/undersampling.png)

### Combo

      -  Balanced Accuracy Score is 52%
      -  High Risk has a low positivity at 1% 
      -  Recall is at 70%
      
![combo.png](https://github.com/Normanfamdamly/Credit_Risk_Analysis/blob/main/images/combo.png)

### BalancedRandomForestClassifier

      -  Balanced Accuracy Score is 79%
      -  High Risk has a low positivity at 3% 
      -  Recall is at 70%
      
![balanced_random_forest_classifier.png](https://github.com/Normanfamdamly/Credit_Risk_Analysis/blob/main/images/balanced_random_forest_classifier.png)

### AdaBoost

      -  Balanced Accuracy Score is 93%
      -  High Risk has a low positivity at 9% 
      -  Recall is at 92%
      
![ada_boost.png](https://github.com/Normanfamdamly/Credit_Risk_Analysis/blob/main/images/ada_boost.png)



## Summary
---

After looking through all the models the one I would recommend is the AdaBoost since it had the best results and accuracy rate of 93% and 9% high risk low positivity rate with a recall of 92%.  This gave us the most diverse results.  Most of the other models did not have a diverse population of High-risk clients to see a real test environment to know if the analysis was good or not.  I actually think the data was rather a skewed because of the large percentage of low-risk accounts. I am not sure the data was the best to use to test on Machine learning since it was rather white washed with "good credit" users.  I would recommend utilizing data that is more in line with the real-world next time to get a better result.





