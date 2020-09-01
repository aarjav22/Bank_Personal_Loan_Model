# Bank Loan Modelling

## The classification goal is to predict the likelihood of a liability customer buying personal loans.
&nbsp; &nbsp; &nbsp; &nbsp;

## Table of Contents

1.	Introduction
2.	Python libraries
3.	The problem statement
4.	Classification Algorithm Used
5.	Independent and dependent variable
6.	Interpretation and Conclusion


&nbsp; &nbsp; &nbsp; &nbsp;

## 1.	Introduction

This case is about a bank (Thera Bank) which has a growing customer base. Majority of these customers are liability customers (depositors) with varying size of deposits. The number of customers who are also borrowers (asset customers) is quite small, and the bank is interested in expanding this base rapidly to bring in more loan business and in the process, earn more through the interest on loans. In particular, the management wants to explore ways of converting its liability customers to personal loan customers (while retaining them as depositors). A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over 9% success. This has encouraged the retail marketing department to devise campaigns to better target marketing to increase the success ratio with a minimal budget.

The department wants to build a model that will help them identify the potential customers who have a higher probability of purchasing the loan. This will increase the success ratio while at the same time reduce the cost of the campaign.
&nbsp; &nbsp; &nbsp; &nbsp;

## 2.	Python libraries

 •	Numpy

 •	Pandas

 •	Matplotlib

 •	Seaborn

 •	Scikit-Learn

&nbsp; &nbsp; &nbsp; &nbsp;

## 3.	The problem statement

The main aim of this model is to predicting the way to explore ways of converting its liability customers (depositors) to personal loan customers (while retaining them as depositors) using some continous and discrete variable data. Finding relationship or dependency of Personal Loan on attrubutes like Income, Age ,Experience etc.

&nbsp; &nbsp; &nbsp; &nbsp;

## 4.	Classification Algorithm Used
  •	LogisticRegression

  •	DecisionTreeClassifier

  •	RandomForestClassifier

  •	SVC

  •	KNeighborsClassifier
&nbsp; &nbsp; &nbsp; &nbsp;

## 5.	Independent and Dependent Variables

### Independent variable

Independent or Input variable (X) = Feature variable = Predictor variable

The following are the independent variable:-

  1.  ID	       : Customer ID							
  2.  Age	       : Customer's age in completed years							
  3.  Experience : years of professional experience							
  4.  Income	   : Annual income of the customer ($000)							
  5.  ZIPCode	   : Home Address ZIP code.							
  6.  Family	   : Family size of the customer							
  7.  CCAvg	Avg. : spending on credit cards per month ($000)							
  8.  Education	 : Education Level. 1: Undergrad; 2: Graduate; 3: Advanced/Professional							
  9.  Mortgage	 : Value of house mortgage if any. ($000)														
  10. Securities Account	: Does the customer have a securities account with the bank?							
  11. CD Account : Does the customer have a certificate of deposit (CD) account with the bank?							 
  12. Online	   : Does the customer use internet banking facilities?							
  13. CreditCard :Does the customer use a credit card issued by UniversalBank?							


### Dependent variable

Dependent or Output variable (y) = Target variable = Response variable

The following is the dependent variable:-

  1. Personal Loan :Did this customer accept the personal loan offered in the last campaign?

&nbsp; &nbsp; &nbsp; &nbsp;

## 6.	Interpretation and Conclusion
                                f1-Score              Accuracy Score

•	LogisticRegression              68%                    94%    

•	DecisionTreeClassifier          91%                    98%

•	RandomForestClassifier          91%                    98%

•	SVC                             83%                    97%

•	KNeighborsClassifier            78%                    96%

Among the 5 models that we have implemented DecisionTreeClassifier and RandomForestClassifier gives the same and best F1 Score and accuracy score with almost accuracy of 98% and F1-Score of 91%

&nbsp; &nbsp; &nbsp; &nbsp;
