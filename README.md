# Credit Risk Analysis

## Project Overview
This is a machine learning project that predicts credit risk in loan applicants. By employing supervised machine learning algorithms, we can resample, train, and test our model, and compare the performance of each of the algorithms in the accuracy of accurately predicting credit risk. 

The algorithms used for this project include RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, as well as ensemble classifiers including BalancedRandomForestClassifier and EasyEnsembleClassifier. 

## Results
The accuracy, precision, and recall were calculated for each of the six techniques used for this project. 

- RandomOverSampler:
    - Accuracy: 64.6%
    - Precision: 0.99%
    - Recall: 71.3%

    ![ros](Images/ros.png)

- SMOTE:
    - Accuracy: 65.9%
    - Precision: 1.2%
    - Recall: 63.4%

    ![smote](Images/smote.png)

- ClusterCentroids:
    - Accuracy: 66.7%
    - Precision: 0.67%
    - Recall: 69.3%

    ![cluster](Images/cluster.png)

- SMOTEENN:
    - Accuracy: 54.4%
    - Precision: 1.1%
    - Recall:  73.3%

    ![smoteenn](Images/smoteenn.png)

- BalancedRandomForestClassifier:
    - Accuracy: 78.9%
    - Precision: 3.2%
    - Recall: 70.3%

    ![forest](Images/forest.png)

- EasyEnsembleClassifier:
    - Accuracy: 93.1%
    - Precision: 8.6%
    - Recall: 92.1%

    ![easy](Images/easy.png)


## Summary

All accuracy scores were above 50%, with the highest being EasyEnsembleClassifier with 93%. 
Precision was usually below 2%, with the highest being EasyEnsembleClassifier with 8.6%. 
Recall varied between 60-75% for most models, but was highest for EasyEnsembleClassifier with 92.1%. 

The EasyEnsembleClassifier model seems to be a clear choice for this analysis. With the highest accuracy, precision, and recall, it will reduce the total number of errors and incorrectly flagged applications being evaluated. 