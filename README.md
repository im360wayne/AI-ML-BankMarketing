# Predicting Direct Marketing Acceptance Rates in Retail Banking 

**OVERVIEW**

Real-world data from a Portuguese banking institution was used with machine learning techniques to predict the probability of a telephone marketing campaign recipient accepting the campaign, defined as signing up for the bank product and making a deposit.

Several machine learing classifiers are compared. They are K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines.  

The source of this dataset is the UCI Machine Learning repository [link](https://archive.ics.uci.edu/ml/datasets/bank+marketing).

## Executive Summary

Various Machine learning techniques were used to determine which types of customer are most likely to accept a telephone marketing campaign and sign up for an account. 

Various computer models were evaluated based on their ability to accuractely predict a yes or no acceptance result. Data from 17 campaigns over the time period of May 2008 to November 2010 was used. A dataset of 38,488 was entries was used filtering out any records with incomplete data. 

An analysis of the models provided insight on specific customer attributes that contributed to predicting a positive response to the a marketing contact. 

**Top Customer Attributes Accepting a Marketing Contact**
* Job: Student
* Job: Retired	
* Job: Unemployed
* Age
* Education: University Degree
* Marital Status: Single


The complete list of customer attributes in priority order is available for download here: 
<a href="top_customer_acceptance_attributes_sorted.csv">top_customer_acceptance_attributes_sorted.csv</a>

**Action Items and Next Steps**
1. The financial instituation should review the sorted list of customer attributes that contributed to acceptance rates and create targed marketing campaigns that focues on these groups.
2. As the recommendations are only as good as the data used, the bank to continuously provide updated marketing campaign and acceptance data for re-evaluation. 
 

 **Full Technical Analysis**

The full Machine Learning technical analysis can be found in the Juypter Notebook here:
<a href="BankMarketing.ipynb">BankMarketing.ipynb</a>
