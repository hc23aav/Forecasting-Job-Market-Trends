# Forecasting-Job-Market-Trends


# Overview:

This research project's main goal is to use a variety of machine learning models to forecast the total number of applicants for a given dataset. This prediction can be used in a number of real-world situations where knowing and forecasting the number of applications can help with decision-making, including marketing strategies, admissions, and recruitment.

# Features
# Data preprocessing: 
seperating the data as numerical and categorical data, encoding categorical columns, replacing mean for the specific categorical columns(designation, level, industry), total applications with non-zero taken into consideraion
# Exploratory Data Analysis(EDA)
- Corelation Heatmap for both numerical and categorical columns
- Scatter Plot of Employees Count vs Total Applicants
- histogram for the total applications column
- count plots for 'work_type', 'involvement',  'level',  'State'

# Meachine Learning Models
- Random Forest Regression(optimized with GridsearchCV)
- Gradient Boosting(optimized with GridsearchCV)
- XG Boost(optimized with GridsearchCV)
- Support Vector Regression (SVR)(optimized with GridsearchCV)
# Evalution Metrics
RMSE,MAE,R^2

# Dataset
The Dataset contains following features

**Numerical Columns**
- job_ID
- company_id
- employees_count
- total_applicants    
- linkedin_followers
- details_id

**Categorical Columns**
- designation
- name
- work_type
- involvement
- job_details
- industry
- level
- City
- State


