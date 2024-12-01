# Fraud-Detection-in Electricity-and-Gas-Consumption
CS3244 Project Group 9 AY24/25 Semester 1

Welcome to the Fraud-Detection-in Electricity-and-Gas-Consumption repository! We are a group of NUS students embarking on a Machine Learning Project to conduct Fraud Detection of electricity and gas consumption.

## Background
The Tunisian Company of Electricity and Gas (STEG) is a public and a non-administrative company, it is responsible for delivering electricity and gas across Tunisia. The company suffered tremendous losses in the order of 200 million Tunisian Dinars due to fraudulent manipulations of meters by consumers.

## Flowchart
As not much information was provided on the dataset and its variables, we employed relevant domain knowledge where possible, along with our findings through exploratory data analysis to make assumptions about the variables. After the first preprocessing step, we then performed feature engineering and resampling via Synthetic Minority Oversampling Technique (SMOTE) to address imbalances in our target class. After which, we experimented with different models, namely K-Nearest Neighbours (KNN), Decision Trees, Support Vector Machines (SVM), Logistic Regression, Naive Bayes and Neural Networks to determine which model might best allow for effective fraud detection. 

## Requirements
Do ensure your system or environment has the following dependencies installed as in requirements.txt

## Scripts
You may refer to the following notebooks as per the flowchart:
1. Exploratory Data Analysis and Cleaning (data_cleaning_and_EDA.ipynb)
2. Feature Engineering & SMOTE (resampling.ipynb)
3. K-Nearest Neighbours (kNN model.ipynb)
4. Decision Trees (DT Classifier model.ipynb & DT Continuous Output Model.ipynb)
5. SVM (SVM.ipynb)
6. Logistic Regression (logreg model.ipynb)
7. Naive Bayes (naivebayes.ipynb)
8. Neural Network (NeuralNetworks.ipynb)

## Datasets (finalised_datasets)
1. data: raw data
2. cleaned_data: cleaned data after EDA
3. transformed_data: finalised dataset after feature engineering, including train & test data
4. smote_train_data: resampled train data after splitting into 5 folds