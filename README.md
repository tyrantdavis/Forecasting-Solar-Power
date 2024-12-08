# [Building a Univariate Time Series Model](https://nbviewer.org/github/tyrantdavis/Forecasting-Solar-Power/blob/main/SolarPower.ipynb) - Solar Power

Click the link above for a demo.

## Introduction
This project aims to forecast the quantity of electrical energy that will be generated in the forthcoming year from every energy source.

This project will scope, analyze, prepare, plot data, and seek to explain the findings from the analysis.

Here are a couple of questions that this project seeks to answer:

- Has there been a rise in the utilization of solar power energy over the years?      
- When did the most significant surge occur?
- What energy output does the model forecast?



### Scenario
You are employed by a research company within the energy sector. Your assignment involves identifying patterns in electricity generation throughout the nation. Specifically, you aim to predict the amount of electrical energy that will be produced in the next year for each energy source. This information can assist the industry in implementing strategies that properly align with the anticipated demand.

To begin, you will examine the electrical energy produced from solar power, which has gained significant popularity recently. You have gathered data from the U.S. Energy Information Administration (EIA) concerning net electricity generation from solar energy on a monthly basis over the last 50 years. You plan to construct a univariate time series model utilizing ARIMA to estimate how much electrical energy will be generated from solar power in the upcoming year. Ultimately, you intend to broaden your forecasting to include additional power sources for comparative analysis.

**Data Sources:**

- elect_net_gen_solar.csv
- [U.S Energy Information Administration](https://www.eia.gov/)
  

## Project Goals
In this initiative, the viewpoint will be that of a energy industry analyst. The analyst's objective is to forecast the quantity of electrical energy that will be generated next year from each energy source.  As a result, the primary goals will be to understand energy features particualaryly solar energy and its predicted future use and to uncover emerging trends. Several questions will be asked:

- Has there been a rise in the utilization of solar power energy over the years?      
- When did the most significant surge occur?



#### Why use a univariate forecasting algorithm to predict future energy output?
Forecasting is particularly effective at producing numerical predictions from data that exhibits time-related patterns, making it well-suited for this project. The most basic use of forecasting involves a solitary variable that varies over regular time intervals.


## Data
An anonymized dataset that can be used to train the machine-learning model has been found. It is a CSV file containing 591 solor energy records. 


## Conclusions

- Has there been a rise in the utilization of solar power energy over the years?
    - **Yes. Solar power usage followed a seasonal but overall rising trend over the years according to the predictions**.
- When did the most significant surge occur?
    - **.The most significant growth occurring around the mid-2010s**..
- What energy output does the model forecast?
    - **The model indicated that electrical energy generation from solar power would peak in the middle of 2022 at roughly 14,000 GWh, then dip to around 9,000 GWh at the end of the year before rising again in 2023**.
