# Module-challenge-20

Module assignment 20 - credit-risk-classification

**Credit Risk Analysis Report**:

An overview of the analysis: the purpose of this analysis was to evaluate how logistic regression can predict te credit risk of potential lenders. The target value for analysis is loan_status. All other features in csv such as loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, and total_debt were used to predict target. Value_counts helps us to see the size of the data set before splitting it up into a training and testing set. The purpose was to predict whether a loan would be classified as "healthy" (0) or "high-risk" (1). The target variable, loan_status showed 75036 loans as "healthy" (0) and 2500 loans as "high-risk" (1). 


**The results of the machine learning model**: 

**the accuracy score**:  99%
**the precision score**: 1.00 for '0' (healthy loan) -> had perfect precision, no false positive. 0.84 for `1` (high-risk loan), with some false positive, indicating some healthy loans are incorrectly classified as high-risk. 
**recall score**:  99% for '0' (healthy loan) and 94% for `1` (high-risk loan)


**A summary**: 

The accuracy score from the machine learning model is 99%, excelling at predicting "healthy" (0) with 1.00 perfect precision and high recall. 
For "high-risk" (1), the precision score is lower 0.84, indicating some healthy loans are incorrectly classified as high-risk. 
The model is satisfy if identifying healthy loans is the priority, but need enhancement in high risk loan precision if high risk is more critical. If reducing false positives for high-risk loans is essential, further adjustments or another model may be needed.

