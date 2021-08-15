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

### Summary: 
When originally looking at the data set we can see according to balance of our target values - that there is a big discrepancy  between the number of low risk and high risk loans. So we can see that the data is already imbalanced, but that is why we split took a few different approaches above to see what would be the most advantageous. When looking primarily at the balanced accuracy score the Easy Ensemble AdaBoost Classifier records the highest score of .912. This model also records the highest f1 score on an average/total. The F1 score is that a pronounced imbalance between sensitivity and precision will yield a low F1 score. Just by looking at these two metrics, I would recommend the Easy Ensemble AdaBoost Classifier model.









