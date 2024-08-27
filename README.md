'''
Introduction-
The energy consumption of urban areas is a critical parameter that 
reflects the city's lifestyle, industrial activity, and overall energy efficiency. 
For regions with varying environmental conditions, like Tetouan city in northern Morocco,
predicting power consumption becomes even more crucial. Accurate forecasting helps in better planning, 
efficient energy distribution, and reducing power outages. This project aims to leverage machine learning 
techniques to predict the power consumption in Tetouan city, considering various environmental factors.

Problem Statement-
Tetouan city is divided into three different distribution networks, 
each representing a specific zone. The power consumption data of these 
zones can vary based on multiple environmental factors such as temperature,
humidity, and wind speed. The challenge lies in accurately predicting the average
power consumption of the city based on these independent variables.
By applying machine learning models, specifically Random Forest Regression, 
XGBoost Regression, and KNN Regression, the goal is to build a robust predictive 
model that can forecast the city's energy demands.

Aim of the Project-
The primary objective of this project is to develop a machine learning model that 
can accurately predict the average power consumption of Tetouan city. 
The model will utilize historical data related to environmental factors and 
power consumption from three different zones. The focus will be on comparing the performance 
of Random Forest Regression, XGBoost Regression, and KNN Regression models to 
determine the most effective approach for predicting power consumption.

Data Variables Description
- DateTime (Feature): The timestamp of the data recorded every ten minutes.
- Temperature (Feature): Continuous variable representing the weather temperature of Tetouan city.
- Humidity (Feature): Continuous variable representing the humidity levels in Tetouan city.
- Wind Speed (Feature): Continuous variable representing the wind speed in Tetouan city.
- General Diffuse Flows (Feature): Continuous variable representing the general diffuse flows.
- Diffuse Flows (Feature): Continuous variable representing the diffuse flows.
- Zone 1 Power Consumption (Target): Continuous variable representing the power consumption in Zone 1 of Tetouan city.
- Zone 2 Power Consumption (Target): Continuous variable representing the power consumption in Zone 2 of Tetouan city.
- Zone 3 Power Consumption (Target): Continuous variable representing the power consumption in Zone 3 of Tetouan city.
'''
