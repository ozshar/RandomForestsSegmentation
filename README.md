# RandomForestsSegmentation
Further uses of Random Forest  : Segmentation and detection of features interactions 


Main purpose : Uncover some of Random forest "black box" and get useful insights : 
	1. Find the main segments that best distinguish diabete from non-diabete samples.
	2. Find most significant interactions between features. Can provide new domain insights as well as new features for the linear models.

Dataset used : PIMA Indians diabetes dataset - https://www.kaggle.com/uciml/pima-indians-diabetes-database  

Main structure : 
	1. Basic EDA 
	2. Data cleaning : Define 3 cleanesed datasets - by 3 different cleansing strategies.
	3. Diabetes predictions : Compare few ML models preformance (Accuracy and AUC under ROC) on the 3 cleansed datasets.
	4. Finally, and MOST IMPORTANTLY, extract from random forest algorithm:
		* Segmentation method.
		* Most significant interactions between features. 
		  
