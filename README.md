# credit-risk-classification
## Overview of the Analysis

For this challenge, I created a model for peer to peer lenders to categorize a loan as healthy or high-risk based on an applicants creditworthiness. The dataset for this model is historical data from a peer to peer lending services company. The predicted value was binary (0/1) indicator where 0 = healthy loan and 1 = high-risk loan. The inputs for this model are: loan size, interest rate, borrower income, debt to income ratio, number of accounts, and number of derogatory marks. To make the model, I created the labels set and then split the dataset into test and train sets. I used the train set to fit a logistic regression model and then saved the predictions in the test set. I calculated the balanced accuracy score, generated a confusion matrix, and made a classification report to assess the performance of the model. I then resampled the data to achieve a more equal number of data points across the labels, and made a logistic regression model along with the same analysis. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * The balanced accuracy was 95.2%
  * The healthy loan precision was 100%, and the high-risk loan precision was 85%
  * The healthy loan recall was 99%, and the high-risk loan recall was 91%



* Machine Learning Model 2:
  * The balanced accuracy was 99.4%
  * The healthy loan precision was 100%, and the high-risk loan precision was 84%
  * The healthy loan recall was 99%, and the high-risk loan recall was 99%
  
## Summary

While both models did a fairly good job at predicting loan health, the 2nd model would be more useful for lenders. This is becasue it has a recall of 99% on high-risk loans as opposed to 91% in the 1st model. A high recall on the high-risk loans is very important to ensure that loans are not given out to those without credit worthiness. 
