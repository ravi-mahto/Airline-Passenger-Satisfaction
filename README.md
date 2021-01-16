# Airline-Passenger-Satisfaction
## Table of Content
* Overview
* About Dataset
* Objective
* Data cleaning
* Exploratory Data Analysis
* Data Preprocessing 
* Model Selection
* Model Evaluation
* Conculusion

## Overview
This is a classification supervised machine learning project
## Data Dictionary

| Variable | Definition |
| -------- | ---------- |
| Gender: Gender of the passengers (Female, Male) |
| Customer Type: The customer type (Loyal customer, disloyal customer) |
| Age: The actual age of the passengers |
| Type of Travel: Purpose of the flight of the passengers (Personal Travel, Business Travel) |
| Class: Travel class in the plane of the passengers (Business, Eco, Eco Plus) |
| Flight distance: The flight distance of this journey |
| Inflight wifi service: Satisfaction level of the inflight wifi service (0:Not Applicable;1-5) |
| Departure/Arrival time convenient: Satisfaction level of Departure/Arrival time convenient |
| Ease of Online booking: Satisfaction level of online booking |
| Gate location: Satisfaction level of Gate location |
| Food and drink: Satisfaction level of Food and drink |
| Online boarding: Satisfaction level of online boarding |
| Seat comfort: Satisfaction level of Seat comfort |
| Inflight entertainment: Satisfaction level of inflight entertainment |
| On-board service: Satisfaction level of On-board service |
| Leg room service: Satisfaction level of Leg room service |
| Baggage handling: Satisfaction level of baggage handling |
| Check-in service: Satisfaction level of Check-in service |
| Inflight service: Satisfaction level of inflight service |
| Cleanliness: Satisfaction level of Cleanliness |
| eparture Delay in Minutes: Minutes delayed when departure |
| Arrival Delay in Minutes: Minutes delayed when Arrival |
| Satisfaction: Airline satisfaction level(Satisfaction, neutral or dissatisfaction |

1. __Weekly Demand data (train.csv)__: Contains the historical demand data for all centers, test.csv contains all the following features except the target variable.

| Variable | Definition |
| -------- | ---------- |
| id | Unique ID |
| week | Week No |
| center_id | Unique ID for fulfillment center |
| meal_id | Unique ID for Meal |
| checkout_price | Final price including discount, taxes & delivery charges | 
| base_price | Base price of the meal |
| emailer_for_promotion | Emailer sent for promotion of meal |
| homepage_featured	Meal | featured at homepage |
| num_orders | (Target) Orders Count |


| Variable | Definition |
| -------- | ---------- |
| Gender: Gender of the passengers (Female, Male) |
| Customer Type: The customer type (Loyal customer, disloyal customer) |
| Age: The actual age of the passengers |
| Type of Travel: Purpose of the flight of the passengers (Personal Travel, Business Travel) |
| Class: Travel class in the plane of the passengers (Business, Eco, Eco Plus) |
| Flight distance: The flight distance of this journey |
| Inflight wifi service: Satisfaction level of the inflight wifi service (0:Not Applicable;1-5) |
| Departure/Arrival time convenient: Satisfaction level of Departure/Arrival time convenient |
| Ease of Online booking: Satisfaction level of online booking |
| Gate location: Satisfaction level of Gate location |
| Food and drink: Satisfaction level of Food and drink |
| Online boarding: Satisfaction level of online boarding |
| Seat comfort: Satisfaction level of Seat comfort |
| Inflight entertainment: Satisfaction level of inflight entertainment |
| On-board service: Satisfaction level of On-board service |
| Leg room service: Satisfaction level of Leg room service |
| Baggage handling: Satisfaction level of baggage handling |
| Check-in service: Satisfaction level of Check-in service |
| Inflight service: Satisfaction level of inflight service |
| Cleanliness: Satisfaction level of Cleanliness |
| eparture Delay in Minutes: Minutes delayed when departure |
| Arrival Delay in Minutes: Minutes delayed when Arrival |
| Satisfaction: Airline satisfaction level(Satisfaction, neutral or dissatisfaction |
| id | Unique ID |
| week | Week No |
| center_id | Unique ID for fulfillment center |
| meal_id | Unique ID for Meal |
| checkout_price | Final price including discount, taxes & delivery charges | 
| base_price | Base price of the meal |
| emailer_for_promotion | Emailer sent for promotion of meal |
| homepage_featured	Meal | featured at homepage |
| num_orders | (Target) Orders Count |
