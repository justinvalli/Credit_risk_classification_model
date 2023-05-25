# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis is to predict a healthy loan vs a high-risk loan. The financial information contained various clues as to the credit worthiness of a loan, i.e loan size, income, etc. The variables that we were trying to predict were the classification outputs, i.e y variable in the analysis. 

* Logistic regression was used to model the low risk and high risk loans. Then, since there were significantly less high-risk loans than low-risk loans, the data was re-sampled, which yielded much superior results as explained below. 

## Results

* Machine Learning Model 1: Original data
  * Description of Model 1 Accuracy, Precision, and Recall scores.
* The model does a good job in terms of accuracy and precision for the low risk loans, but not as good for high risk loans. Although, both are close to optimal - there is room for improvement. 


* Machine Learning Model 2: Re-sampled data
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  
* After oversampling, the model was able to improve it's ability to classify high risk loans, making it indeed a more reliable model as it lowers any risk of potentially misclassifying a bad loan as a good loan. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, please justify your reasoning.For example:

* The second model performed better. Although there was a slight decrease in precision (0.01) from 0.85 to 0.84 for predicting the good loans, the precision for the high risk loan went up drastically, which is the superior method. 
* In this case, it is more important to predict the 1 class (high-risk loan), because it would be more costly to accept a borrower, thinking that they are low risk, but they turn out to be high risk - as opposed to turning away a borrower that is low risk, thinking they are high risk.
