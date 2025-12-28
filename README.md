# Short-Term Electricity Demand Forecasting and Resource Allocation

## Overview
This project focuses on forecasting short-term electricity demand and optimizing electricity allocation using machine learning and linear programming techniques. The study was conducted as part of my MSc Business Statistics program.

## Problem Statement
Efficient electricity distribution requires accurate demand forecasting. This project aims to predict short-term electricity demand and optimize resource allocation during shortage scenarios.

## Dataset
- Hourly electricity demand data
- Countries: Germany, France, Spain
- Source: Open Power System Data (OPSD)

## Methodology
### Demand Forecasting
- Data preprocessing and time-series handling
- Feature engineering (lag features, rolling statistics, time-based features)
- Machine learning models used:
  - Random Forest
  - XGBoost
  - LightGBM

### Optimization
- Linear Programming model for electricity allocation
- Allocation strategies:
  - Proportional allocation
  - Priority-based allocation

## Tools & Technologies
Python, Pandas, NumPy, Scikit-learn, XGBoost, LightGBM, Linear Programming (PuLP)

## Results
XGBoost provided the best forecasting accuracy. Optimized electricity allocation reduced unmet demand compared to baseline allocation.

## Academic Note
This is an academic project completed as part of the MSc Business Statistics program at VIT Vellore.

