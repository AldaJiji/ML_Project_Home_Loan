# ML Project - Home Loan Prediction
---

This project is a standard supervised classification task which aims to predict whether a loan would be approved or not. We will use a [dataset](Loan_Home.csv)  containing various attributes such as Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, Loan Status, etc, and obtained from https://www.kaggle.com/datasets/gavincanacam/home-loan-predictions/data

The goal is to perform all the necessary machine learning steps in order to build a predictive model and predict whether or not a loan would be approved.
To achieve this, we employed three different machine learning models : Random Forest Classifier, Logistic Regression, and Support Vector Classifier (SVC). 

## Notebook content

1. Imports and Data Loading + EDA and Visualization
2. Data Cleaning and Data Preparation
3. Create Random Forest Classifier model
Precision: 0.80
Recall: 0.78
F1-Score: 0.75
Accuracy: 0.78

4. Create Logistic Regression model
Precision: 0.80
Recall: 0.78
F1-Score: 0.75
Accuracy: 0.78

5. Create Support Vector Classifier (SVC) model
Precision: 0.82
Recall: 0.79
F1-Score: 0.76
Accuracy: 0.79


Note that during the preprocessing phase:
* Columns 'Self_Employed', 'Female', and 'Male' were removed to test their impact on model performance.
* GridSearchCV was employed to fine-tune model parameters but did not improve the results significantly.


6. Make prediction
Among the models evaluated, the Support Vector Classifier (SVC) achieved the highest accuracy and F1-Score. This model was selected for making predictions for an example input data and the SVC model predicts that the loan will be approved (1)

7. ## Files Included
  - .ipynb Notebook
  - CSV file
