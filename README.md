# Credit_Risk_Analysis

## Overview of Analysis

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, I’ll need to employ different techniques to train and evaluate models with unbalanced classes. I'll use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, I’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. I’ll also compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once we’re done, I’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.


## Results:

Accuracy Score:  

- Score for Nave Random Oversampling Accuracy: 0.6595 = 66%


- Oversampling Accuracy Score for SMOTE: 0.6628 = 66%


- Score for Undersampling Accuracy: 0.6628 = 66%


- Sampling Accuracy Score for Combination (Over and Under): 0.6445 = 64%


- Accuracy of the Balanced Random Forest Classifier: 0.7959 = 80%


- Accuracy of the Easy Ensemble AdaBoost Classifier: 0.9197 = 91% 


Score of precision: 

- Precision Score for all was 99%


Score for Recall (Sensitivity): 

- Sensitivity of Nave Random Oversampling: 0.60 = 60%


- SMOTE Sensitivity Score for Oversampling: 0.69 = 69%


- Sensitivity Score for Undersampling: 0.69 = 69%


- Sensitivity Score for Combination (Over and Under) Sampling: 0.57 = 57%


- Sensitivity Score of the Balanced Random Forest Classifier: 0.91 = 91%


- Sensitivity Score of the Easy Ensemble AdaBoost Classifier: 0.94 = 94%

F1 Score: 

- F1 Score of Nave Random Oversampling: 0.74 = 74% 


- SMOTE Oversampling F1 Score: 0.81 = 81%


-  Undersampling F1 Score: 0.81 = 81%

- Combination (Over and Under) Sampling- F1 Score: 0.72= 72%

- F1 Score of the Balanced Random Forest Classifier: 0.95 = 95%


- F1 Score of the Easy Ensemble AdaBoost Classifier: 0.97 = 97%



## Summary
Precision score for all was 99%, accuracy and sensitivity scores varied accross board. The Ensemble AdaBoost Classifier had the highest accuracy and Recall scores, at 92% and 94% respectively.

Therefore, I recommend that the Easy Ensemble AdaBoost Classifier machine learning model be used to forecast credit risk based on the results and additional data analysis. It constantly received the greatest ratings, especially in terms of accuracy, precision, and sensitivity, and hence successfully predicted the outcomes when compared to the other models.
