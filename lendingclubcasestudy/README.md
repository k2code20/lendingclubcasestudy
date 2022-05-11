# Lending Club Case Study

Datasets were collected and processed for further consumption. This included Removing the null values, Duplicates, Imputation, and correction of outliers. 
EDA method used to analyse the datasets very well for the better understanding. This included Univariate, Bivariate, Segmented and Multivariate analysis.
Then, the analysis was visualised clearly. This included Bar plot, box plots, Scatter plot, Stacked plots. 



## Table of Contents
* Objective
* Data Handling
* Data cleaning
* Univariate Analysis
* Bivariate Analysis
* Multivariate Analysis
* Conclusion


## General Information

A firm delivering loan applications to people have defaulters, who does not re-pay their loan. With the help of datasets that has past history of all the loan applicants who defaulted/fully paid/Currently paying applicants and their information, an EDA needed to understand the previous patterns of defaulters so that the firm can be aware of the defaulters on prior.

Datasets Inputs: 
Dataset1 = loan.csv (Contains ample amount of features of the respective individuals taken loan)
Dataset2 = Data_Dictionary.xlsx (Description of the features present in the Dataset1)


## Conclusions
- Data handling showed there are many NULL values, Unnecessary features and Duplicates present.
- Data cleaning done to retrieve the necessary features that are required for analysis 
- Univariate analysis done to understand the individual features over the loan applicants.
	- Result: 14% of the loan applicants are likely to default 
- Bivariate analysis done to understand relationship between features. 
	- Result: Annual inc positively correlated with Loan recoveries
- Multivariate analysis done to understand relationship between multiple factors.

Driving Factors:
annual _inc
funded_amnt_inv
int_rate
term
grade
purpose
addr_state

## Technologies Used
- library - pandas
- library - matplotlib
- library - seaborn

## Acknowledgements
Thanks to upgrad for letting us work with the real world datasets. 


## Contact
Created by [@githubusername] - feel free to contact me!

