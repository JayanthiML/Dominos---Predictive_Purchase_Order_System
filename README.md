# Dominos – Predictive Purchase Order System

## Overview
This project focuses on building a **Predictive Purchase Order System** for Dominos using historical sales data.  
The goal is to **forecast future pizza sales** and automatically generate an **optimized ingredient purchase order**, helping Dominos reduce waste, avoid stockouts, and improve inventory management.

The project demonstrates a real-world application of **data science, time series forecasting, and business decision-making** in the food service industry.

---

## Objectives
- Forecast future pizza sales using historical data
- Analyze sales trends, seasonality, and demand patterns
- Predict ingredient requirements based on forecasted sales
- Generate an efficient purchase order for inventory planning
- Support data-driven decision-making in supply chain management

---

## Project Structure 
├── 1_prep_for_train.ipynb # Data cleaning and preprocessing  
├── 2)_EDA.ipynb # Exploratory Data Analysis  
├── 3)_Models_Dominos.ipynb # Model selection and experimentation  
├── 4)_Train_Forecast_Dominos.ipynb # Training, forecasting & purchase order generation  
├── README.md  

---

## Methodology

### 1) Data Preprocessing
- Handled missing and inconsistent values
- Ensured proper formatting for time series analysis

### 2) Exploratory Data Analysis (EDA)
- Identified sales trends and seasonality
- Analyzed demand by pizza category and time period
- Visualized patterns using plots and charts

### 3) Feature Engineering
- Created time-based features (day, week, month)
- Incorporated sales patterns and historical demand signals

### 4) Model Building & Evaluation
- Implemented time series forecasting models such as:
  - ARIMA / SARIMA
  - Prophet
  - Long Short Term Memory (LSTM)
  - Regression-based approaches
- Evaluated model performance using **MAPE (Mean Absolute Percentage Error)**

### 5) Purchase Order Generation
- Forecasted pizza sales for the upcoming week
- Calculated ingredient requirements using ingredient mapping
- Generated a detailed purchase order for inventory planning

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Time Series Forecasting Models (ARIMA / SARIMA / Prophet/ LSTM)
