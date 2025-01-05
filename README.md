# Forecasting-Job-Market-Trends


# Overview:

This research project's main goal is to use a variety of machine learning models to forecast the total number of applicants for a given dataset. This prediction can be used in a number of real-world situations where knowing and forecasting the number of applications can help with decision-making, including marketing strategies, admissions, and recruitment.

# Features
# Data preprocessing: 
seperating the data as numerical and categorical data, encoding categorical columns, replacing mean for the specific categorical columns(designation, level, industry), total applications with non-zero taken into consideraion
# Exploratory Data Analysis(EDA)
1.Corelation Heatmap for both numerical and categorical columns
2.Scatter Plot of Employees Count vs Total Applicants
3.histogram for the total applications column
4. count plots for 'work_type', 'involvement',  'level',  'State'
# Meachine Learning Models
1.Random Forest Regression(optimized with GridsearchCV)
2.Gradient Boosting(optimized with GridsearchCV)
3. XG Boost(optimized with GridsearchCV)
4.Support Vector Regression (SVR)(optimized with GridsearchCV)
# Evalution Metrics
RMSE,MAE,R^2
