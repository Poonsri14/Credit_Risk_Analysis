# Credit_Risk_Analysis
ML, python

### Overview of the loan prediction risk analysis:

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, it needs to employ different techniques to train and evaluate models with unbalanced classes. 

To use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company. For oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Furthermore, combinatorial approach of over- and undersampling using the SMOTEENN algorithm that will reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 


### Results: 

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.(15 pt)


#### Balanced Accuracy Score and The Imbalanced Classification Report for each machine learning models


##### RandomOverSampler 
![1](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/RandomOverSampler_AC.png)
![1](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/RandomOverSampler_Table.png)

##### SMOTEENN
![2](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN_AC.png)
![2](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN_Table.png)

##### SMOTE
![3](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/SMOTE_AC.png)
![3](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/SMOTE_Table.png)

##### ClusterCentroids
![4](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids_AC.png)
![4](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids_Table.png)

##### BalancedRandomForestClassifier
![5](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForestClassifier_AC.png)
![5](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForestClassifier_Table.png)

##### EasyEnsembleClassifier
![6](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/EasyEnsembleClassifier_AC.png)
![6](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/EasyEnsembleClassifier_Table.png)








### Summary:

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification If you do not recommend any of the models, justify your reasoning.

(3 pt)
