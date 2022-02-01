# TEXT CLASSIFIER

## DataSet - Legal Clauses extracted from Credit Agreements
## Targets  - Legal Clauses Type


## Structure of the Project

### 1. Naive Bayes Model 
#### 1. Naive Bayes Step 1 - Pre-Processing Data.ipynb
#### 2. Naive Bayes Step 2 - Training Model.ipynb
#### 3. Naive Bayes Step 3 - Testing the Validation Data and Evaluating the Result.ipynb
#### 4. Naive Bayes Step 4 - Predicting the Output of Given Test Cases.ipynb

### 2. Improving Naive Bayes using HyperParameter Optimization ( GridSearch )

### 3. Comparing the evaluation metric of the Naive Bayes Model with SVM and Decision Tree

### 4. Training Data Folder 
####      Contains Manually Added Training Files as well as files generated during date cleaning - data preprocessing stage

### 5. Testing Data Folder
####     Contains Manually Added Testing Cases File as well as the testing output predictions generated during the testing stage

### 6. Validation Data Folder
####     Contains Manually Added Validation Data and their actual classes files as well as the model predictions files generated during metric              evaluation stage

### 7. Trained Model
####     Contains the probability files generated during the training stage which are later used for prediction purposes

## Environment Requirement
### It is recommended to run this project in Jupyter Notebook Setup
### All the required imports are mentioned in the project files in the Notebook Imports Section


## Getting Started

Add the training CSV Files in the following path
The File Names and paths are as follows - These csv Files Contain only one column( the legal statement)

'Training_Data/Preamble_Training_Data.csv'
'Training_Data/Other_Training_Data.csv'
'Training_Data/Lender_Defaulting_Training_Data.csv'
'Training_Data/Governing_law_Training_Data.csv'
'Training_Data/Indemnification_Training_Data.csv'


Add the validation data and validation class in the following file paths

'Validation_Data/Validation_Statement.csv' ( Contains one column for the statement )
'Validation_Data/Validation_Class.csv' ( Contains one column for the class - please make sure it is written in the correct case i.e First Letter of each word in upperCase and rest are in lowerCase )


Add the testing data in the following path 

TESTING_DATA_PATH = 'Testing_Data/Testing_Data.csv' ( Only one column for the legal Statement )


## Order of Execution

Run the files in the order 
1. Naive Bayes Step 1 - Pre-Processing Data.ipynb
2. Naive Bayes Step 2 - Training Model.ipynb
3. Naive Bayes Step 3 - Testing the Validation Data and Evaluating the Result.ipynb
4. Naive Bayes Step 4 - Predicting the Output of Given Test Cases.ipynb

## Important Files Generated

The Validation Data Prediction would be found in
VALIDATION_PREDICTION_DATA_PATH = 'Validation_Data/Validation_Prediction.csv'

The Testing Data Prediction would be found in
TESTING_PREDICTION_PATH_CSV = 'Testing_Data/Testing_Prediction.csv'
TESTING_PREDICTION_PATH_JSON = 'Testing_Data/Testing_Prediction.json'



