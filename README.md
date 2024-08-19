# General Notes on Classification
When the outcome that we want to predict is a categorical variable, we go for classification. We use confusion matrix (instead of minimum error/r square that’s used in regression). 

## Introduction
This repo contains different types of classification models and a demonstration of how they work along with hands-on projects. Individual README files has been added for every type of model (that includes  dataset description, process and results discussion) 

# 1. Random Forest Classification  
## Introduction
This project is about developing a classification model to predict whether or not the customer will buy a product that was shown in an advertisement (dependent variable) based on the independent variables of Gender, Age and estimated salary. 

## Dataset
- This dataset is called Social_Network_Ads. It contains 5 columns in total and 400 rows. We drop user id column as it is not relevant. Gender column is categorical. Through 1 hot encoding, we use get_dummies function from pandas to convert categorical values to numerical values. 

To find whether the data is balanced, we use value_counts of the target variable and to also find the total number of classes to classify into. 

## Model Creation/Learning
- Data Collection
- Data Preprocessing
- Input/Output Split
- Split Train and Test Data
- Create model with Train Data
- Evaluate/Test model performance with the Test set
- Save the best model 

## Model deployment
1 - Creating the model (in jupyter notebook)
2 - Saving the model (using pickle, save the finalized model and perform pickle dump which will result in a .sav file) 
3 - Deploying the model (create new deployment notebook to call on and open the saved model) 

## Evaluation Metric Results
-Confusion matrix is imported and evaluated with classification report
- Achieved an accuracy of 0.90


# 2. Decision Tree Classification 
## Introduction
This project is about developing a classification model to predict whether or not the customer will buy a product that was shown in an advertisement (dependent variable) based on the independent variables of Gender, Age and estimated salary. 

## Dataset
- This dataset is called Social_Network_Ads. It contains 5 columns in total and 400 rows. We drop user id column as it is not relevant. Gender column is categorical. Through 1 hot encoding, we use get_dummies function from pandas to convert categorical values to numerical values. 

To find whether the data is balanced, we use value_counts of the target variable and to also find the total number of classes to classify into. 

## Model Creation/Learning
- Data Collection
- Data Preprocessing
- Input/Output Split
- Split Train and Test Data
- Create model with Train Data
- Evaluate/Test model performance with the Test set
- Save the best model 

## Model deployment
1 - Creating the model (in jupyter notebook)
2 - Saving the model (using pickle, save the finalized model and perform pickle dump which will result in a .sav file) 
3 - Deploying the model (create new deployment notebook to call on and open the saved model) 

## Evaluation Metric Results
-Confusion matrix is imported and evaluated with classification report
- Achieved an accuracy of 0.87


# 3. SVM Classification 
## Introduction
This project is about developing a classification model to predict whether or not the customer will buy a product that was shown in an advertisement (dependent variable) based on the independent variables of Gender, Age and estimated salary. 
 
## Dataset
- This dataset is called Social_Network_Ads. It contains 5 columns in total and 400 rows. We drop user id column as it is not relevant. Gender column is categorical. Through 1 hot encoding, we use get_dummies function from pandas to convert categorical values to numerical values. 
 
To find whether the data is balanced, we use value_counts of the target variable and to also find the total number of classes to classify into. 
 
## Model Creation/Learning
- Data Collection
- Data Preprocessing
- Input/Output Split
- Split Train and Test Data
- Create model with Train Data
- Evaluate/Test model performance with the Test set
- Save the best model 
 
## Model deployment
1 - Creating the model (in jupyter notebook)
2 - Saving the model (using pickle, save the finalized model and perform pickle dump which will result in a .sav file) 
3 - Deploying the model (create new deployment notebook to call on and open the saved model) 
 
## Evaluation Metric Results
-Confusion matrix is imported and evaluated with classification report
- Achieved an accuracy of 0.78


## 4. Logistic Regression Classification 
## Introduction
This project is about developing a classification model to predict whether or not the customer will buy a product that was shown in an advertisement (dependent variable) based on the independent variables of Gender, Age and estimated salary. 

In logistic algorithm, the Y values range between 0 and 1. 0.5 is considered as threshold value. If y is less than 0.5 then it is considered 0/not purchased and it it is above 0.5, it is considered 1/purchased value. So sigmoid works great for binary classification. 

## Dataset
- This dataset is called Social_Network_Ads. It contains 5 columns in total and 400 rows. We drop user id column as it is not relevant. Gender column is categorical. Through 1 hot encoding, we use get_dummies function from pandas to convert categorical values to numerical values. 

To find whether the data is balanced, we use value_counts of the target variable and to also find the total number of classes to classify into. 

## Model Creation/Learning
- Data Collection
- Data Preprocessing
- Input/Output Split
- Split Train and Test Data
- Create model with Train Data
- Evaluate/Test model performance with the Test set
- Save the best model 

## Model deployment
1 - Creating the model (in jupyter notebook)
2 - Saving the model (using pickle, save the finalized model and perform pickle dump which will result in a .sav file) 
3 - Deploying the model (create new deployment notebook to call on and open the saved model) 

## Evaluation Metric Results
-Confusion matrix is imported and evaluated with classification report
- Achieved an accuracy of 0.63


## 5. KNN Classification 
## Introduction
This project is about developing a classification model to predict whether or not the customer will buy a product that was shown in an advertisement (dependent variable) based on the independent variables of Gender, Age and estimated salary. 

Different K values will give different results

## Dataset
- This dataset is called Social_Network_Ads. It contains 5 columns in total and 400 rows. We drop user id column as it is not relevant. Gender column is categorical. Through 1 hot encoding, we use get_dummies function from pandas to convert categorical values to numerical values. 

To find whether the data is balanced, we use value_counts of the target variable and to also find the total number of classes to classify into. 

## Model Creation/Learning
- Data Collection
- Data Preprocessing
- Input/Output Split
- Split Train and Test Data
- Create model with Train Data
- Evaluate/Test model performance with the Test set
- Save the best model 

## Model deployment
1 - Creating the model (in jupyter notebook)
2 - Saving the model (using pickle, save the finalized model and perform pickle dump which will result in a .sav file) 
3 - Deploying the model (create new deployment notebook to call on and open the saved model) 

## Evaluation Metric Results
-Confusion matrix is imported and evaluated with classification report
- Achieved an accuracy of 0.84


# 6. NB Classification 

## Introduction
This project is about developing a classification model to predict whether or not the customer will buy a product that was shown in an advertisement (dependent variable) based on the independent variables of Gender, Age and estimated salary. 

This is a probabilistic ML algorithm. Zero frequency issue in NB algorithm can be fixed by adding 1 to all values. 

## Dataset
- This dataset is called Social_Network_Ads. It contains 5 columns in total and 400 rows. We drop user id column as it is not relevant. Gender column is categorical. Through 1 hot encoding, we use get_dummies function from pandas to convert categorical values to numerical values. 

To find whether the data is balanced, we use value_counts of the target variable and to also find the total number of classes to classify into. 

## Model Creation/Learning
- Data Collection
- Data Preprocessing
- Input/Output Split
- Split Train and Test Data
- Create model with Train Data
- Evaluate/Test model performance with the Test set
- Save the best model 

## Model deployment
1 - Creating the model (in jupyter notebook)
2 - Saving the model (using pickle, save the finalized model and perform pickle dump which will result in a .sav file) 
3 - Deploying the model (create new deployment notebook to call on and open the saved model) 

## Evaluation Metric Results
-Confusion matrix is imported and evaluated with classification report
- Achieved an accuracy of 0.84 with default NB, Gaussian NB gave 0.90 accuracy, multinomial NB gave 0.63 accuracy , Bernoulli NB gave 0.63 accuracy, categorical NB gave 0.84 accuracy and complement NB gave 0.51 accuracy 



# 7. GRID search with classification 
- README file included as part of this folder for the hands-on project



# 8. Capstone Assignment on Classification to predict chronic kidney disease 
- README file included as part of this folder for the hands-on project

