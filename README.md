# Lab-1-Machine-Learning

Student Performance Prediction Model
Overview
This project aims to predict student performance based on factors such as disability status and Index of Multiple Deprivation (IMD) band. The model uses logistic regression to classify students as pass or fail based on these predictors.

Dataset
The dataset used in this project is studentInfo.csv, which contains information about student demographics, disability status, IMD band, and final result (pass or fail).

Setup
To run the code, make sure you have R and the required packages installed:

R
Copy code
# Install required packages
install.packages(c("tidyverse", "tidymodels", "janitor"))
Running the Code
Clone the repository to your local machine.
Ensure that studentInfo.csv is in the project directory.
Open the R script file (student_performance_prediction.R).
Run the code in your R environment.
Workflow
The data is loaded and preprocessed, including feature engineering and splitting into training and testing sets.
A logistic regression model is specified and added to a workflow along with a recipe.
The model is trained using the training data.
The model is evaluated using the testing data to assess its performance.
Results
The final fitted model is evaluated for accuracy, and predictions are collected to analyze model performance.

Files Included
studentInfo.csv: Dataset containing student information.
student_performance_prediction.R: R script file containing code for data preprocessing, modeling, and evaluation.
Contributors
Yeshwanth
