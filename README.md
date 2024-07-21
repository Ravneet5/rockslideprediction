# **Time Series Prediction Project**

This project aims to predict sensor readings using time series analysis. 
The data is collected from two types of sensors: tiltmeter and crackmeter.
The prediction is made using two models: LSTM and Prophet, and the accuracy of both models is compared.


## **Data**

The project uses sensor readings from 10 tiltmeter sensors and 4 crackmeter sensors. The data is stored in Excel files:

1. **'CM_Combine_Data.xlsx'** : Contains crackmeter data
2. **'TM_Combine_Data.xlsx'** : Contains tiltmeter data

## Requirements
- Python 3.7+
- pandas
- numpy
- scikit-learn
- keras
- matplotlib
- fbprophet
