# credit-risk-classification
Module 20 Challenge

** Purpose of the Analysis 
The purpose of the analysis was to train and evaluate a model based on loan risk. We were given a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. 

** About the Data
The data included several predictors of creditworthiness, including: the size of the loan, interest rate, borrower’s income, the debt to income ratio, the borrower’s number of accounts, derogatory marks, and the borrower’s total debt. These were used to predict the status of a loan: whether it would be paid off or defaulted on.  

** Stages of the Machine Learning Process and Methods Used
First, I split the data into training and testing sets. I separated the data into labels and features, and checked the balance of the labels. I instantiated a logistic regression model and fit the model using the training data. Finally, I evaluated the model’s performance by calculating the accuracy score of the model, generating a confusion matrix, and printing the classification report. 
These stages were repeated to predict a logistic regression model with resampled training data. I used the RandomOverSampler module from the imbalanced-learn library to resample the data and ensure that the labels had an equal number of data points. I fit the model with the resampled data and made predictions as in the previous steps. Finally, the performance of the second model was evaluated by the accuracy score, confusion matrix, and classification report.
I compared these three (accuracy score, confusion matrix, and classification report) measures of the model’s performance between both logistic regression models to determine which model would be better for banks to use to reduce their risk in lending money. 

** Files
Files in the repository include the ipynb file with the code, a Resources folder which contains the given csv file dataset, and a Microsoft Word Document with a written analysis of the results and conclusions of this exercise.

** Resources
Resources used for this project include course material, course-provided starter code, collaboration with team members, instructor-provided CSV file, assistance from Tutors, GeeksforGeeks, Towards Data Science, Medium, and Chat GPT.
