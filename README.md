# Credit_Risk_Analysis

### Overview of the analysis: Explain the purpose of this analysis.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. I employed different techniques to train and evaluate models with unbalanced classes. Jill asked us to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we will oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Finally, we compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

### Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

#### Balanced Random Forest Classifier
![](https://github.com/akmilton11/Credit_Risk_Analysis/blob/main/Images/Balanced%20Random%20Forest%20Classifier.PNG)

#### Easy Ensemble AdaBoost Classifier
![](https://github.com/akmilton11/Credit_Risk_Analysis/blob/main/Images/Easy%20Ensemble%20AdaBoost%20Classifier.PNG)

#### Naive Random Oversampling
![](https://github.com/akmilton11/Credit_Risk_Analysis/blob/main/Images/Naive%20Random%20Oversampling.PNG)

#### SMOTE Oversampling
![](https://github.com/akmilton11/Credit_Risk_Analysis/blob/main/Images/SMOTE%20Oversampling.PNG)

#### SMOTE Undersampling
![](https://github.com/akmilton11/Credit_Risk_Analysis/blob/main/Images/Undersampling.PNG)

#### SMOTEENN
![](https://github.com/akmilton11/Credit_Risk_Analysis/blob/main/Images/SMOTEENN.PNG)

### Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.







