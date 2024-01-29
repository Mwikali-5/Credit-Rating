# A classification model to predict whether a customer will default on their loan based on their credit rating

![pexels-engin-akyurt-1552617](https://github.com/Mwikali-5/Credit-Rating/assets/117146053/394dbb77-10d0-460c-a2b3-ebef6255f066)

## Overview
This project aims to predict whether a customer will default on their loan based on their credit score using different models. The dataset is obtained from a banking company that deals with loans.

## Research Question
Build a classifier model to predict whether a customer will default or not based on their credit rating.

## Specific Objectives
* To determine which features detemine if a customer will default or not default
* To increase the recall score to minimize false negatives

 ## Data Understanding
### Data Source
The dataset used in this project was provided by the company.
### Data Description
The data contains 1000 rows and 32 columns. The columns cointain both numerical and categorical data.
### Data Preparation
The data was checked to ensure it was in useable form. This was done by checking duplicates, null values and outliers.

## Explanatory Data Analysis
### Credit Rating Status
![credit rating score](https://github.com/Mwikali-5/Credit-Rating/assets/117146053/a1d7189c-b92b-4f1c-9b79-6788d3870a84)

### Credit Amount 
![credit amount](https://github.com/Mwikali-5/Credit-Rating/assets/117146053/057712db-7939-429d-b568-b076ddf9edaa)

## Modelling
Baseline model was constructed using logistic regression and the output displayed.
The baseline model had a relatively good metric with an accuracy of 75% and a recall score of 88%. Other models were fitted to see if the metrics would improve. They included Random Forest and Gradient Boost.

The Gradient Boost Classifier was the best model overall since it had the highest recall score of 90%.

## Conclusion
1. The initial goal of achieving 75% accuracy is achieved by all the models that were fitted.
2. Gradient Boost Classifier model provides the highest accuracy score of all the models of 78% and a recall score of 90%.
3. All features play an important role in determining the credit rating.

## Recommendations 
1. The company should focus on skilled employees or officials

2. The company should perform more checks before giving credit to people with no credit history and avoid giving people with existing credit more credit at the same bank.

3. Market more to people who have been employed for more than two years since they have a lower default rate.

4. Market more to people with savings account as they have a lower default rate.

5. The lower the amount, the higher the default rate

6. The shorter the duration of credit in months that is ten months or less, the higher the likelihood of getting a good credit rating.
Avoid giving credit to people who pay back after a long duration of 24 months or more.

7. Younger customers have a high default rate as compared to their older counterparts. Market credit to people between the ages of 35 to 55 years as they have good credit rating.
Perform mre checks before giving credit to people above 55 years.

## Repository Guide
The notebook that contains the project can be found [here](https://github.com/Mwikali-5/Credit-Rating/blob/main/Credit_Loan.ipynb)





