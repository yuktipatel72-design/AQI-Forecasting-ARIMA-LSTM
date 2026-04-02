# AQI-Forecasting-ARIMA-LSTM
Comparative AQI prediction and forecasting using ARIMA and LSTM models with Power BI dashboard.

## Overview
This project analyzes and forecasts Air Quality Index (AQI) using ARIMA and LSTM models. It compares model performance, evaluates accuracy, and presents results in a Power BI dashboard.

## Objectives
- Perform exploratory data analysis on AQI dataset
- Build ARIMA and LSTM models for prediction and forecasting
- Compare models using RMSE, MAE
- Provide a 20-day forecast horizon
- Visualize results in an interactive Power BI dashboard

## Repository Structure
- `AQI_Project.ipynb` → Notebook with AQI forecasting code
- `AQI_Dataset.csv` → Dataset used for training and testing
- `AQI_Dashboard.pbix` → Power BI dashboard file
- `README.md` → Project documentation
- `Requirements.txt` → Python dependencies

## How to Run
- Download this repository  
- Install dependencies: `pip install -r Requirements.txt`  
- Open and run `AQI_Project.ipynb` in Jupyter/Colab/VS Code  
- Open `AQI_Dashboard.pbix` in Power BI Desktop to explore visuals

## Key Insight
LSTM delivers more accurate AQI predictions and forecasts by effectively capturing nonlinear patterns, whereas ARIMA struggles to adapt to complex variations, achieving lower RMSE and MAE compared to ARIMA.
