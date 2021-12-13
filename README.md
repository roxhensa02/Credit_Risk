# Credit_Risk

## Overview of the analysis
*Explain the purpose of this analysis.*

In this analysis ww will eavlaute credit risk based on the loan history. We will employ different techniques to train and evaluate models with unbalanced classes to predict credit risks.



## Results: 
*Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.*

**Oversampling - Naive Random Oversampling**

Accuracy score: 64.6% (0.646602844334948)

![Chart](https://github.com/roxhensa02/Credit_Risk/blob/main/Images/naive%20random%20oversampling.PNG)


**Oversampling - SMOTE Oversampling**

Accuracy score: 66.2% (0.662394124702461)

![Chart](https://github.com/roxhensa02/Credit_Risk/blob/main/Images/Smote%20Oversampling.PNG)


**Undersampling - Cluster Centroids**

Accuracy score: 54.4% (0.5442166848817717)

![Chart](https://github.com/roxhensa02/Credit_Risk/blob/main/Images/ClusterCentroids.PNG)


**Combination (Over and Under) Sampling- SMOTEENN**

Accuracy score: 64.0% (0.6400726134353378)

 ![Chart](https://github.com/roxhensa02/Credit_Risk/blob/main/Images/Smoteenn.PNG)

**Balanced Random Forest Classifier**

Accuracy score: 78.9% (0.7885466545953005)

 ![Chart](https://github.com/roxhensa02/Credit_Risk/blob/main/Images/BrfClassifier.PNG)
 
 
**Easy Ensemble AdaBoost Classifier**

Accuracy score: 93.1.0% (0.9316600714093861)

  ![Chart](https://github.com/roxhensa02/Credit_Risk/blob/main/Images/EEAdaBoost.PNG)

##Summary: 

*Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning*

After reviewing the results from the different models, the most effective method is Easy Ensemble AdaBoost Classifier. This method has a 93.1% accuracy score. 
