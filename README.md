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
▪ Problem: Vaccine hesitancy creates financial burden on healthcare system and insurance industry during pandemic

▪ Objective: Lower hesitancy andincrease vaccine uptake as cost-effective means of lowering said burden

▪ Solution: Use predictive modeling to determine who is less likely to get vaccinated, elucidate influencing factors, and target outreach according to recommendations
 

## Results and Analysis
### Classification Modeling and Results (Test Accuracy)
•	Logistic Regression:  0.85
•	Support Vector Machine: 0.84
•	Decision Tree: 0.77
•	Random Forest: 0.84
•	XGBClassifier: 0.84
•	GradientBoostingClassifier 
    Before Tuning: 0.84
    After Tuning: 0.85
    
For each model, our goal was to minimize false positives, since these were the cases that would ultimately fly under the detection radar and remain unvaccinated. False negative cases still ended up vaccinated, so their presence was not quite as much of a detriment to our overall goal of increasing vaccine uptake. 

## Recommendations

• Work with hospitals and doctors in network to develop effective dialogue regarding the importance of getting vaccinated

• Social media campaigns to drive home the seriousness of illness, the effectiveness and safety of vaccination.

• Cost saving offers for insured, no-cost for uninsured
