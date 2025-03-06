
# Airport Passenger Forecasting using Time Series Analysis

## Overview

This project focuses on forecasting airport passenger traffic using various time series analysis techniques, including ARIMA, SARIMA, Exponential Smoothing, and Moving Average. The goal is to build accurate models to predict future passenger numbers, which can aid in resource planning and operational efficiency for airports.




## Screenshots

![Alt Text](https://github.com/NAMANNIMBLE1/Airport_passengers_forecasting/blob/main/images/Screenshot%202025-03-06%20183820.png)

![Alt Text](https://github.com/NAMANNIMBLE1/Airport_passengers_forecasting/blob/main/images/Screenshot%202025-03-06%20183826.png)

![Alt Text](https://github.com/NAMANNIMBLE1/Airport_passengers_forecasting/blob/main/images/Screenshot%202025-03-06%20184007.png)

![Alt Text](https://github.com/NAMANNIMBLE1/Airport_passengers_forecasting/blob/main/images/Screenshot%202025-03-06%20184015.png)

![Alt Text](https://github.com/NAMANNIMBLE1/Airport_passengers_forecasting/blob/main/images/Screenshot%202025-03-06%20184026.png)

![Alt Text](https://github.com/NAMANNIMBLE1/Airport_passengers_forecasting/blob/main/images/Screenshot%202025-03-06%20184034.png)
## Techniques 

- used ARIMA (AutoRegressive Integrated Moving Average)

- SARIMA (Seasonal AutoRegressive Integrated Moving Average)

- Exponential Smoothing (Holt-Winters)

- Moving Average

- Data Visualization and Preprocessing
## Dataset

The dataset used in this project contains historical passenger traffic data for an airport. It includes:

Date: Timestamp for each observation.

Passenger Count: Number of passengers for the given date.

The dataset is preprocessed to handle missing values, outliers, and to ensure it is suitable for time series analysis.
## Installation

Installation
To run this project, you need the following Python libraries:

pandas
```bash
  pip install pandas
```

numpy
```bash
  pip install numpy 
```

matplotlib
```bash
  pip install matplotlib 
```

statsmodels
```bash
  pip install statsmodels
```

seaborn & plotly 
```bash
  pip install plotly
  pip install seaborn 
```




## Methodology 

Methodology
### Data Preprocessing:

- Handle missing values and outliers.

- Resample the data to a consistent frequency (e.g., monthly).

- Perform stationarity checks and apply transformations if necessary.

### Model Training:

- Split the data into training and testing sets.

- Train ARIMA, SARIMA, Exponential Smoothing, and Moving Average models.

### Model Evaluation:
- Compare the performance of different models.

### Forecasting:

- Generate forecasts for future passenger traffic.

- Visualize the results using plots.

## Authors

- [@NAMANNIMBLE1](https://github.com/NAMANNIMBLE1)

