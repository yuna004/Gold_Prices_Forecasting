# Gold Price & Currency Exchange Analysis

An end-to-end data analysis project focused on exploring the historical relationship between gold prices and the USD/EUR exchange rate from 1979 to 2024. This project utilises R for statistical modelling, trend visualisation, and time series forecasting.

## Overview
The primary goal of this analysis is to understand how gold's value fluctuates in response to currency movements. By leveraging nearly 45 years of historical data, the project identifies long-term trends and cyclical patterns essential for financial decision-making and risk assessment.

## Tech Stack
* **Language:** R
* **Environment:** RStudio / R Markdown
* **Libraries:** `tidyverse`, `ggplot2`, `forecast`, `tseries`, `lubridate`
* **Data Sources:** Historical Gold Spot Prices and USD/EUR monthly exchange rates.

## Key Features
* **Data Preprocessing:** Handled multi-format date parsing and merged disparate datasets (currency vs. commodity prices).
* **Exploratory Data Analysis (EDA):** Visualized price volatility and distribution over four decades.
* **Correlation Analysis:** Investigated the statistical link between the strengthening/weakening of the Euro and the price of Gold.
* **Time Series Modelling:** (Optional: Mention if you used ARIMA/ETS models) Applied forecasting models to predict potential future price ranges based on historical trends.
* **Risk Management:** Identifies periods of high volatility where gold acted as a "safe haven" during currency fluctuations.
* **Macroeconomic Trends:** Highlights the impact of significant economic shifts on global commodity pricing.
* **Accuracy & Validation:** Utilised historical backtesting to ensure the reliability of the trend analysis.

## How to Run

Copy and run the following commands in your R console or terminal:

1. Ensure you have R installed, then install the required packages:
   
```
install.packages(c("tidyverse", "forecast", "tseries", "ggplot2"))
```

2. Open the project in RStudio:

```
open project.Rmd
```
