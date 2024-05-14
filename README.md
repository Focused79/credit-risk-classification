# Module 20 Report

## Overview of the Analysis

* The goal in constructing a supervised learning model was to determine the creditworthiness of loan applicants. A Logistical Regression Model was trained and tested through subsets of the original data. The initial dataset was seperated for the 'y' (dependent) label. The 'y' label was the output in binary form, where '0' was a healthy loan applicant and '1' was a risky loan applicant. Meanwhile, the 'x' dataframe, made up of independent variables, was created by dropping the dependent variable column, 'loan_status." The remaining features included in 'x' are the following: 'loan_size', 'interest_rate','borrower_income','debt_to_income','num_of_accounts','derogatory_marks', and 'total_debt'. 

* The model was trained on a subset of x (x_train) and y (y_train). Then the model was was tested for the accuracy of its predictions by providing the x_test subset, whereby the model would predict test outcomes (y). 

## Results 

The logistic regression model performed exceptionally well when predicting categorical outcomes of '0" (healthy) and '1' (risky). 

* The precision outcome for the Healthy loan applicant was perfect, at 100-percent (rounded at two decimal points). The Risky loan applicant category was slightly worse at 87- (rounded at two decimal points). 
* Recall for the Healthy category was once again perfect, coming in at 100-percent (rounded at two decimal points). 
* The weighted combinations of both the Healthy and Risky categories (f1) were also highly accurate, coming in at 100% and 91-percent (both rounded at the two decimal point), respectively. 
* The collective accuracy was 99-percent. 

Overall, the logistic regression model excelled better with predicting the Healthy loan status than the Risky loan status; nevertheless, the model's achievement was outstanding overall. Given the result of the model's predictions, I recommend that the Logistical Regression model be utilized for the analysis. 

## Resources used in module:
1. Class lectures/slides.
2. Class activities. 

