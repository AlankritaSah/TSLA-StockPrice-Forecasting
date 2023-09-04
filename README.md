# TSLA-StockPrice-Forecasting
Tesla Stock Price Prediction using FBProphet forecasting tool

# Dataset
The dataset used in this project is Tesla stocks history (01 September 2022 - 01 September 2023). The real-time data is available at [Yahoo finance](https://finance.yahoo.com/quote/TSLA?p=TSLA&.tsrc=fin-srch) which can be downloaded for free.

# Install
    Supported Python version
         - Python version used in this project: 3.0+
    Runtime environment
         - GPU

## Libraries used
* **Pandas** - For smooth working and transformation of dataframe.
* **Plotly** - For creating high level data visualizations that comes handy.
* **FBProphet** - For carrying out the Time Series Forecasting.

# Code
This project has been done in Google Colab and then the evaluation is done by using Google Sheets.

## Steps:
1. I imported the dataset & explored it using various Python inbuilt function that gave the statistical description of the data like the **5 Number Summary** and other descriptive features.
2. Then I did the visualization of the dataset using **plotly express** and visualized the historical performance of Tesla
3. The next step is to prepare the data to be fed into the forecasting model.
4. Created **Facebook Prophet Model** which carry out the forecasting.
5. Carried out the forecasting for 30 days time period.
6. Downloaded the Forecast data to do further evaluation of the next 30 days in **Goggle Sheet** which can be accessed [here](https://docs.google.com/spreadsheets/d/1HcbhNFkfTJBETnIBkcB0QM0Db9TSXfh7kevnMgPqlUY/edit?usp=sharing).





