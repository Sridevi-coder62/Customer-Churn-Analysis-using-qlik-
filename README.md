# Customer Churn Analysis Dashboard

## Overview

This project analyzes customer churn behavior using data analytics, exploratory data analysis (EDA), and interactive dashboarding. The objective was to identify patterns behind customer inactivity, subscription cancellations, and usage decline in order to support retention-focused business decisions.

The project was completed as a team project using Qlik for dashboard development and Python-based analysis for data cleaning and exploratory analysis.

## Problem Statement

Customer churn directly affects revenue, customer lifetime value, and long-term business growth. Many organizations struggle to understand why customers become inactive, request cancellations, or discontinue subscriptions.

This project was designed to:

* identify churned and inactive customers
* analyze usage and subscription behavior
* understand factors influencing churn
* generate business insights for customer retention

## Objectives

* Clean and prepare raw customer data for analysis
* Perform exploratory data analysis to identify churn patterns
* Build an interactive dashboard for business users
* Analyze customer activity, subscription behavior, and support interactions
* Provide actionable recommendations to reduce churn risk

## Tools and Technologies

* Qlik
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Dataset Summary

The dataset contains customer subscription and activity information including:

* customer activity history
* subscription tier
* contract type
* monthly charges
* cancellation request flag
* support ticket activity
* account age
* total usage metrics

### Key figures

* Total customers analyzed: 3.53K
* Churned customers: 941

## Project Workflow

### 1. Data Cleaning

Data preprocessing was performed to improve dataset quality before analysis.

Tasks included:

* handling missing values
* removing inconsistencies
* checking data types
* preparing analytical fields for dashboarding

### 2. Exploratory Data Analysis (EDA)

EDA was performed to understand customer behavior and discover important churn indicators.

<img width="1171" height="749" alt="EDA Chrun Prediction" src="https://github.com/user-attachments/assets/38d6a045-4557-4299-85f1-44434510a047" />


Analysis included:

* churn distribution
* feature importance analysis
* correlation heatmap
* usage drop vs churn behavior
* inactivity analysis
* cancellation request analysis

### 3. Dashboard Development

An interactive Qlik dashboard was created to help users explore customer churn from multiple perspectives.

<img width="1600" height="632" alt="Qlik Dashboard  to predict churn prediction" src="https://github.com/user-attachments/assets/201a9b22-adf6-44ef-8278-db6e089295a9" />


## Dashboard Components

### KPI Cards

* Total Customers
* Churned Customers
* Inactive Users

### Visualizations

* Subscription tier distribution
* User activity trend chart
* Cancellation requests vs churn
* Support ticket impact analysis
* Churn pattern scatter plots
* Distribution comparison charts
* Feature importance chart
* Correlation heatmap

### Interactive Filters

* Subscription tier
* Contract type
* Payment issue flag
* Cancellation requested
* Inactive flag

## Key Insights

* Customer inactivity showed a strong relationship with churn
* Recent usage decline was one of the most important churn indicators
* Cancellation requests significantly increased churn probability
* Support ticket patterns revealed customer dissatisfaction signals
* Subscription and contract types influenced customer retention behavior

## Business Recommendations

Based on the analysis, the following actions were recommended:

* implement proactive monitoring for inactive users
* trigger early engagement campaigns for usage decline
* monitor cancellation requests as high-risk signals
* improve customer support response quality
* build retention strategies based on subscription behavior

## Outcome

The project demonstrated how business intelligence and exploratory analytics can be combined to identify churn risk, improve customer understanding, and support data-driven retention strategies.

## Team Project

This project was completed as a collaborative team effort involving analytics, data preparation, exploratory analysis, and dashboard development.
