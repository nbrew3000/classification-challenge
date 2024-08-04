# classification-challenge
Create a new repository for this project called classification-challenge. Do not add this homework assignment to an existing repository.

Clone the new repository to your computer.

Inside your local Git repository, add the starter file spam_detector.ipynb from your file downloads.

Push these changes to GitHub or GitLab.

Instructions
This challenge consists of the following subsections:

Split the data into training and testing sets.

Scale the features.

Create a logistic regression model.

Create a random forest model.

Evaluate the models.

Split the Data into Training and Testing Sets
Open the starter code notebook and then use it to complete the following steps.

Read the data from https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csvLinks to an external site. into a Pandas DataFrame.

In the appropriate markdown cell, make a prediction as to which model you expect to do better.

Create the labels set (y) from the “spam” column, and then create the features (X) DataFrame from the remaining columns.

NOTE

Check the balance of the labels variable (y) by using the value_counts function.

Split the data into training and testing datasets by using train_test_split.

Scale the Features
Create an instance of StandardScaler.

Fit the Standard Scaler with the training data.

Scale the training and testing features DataFrames using the transform function.

Create a Logistic Regression Model
Employ your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the scaled training data (X_train_scaled and y_train). Set the random_state argument to 1.

Save the predictions on the testing data labels by using the testing feature data (X_test_scaled) and the fitted model.

Evaluate the model’s performance by calculating the accuracy score of the model.

Create a Random Forest Model
Employ your knowledge of the random forest classifier to complete the following steps:

Fit a random forest classifier model by using the scaled training data (X_train_scaled and y_train).

Save the predictions on the testing data labels by using the testing feature data (X_test_scaled) and the fitted model.

Evaluate the model’s performance by calculating the accuracy score of the model.

Evaluate the Models
In the appropriate markdown cell, answer the following questions:

Which model performed better?

How does that compare to your prediction?

Requirements
To receive all points, your Jupyter notebook file must have all of the following:

Split the Data into Training and Testing Sets 
There is a prediction about which model you expect to do better. 
The labels set (y) is created from the “spam” column. 

The features DataFrame (X) is created from the remaining columns. 

The value_counts function is used to check the balance of the labels variable (y). 

The data is correctly split into training and testing datasets by using train_test_split. 

Scale the Features
An instance of StandardScaler is created. 

The Standard Scaler instance is fit with the training data. 

The training features DataFrame is scaled using the transform function.

The testing features DataFrame is scaled using the transform function. 

Create a Logistic Regression Model
A logistic regression model is created with a random_state of 1. 

The logistic regression model is fitted to the scaled training data (X_train_scaled and y_train). 

Predictions are made for the testing data labels by using the testing feature data (X_test_scaled) and the fitted model, and saved to a variable. 

The model’s performance is evaluated by calculating the accuracy score of the model with the accuracy_score function. 

Create a Random Forest Model 
A random forest model is created with a random_state of 1. 

The random forest model is fitted to the scaled training data (X_train_scaled and y_train). 

Predictions are made for the testing data labels by using the testing feature data (X_test_scaled) and the fitted model, and saved to a variable. 

The model’s performance is evaluated by calculating the accuracy score of the model with the accuracy_score function. 

Evaluate the Models 
The following questions are answered accurately:

Which model performed better? 

How does that compare to your prediction? Chatgpt
