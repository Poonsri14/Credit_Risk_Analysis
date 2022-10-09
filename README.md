# Credit_Risk_Analysis
ML, python

### Overview of the loan prediction risk analysis:

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, it needs to employ different techniques to train and evaluate models with unbalanced classes. 

To use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company. For oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Furthermore, combinatorial approach of over- and undersampling using the SMOTEENN algorithm that will reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 


### Results: 

The above pictures are showing the balanced accuracy score and the precision and recall scores of all six machine learning models.

From the over, under, and combination sampling results, the balanced accuracy scores are low which are 0.67, 0.54, and 0.64, respectivly. The average precision scores are good. However, the recall scores are low for low risk credit and is reflected in dropped the F1 score as well. 

For BalancedRandomForestClassifier and EasyEnsembleClassifier models have high model's accuracy, recall, F1 score are high (0.93).


#### Balanced Accuracy Score and The Imbalanced Classification Report for each machine learning models


#### Oversampling: Naive RandomOverSampler VS SMOTE

##### Naive RandomOverSampler 
![1](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/RandomOverSampler_AC.png)
![1](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/RandomOverSampler_Table.png)

##### SMOTE
![2](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/SMOTE_AC.png)
![2](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/SMOTE_Table.png)

#### Undersampling

##### ClusterCentroids
![4](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids_AC.png)
![4](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids_Table.png)


### Combination(Over and Under)sampling

##### SMOTEENN
![3](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN_AC.png)
![3](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN_Table.png)



### Ensemble Algorithms: BalancedRandomForestClassifier VS EasyEnsembleClassifier

##### BalancedRandomForestClassifier
![5](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForestClassifier_AC.png)
![5](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForestClassifier_Table.png)

##### EasyEnsembleClassifier
![6](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/EasyEnsembleClassifier_AC.png)
![6](https://github.com/Poonsri14/Credit_Risk_Analysis/blob/main/Resources/EasyEnsembleClassifier_Table.png)


### Summary:

In summary, this BalancedRandomForestClassifier and EasyEnsembleClassifier models are good at credit card risk analysis because the models's accuracy, 0.79 are high, and the precision and recall and F1 are good enough to state that the model will be good at classifying credit card risk applications. F1 score is high (0.93). The both model are efficiency and no need to do the addtional test modle.



