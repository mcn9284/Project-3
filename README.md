# __Vaccine Drivers: Predicting Vaccination Uptake__
## Table of Contents

* [Overview](#overview)
* [Business Problem](#Business-Problem)
* [Results and Analysis](#Results-and-Analysis)
* [Future Directions](#Future-Directions)


## Overview
The goal of this project is to develop a predictive classification model for who receives and does not receive the pandemic H1N1 vaccine. The data used comes from the U.S. Department of Health and Human Services (DHHS) and the National Center for Health Statistics.

Starting with a baseline model, we make use of a number of different classification algorithms, selecting the best one to then tune iteratively. The resulting model is then used for prediction and our recommendations based thereon.


## Business Problem
As shown by the ongoing Coronavirus pandemic, the need for public acceptance of emergency health direction--such as getting vaccinated--is often met with an obstinate and suspicious populace.
If we had a means of predicting who or what kind of person is likely to resist vaccination, we might be able to more effectively target our public relations and outreach campaigns.
Here we develop a predictive model to help elucidate who is likely to not get an h1n1 vaccination and present our results to a local government agency (such as a public health department) concerned with promoting vaccination during pandemic events.


## Results and Analysis
### Classification Modeling and Results (Test AUC)
•	Logistic Regression:  0.8201
•	Support Vector Machine: 0.8022
•	Decision Tree: 0.8152
•	Random Forest: 0.8190
•	XGBClassifier: 0.8143
•	GradientBoostingClassifier 
    Before Tuning: 0.8286
    After Tuning: 0.8316
    
Using our tuned GradientBoostingClassifier on the unseen test data, 

