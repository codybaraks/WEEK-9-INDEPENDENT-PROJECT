# WEEK-9-INDEPENDENT-PROJECT
### Implementing a K-nearest neighbor (kNN) classifier  and a Naive Bayes classifier

**Summary**

# **Overview**

**Performed Exploratory Data Analysis**

Example:

Checking the 

	info

	Size

	Shape

	Viewing top and Bottom info of the set

	Carried out a pandas profiling Report


**Data cleaning**

•	Checking for unique values

•	Duplicated

•	Missing values

•	Outliers

•	Distribution


**Modelling**


Base Modeling

Feature Importance


**Tuning models**

Cross validation
Identified the Best mode

##**Observation**


**Titanic dataset**

Identified outliers in “fare” column

Noted that there more men who survived as compared to women
The that chances of survival compared to not survived is less, meaning the dataset was imbalanced

Shows that the highest number of people who did not survive we in the ages 20 to 30.


About 85 people survived ranging from the age of 20 to 30
People who did not survive were more compared to the ones who did

**Cross Validation**

10-fold cross validation tells us that K=7 results in the lowest validation error.

After parameter tuning
The accuracy score came to 62%
Out of 179 people, 111 where predicted correctly


**Naïve Classifier**

About 391 duplicates where identified
There were no missing values

**Modeling**

A base model for Gaussian resulted in an accuracy score of 82%
A base model for Bernoulli resulted in an accuracy score of 89%

Show that Bernoulli was better
Gaussian recorded an accuracy of about an average of 82% compared to Bernoulli which scored about 88%, seems that the 

Bernoulli classification performed better, predicted 1422 as spam and 190 as not spam

Something to note was that an increase of test size also increased the accuracy score

**Technologies Used**
Python

{MIT License. See below for more details on licensing.}

Copyright (c) {2019} 
