# Challenge_20 Assignment

## Overview of the Analysis

The purspose of this analysis is to see how accurate this computer learning model is at predicting the likelihood of healthy loans and high risk loans. 

First, the computer model is given lending data which includes the borrower's income, total debt and the loan size in order to predict which loans are healthy and which loans are high-risk, as shown by either a '0' or a '1' in the loan_status column. 

The loan outcomes data was set to variable 'y' and the rest of the data was set as variable 'X'. Then the data was split into a training dataset to train the computer model and testing datasets to test the computer model for accuracy. Next a confusion matrix was applied to the data to find the accuracy of the model, including the precision of the data, how many of the data points predicted to have a healthy loan really did have a healthy loan, and the recall of the data, how many people who were predicted to have a healthy loan actually do have a healthy loan. 

## Results


### Healthy Loans - Accuracy, Precision, and Recall:
  * Accuracy - 100%
  * Precision - 100%
  * Recall - 99% 
  
 The model identified the healthy loans with high levels of accuracy, precision, and recall. But because over 95% of the loans are healthy loans, it is easier for the model to get a high level of accuracy when trying to guess which loans are healthy. 


### High Risk Loans - Accuracy, Precision, and Recall:
  * Accuracy - 88%
  * Precision - 85%
  * Recall - 91%

The model also did well in predicting which loans would be risky and also had high levels of accuracy, precision, and recall, though not nearly as high as the healthy loan percentages. Because the high risk loans only make up a little over 3%, they are harder to accurately predict than the healthy loans. 


## Summary

Because this model has high levels of accuracy, precision, and recall in predicting both healthy and risky loans I would recommend this model. Even though the model is less effective at predicting the high risk loans, it still has an accuracy of 88%, which is still fairly high. 

