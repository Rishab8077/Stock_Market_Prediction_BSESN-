# Stock Market Prediction using Numerical and Textual Analysis

### In this project main aim was to create a hybrid model for stock price/performance prediction using numerical analysis of historical stock prices and sentimental analysis of new headlines.

For Reference BSESN stock price dataset was taken from finance.yahoo.com. The Dataset has total 252 entries starting date from 2019-12-17.Dataset has total 7 columns (Date, Open, High, Low, Close, AdjClose, Volume). For analysing only Close and Data column was choosen<br>

## Graph for moving average (close)
![img1](https://user-images.githubusercontent.com/72625053/138659169-891982d2-10c4-4b08-9299-2117298704cc.png)


### For Textual Analysis India-News-Headlines dataset was taken having 3424067 entries from 2001-01-02 .

## Conclusion
Among different algorithm AdaBoostRegressor was giving least error. Top 3 best performing ALgorithm. <br>
Mean Squared Error <br>
RandomForest = 0.0520 <br>
XGBoost = 0.058 <br>
AdaBoost = 0.0514 <br>
