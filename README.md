# Credit_Risk_Analysis

## This task is to employ different techniques to train and evaluate models with unbalanced classes to predict credit risk. Oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, use a combinatorial approach of over-and-undersampling using the SMOTEENN algorithm. Next, compare two machine learning models BalancedRandomForestClassifier and EasyEnsembleClassifier.

### Resources
- Data Source: LoanStats_2019Q1.csv

- Software: Jupyter Notebook 6.1.4

### Results
-Random Oversampling

![alt text](https://github.com/Yunaka1269/Credit_Risk_Analysis/blob/main/picture/RandomOverSampler.PNG "Random_Oversampling")

	-Balanced accuracy scores : 0.6603423204808787
	-Precision scores
		- High risk : 0.01
		- Low risk : 1.00
	-Recall scores
		- High risk : 0.74 
		- Low risk : 0.58 

-Synthetic Minority Oversampling Technique (SMOTE)

![alt text](https://github.com/Yunaka1269/Credit_Risk_Analysis/blob/main/picture/SMOTE.PNG "SMOTE")

	-Balanced accuracy scores : 0.6537310478007576
	-Precision scores
		- High risk : 0.01
		- Low risk : 1.00
	-Recall scores
		- High risk : 0.62
		- Low risk : 0.68

-Cluster Centroid Undersampling

![alt text](https://github.com/Yunaka1269/Credit_Risk_Analysis/blob/main/picture/ClusterCentroids.PNG "Cluster_Centroids")

	-Balanced accuracy scores : 0.6537310478007576
	-Precision scores
		- High risk : 0.01
		- Low risk : 1.00
	-Recall scores
		- High risk : 0.68
		- Low risk : 0.41

-SMOTEENN

![alt text](https://github.com/Yunaka1269/Credit_Risk_Analysis/blob/main/picture/SMOTEENN.PNG "SMOTEENN")

	-Balanced accuracy scores : 0.5474716701090128
	-Precision scores
		- High risk : 0.01
		- Low risk : 1.00
	-Recall scores
		- High risk : 0.72
		- Low risk : 0.57

-BalancedRandomForestClassifier

![alt text](https://github.com/Yunaka1269/Credit_Risk_Analysis/blob/main/picture/BalancedRandomForestClassifier.PNG "Balanced_Random_Forest_Classifier")

	-Balanced accuracy scores : 0.7885466545953005
	-Precision scores
		- High risk : 0.03
		- Low risk : 1.00
	-Recall scores
		- High risk : 0.70
		- Low risk : 0.87

-EasyEnsembleClassifier

![alt text](https://github.com/Yunaka1269/Credit_Risk_Analysis/blob/main/picture/EasyEnsembleClassifier.PNG "EasyEnsemble_Classifier")

	-Balanced accuracy scores : 0.9316600714093861
	-Precision scores
		- High risk : 0.09
		- Low risk : 1.00 
	-Recall scores
		- High risk : 0.92 
		- Low risk : 0.94

### Summary 
EasyEnsembleClassifier, the classifier is an ensemble of AdaBoost learners trained on different balanced boostrap samples, shows the higest precision scores and recall scores as well as accuracy scores among six train and evaluate models.
