### ⚓ Rock vs Mine Prediction using Machine Learning (Sonar Data)

This project predicts whether an underwater object is a rock (R) or a mine (M) using Logistic Regression trained on the Sonar Dataset.  
The dataset contains 60 sonar signal features collected from submarine sonar experiments.  

The machine learning model learns patterns in these signals to classify unknown objects as either rock or mine.  

### 🎯 Objective

The goal of this project is to build a machine learning system capable of identifying underwater objects based on sonar signal intensities. This is a classic binary classification task.  

### 🚀 Features

✔ Loads and preprocesses Sonar signal data  
✔ Splits dataset into training & test sets  
✔ Trains Logistic Regression model  
✔ Evaluates model performance  
✔ Predicts "Rock" or "Mine" for new data  
✔ Beginner-friendly and easy to understand  


### 📊 Dataset Summary

Dataset: Sonar Signals Dataset (UCI Repository)    
Rows: 208 samples  
Columns: 60 features + 1 label  
Labels:  

R → Rock  
M → Mine  


### 🧠 Machine Learning Approach  

Import required libraries  
Load the sonar dataset  
Split into features (X) and label (Y)  
Train–test split with stratification  
Train a Logistic Regression classifier  
Evaluate accuracy on both train & test data  
Predict rock or mine for new input values  


### 📈 Model Accuracy  

Dataset Accuracy
Training Set	~83.4%  
Testing Set  	~76.1%  


### 🛠 Technologies Used  

Python  
NumPy  
Pandas  
Scikit-Learn  
Jupyter Notebook  


