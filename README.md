# Gradient Boosting for Employee Turnover Prediction

## Overview

The goal of this project is to create a model that allows a company's HR department predict when employees are likely to leave the company. This phenomena could be caused by the employee either being laid off or voluntarily quitting and it will be addressed as **turnover**. The data on which to train the model has been collected by the HR department. 

The final model has a 98.29% accuracy and 91.78% recall identifying employees who will leave the company. The most influential factors are:

 - Self reported satisfaction level
 - Time spent working for the company
 - Number of projects the employee contributes to
 - Score of employee's last performance review
 

## Business Understanding

For a company employee turnover is an undesirable but sometimes necessary event. Here a clear division can be done depending on where the decision is made. 

If the company makes the choice to fire a given employee it, most likely, means that they don't reach the company's standards (measured by the evaluation index) and the company may be better off letting them go and looking for new hires. 

The second scenario involves the employee making the choice of leaving. In most cases (within the given data set) employees who voluntarily leave the company could be further divided by their satisfaction index. 
One could imagine that the reasons for someone leaving the company with a low satisfaction index (e.g. not feeling valued or having personal disagreements with other coworkers) and someone also leaving but with high satisfaction (e.g. getting a better offer from a competitor) are different.

These distinctions are important to understand how these factors influence turnover in order for HR to make adjustments to reduce it. 


## Data Understanding

The provided dataset contains 14999 observations on 10 different features. Each observation represents data corresponding to a single employee. This dataset contained a considerable number of duplicates, after removing redundancies the dataset contains individual data of **11991 unique employees** of whom a **16.6% left the company**. 



## Modeling and Evaluation

## Conclusion