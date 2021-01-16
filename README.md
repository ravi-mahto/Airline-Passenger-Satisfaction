# Airline-Passenger-Satisfaction
## Table of Content
* Overview
* Data Dictionary
* Objective
* Data cleaning
* Exploratory Data Analysis
* Model Selection
* Model Evaluation
* Conculusion

## Overview
The dataset for this project is attained from Kaggle which contains the data sourced from a survey conducted by airlines on the satisfaction level of passengers/customers based on various factors. The dataset consists of 25 columns. The dataset consists of a column or feature named ‘satisfaction’ which describes the overall satisfaction level of the customer. It has two values, ‘neutral or dissatisfied’ and ‘satisfied’. This satisfaction feature is considered as the label feature since it conveys the overall experience of the customer based on the ratings given for other features. The dataset consists of 103904 and 25976 records in train and test respectively.

## Data Dictionary

| Variable | Definition |
| -------- | ---------- |
| id | Unique ID |
| Gender | Gender of the passengers (Female, Male) |
| Customer Type | The customer type (Loyal customer, disloyal customer) |
| Age | The actual age of the passengers |
| Type of Travel | Purpose of the flight of the passengers (Personal Travel, Business Travel) |
| Class | Travel class in the plane of the passengers (Business, Eco, Eco Plus) |
| Flight distance | The flight distance of this journey |
| Inflight wifi service | Satisfaction level of the inflight wifi service (0:Not Applicable;1-5) |
| Departure/Arrival time convenient | Satisfaction level of Departure/Arrival time convenient |
| Ease of Online booking | Satisfaction level of online booking |
| Gate location | Satisfaction level of Gate location |
| Food and drink | Satisfaction level of Food and drink |
| Online boarding | Satisfaction level of online boarding |
| Seat comfort | Satisfaction level of Seat comfort |
| Inflight entertainment | Satisfaction level of inflight entertainment |
| On-board service | Satisfaction level of On-board service |
| Leg room service | Satisfaction level of Leg room service |
| Baggage handling | Satisfaction level of baggage handling |
| Check-in service | Satisfaction level of Check-in service |
| Inflight service | Satisfaction level of inflight service |
| Cleanliness | Satisfaction level of Cleanliness |
| eparture Delay in Minutes | Minutes delayed when departure |
| Arrival Delay in Minutes | Minutes delayed when Arrival |
| Satisfaction | Airline satisfaction level(Satisfaction, neutral or dissatisfaction |

## Objective
The objective or goal of this project is to guide an airlines company to determine the important factors that influences the customer or passenger satisfaction. Customer satisfaction plays a major role in affecting the business of a company therefore analysing and improving the factors that are closely related to customer satisfaction is important for the growth and reputation of a company.

## Model Selection
For making the model in this data set, I will trying use several classification models namely Logistic Regression, Decision Tree Classifier, Random Forest Classifier and Gradient Boosting Classifier.

## Model Evaluation
Finally, I retrain the chosen model on 70% of the data set (Training Sets), and then evaluate the predictions on 30% of the remaining data set (Test Set). The final evaluation of model performance gives a AUC of 0.993, Recall of 91.2% and Precision of 99.1%.
