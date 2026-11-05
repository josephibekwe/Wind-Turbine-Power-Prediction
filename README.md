# <u>Wind-Turbine-Power-Prediction<u>
##**Project Overview**
This Overview contains preliminary data analysis and python code created for a postgraduate Applied Data Analytics dissertation proposal

The propose dissertation is title:
Machine Learning and Deep Learning Models for Wind turbine Power Prediction using SCADA data

This research aims to compare traditional Machine Learning (ML), Deep Learning (DL) algorithms in predicting wind turbine power generation using historical data from Supervisory Control and Data acquisition measurments.

This repository is focused on the dissertation proposal stage and it includes exploratory data analysis (EDA), data quality assessment, and correlation and regression analysis.

**Research Aim and Objectives**
1. Assess the quality of historical wind turbine SCADA data
2. investigate relationships between wind speed and electrical power generation
3. develop regression models to evaluate initial predictive analysis
4. develop machine learning models
5. develop deep learning models
6. compare model performance using R², Mean Absolute Error, and Root Mean Square Error(RMSE)

Objectives 4-6 are planned for the main Dissertation

**Data Description**
The dataset contains historical wind turbine SCADA measurements from January 2006 to March 2020

**Variables**:22
**Observations**: 653,103
**Target Variable**: Power(kW)
**Explanatory variable**: WinsSpeed(m/s)

Other variables include wind direction, generator speed, rotor speed, environmental temperature, and engine temperature.
The dataset also contains minimum, maximum, and standard deviations for each variable.

**Prelimary Exploratory Data Analysis(EDA)**
the initial analysis includes:
-descriptive statistics and data cleaning and data quality assessment
-wind speed distribution time series and boxplots
-wind direction analysis 
-power generation time series and trends
-analysis of relationships between wind speed and power genration

**Preliminary Regression modelling**
-Two baseline regression approaches were used;
-Simple Linear Regression
-Polynomial Regression

Proposed Machine Learning and Deep Learning Models
-Traditional Machine Learning: Random Forest
-Deep Learning: LSTM

**Project Status**
**Current Stage**:
completed:
-Preliminary EDA
-Data quality analysis
-Wind speed vs Power relationship analysis
-linear and polynomial regression baseline 
-initial model evaluation

**Planned**
-Final prepossessing and feature engineering
-Machine Learning model development
-Deep Learning model development
-hyperparameter tuning and validation
-comparative evaluation and dissertation reporting

**AI assistance declaration**
AI tools, including ChatGPT have been used to support learning and troubleshoot python.
the project will include an AI usage log documenting substantive AI assistance and prompts.

**Author**
Student ID: D00252218
Post Graduate Diploma in Applied Data Science

