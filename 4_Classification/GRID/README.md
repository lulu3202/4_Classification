#  Hands-on project implementing Grid Search for classification models

## Introduction
This project is about using GridSearch method (with test/train split data and standard scalar method) for comparing various classification models such as  NB, DT etc. to predict whether or not the customer will buy a product that was shown in an advertisement (dependent variable) based on the independent variables of Gender, Age and estimated salary. 

Grid search is a machine learning technique that helps identify the best hyperparameters for a model to improve its accuracy and performance. It's a brute-force method that involves defining a grid of hyperparameter values and evaluating the model's performance at each point on the grid. The goal is to find the combination of parameters that optimizes the model's performance, which can lead to better predictions or classifications. 

For classification models, I have used 'f1-weighted' as scoring to pick the best model. 

## Dataset
- This dataset is called Social_Network_Ads. It contains 5 columns in total and 400 rows. We drop user id column as it is not relevant. Gender column is categorical. Through 1 hot encoding, we use get_dummies function from pandas to convert categorical values to numerical values. 

To find whether the data is balanced, we use value_counts of the target variable and to also find the total number of classes to classify into. 


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
	- I ran  GridSearch method (with test/train split data) for various classification models
	- I found SVM classification as the best model as the roc was highest value of 0.96

