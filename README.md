# Analyzing Customer Churn

## Introduction

## Project Analysis

### Problem Statement

Customer churn is a critical issue for subscription-based businesses, directly impacting revenue and long-term growth. Databel, a fictitious telecom company, is experiencing customer churn, and understanding the drivers behind it is essential. The goal of this project is to leverage Excel to analyze churn data, identify key patterns, and uncover actionable insights to help reduce future churn.

### Objectives

- **Question 1.** What are the main reasons for customer churn in our dataset, and which features are most strongly associated with it?

- **Question 2.** How does churn vary across different age categories ?

- **Question 3.** Among customers with the Unlimited Data Plan, how does churn differ when segmenting their historical data usage into Less Than 5 GB, Between 5 GB and 10 GB, and More Than 10 GB?

- **Question 4.** How does churn relate to customers’ U.S. state of residence and International Plan ownership? What role do customer tenure and payment types (Month-to-Month, One Year, Two Years) play in churn?


### Identify Data Sources

DataCamp Case Study: Analyzing Customer Churn - this is the source

`Cuastomer` table shows specifics for a single users
`Aggregate` shows specific options and how many users using this combination from the offer

### Loading Data Using Power Query

loaded two tables `Customer` `Aggregate` from the excel file containing data from `Databel`

### Data Cleaning

i highlighed duplitates in `Customer ID` column and deleted using Data->Remove Duplicvates but no duplicates was found

### Descriptive Statistics

how many users, 

### Data Exploration

Q1
I had `Churn Label` in `Customer` containing `Yes`/`No` i added `Churned` column having 0 if no and 1 if yes i helps for analysis all my added columns i highlighted in a blue/green background


Q2



Q3



Q4

### Create Dashboards