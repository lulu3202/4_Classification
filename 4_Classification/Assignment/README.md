# Classification Hands-on project to predict chronic kidney disease 

## Introduction
Based on a set of input parameters, we need to identify whether or not a patient will have chronic kidney disease. 
	- Input variables are numerical –  so we use Machine learning 
	- We have clearly labelled data with a clear target variable of classification – so we use Supervised learning 
	- The required output is a binary outcome of Yes or no – so we use Classification

## Dataset
- Is called CKD  and has a total of 399 rows × 25 columns
-As part of data preprocessing, I converted categorical values to nominal values using:
	dataset=pd.get_dummies(dataset,dtype=int, drop_first=True)
	 The pd.get_dummies() function in pandas is used to perform one-hot encoding.
	 
	One-Hot Encoding: This is a technique used to convert categorical variables into a numerical format that can be used in machine learning algorithms. Each unique category is represented by a binary column (0 or 1).
	
## Model Creation/Learning
- Data Collection
- Data Preprocessing
- Input/Output Split
- Split Train and Test Data 
- Create model with Train Data via regressor.fit method
- Evaluate/Test model performance with the Test set
- Save the best model 

## Model deployment
1 - Creating the model (in jupyter notebook)
2 - Saving the model (using pickle, save the finalized model and perform pickle dump which will result in a .sav file) 
3 - Deploying the model (create new deployment notebook to call on and open the saved model) 

## Evaluation Metric Results
	- I ran 10 classification algorithms, out of which Logistic Regression Classification was the best 
	- Accuracy is 0.99 - - This indicates that the model correctly classified 99% of the instances in the test dataset
	- Roc_Aoc_score is 1 - This means that the ROC curve (Receiver Operating Characteristic curve) achieves the maximum value,  indicating that the model perfectly
	- Best Parameters that worked was: {'penalty': 'l2', 'solver': 'newton-cg'}
