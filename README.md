# Trade with Ease

## About
This project is for SC1015 (Data Science and Artficial Intelligence) which focuses on Apple Stock Price data.

Check out our [Project Video] and [Slide Deck](https://github.com/ShubhangamPrasad/Technical-Indicator-Evaluator/blob/main/C126_Team3_JasonHtutShubhangam.pptx)

## Overview
For a detailed walkthrough, please view the source code in this order:
1. Problem Definition
    - [README.md](https://github.com/ShubhangamPrasad/Technical-Indicator-Evaluator#:~:text=1%20hour%20ago-,README.md,-refined%20ML%20models_)

2. Data Preparation
    - [APPL_clean.csv](https://github.com/ShubhangamPrasad/Technical-Indicator-Evaluator#:~:text=3%20days%20ago-,AAPL_clean.csv,-2%20days%20ago)
    - [Data_Cleaning.ipynb](https://github.com/ShubhangamPrasad/Technical-Indicator-Evaluator#:~:text=3%20minutes%20ago-,DataCleaning.ipynb,-8%20hours%20ago) : The Apple Stock Price dataset is cleaned such that it is ready to be used for analysis and modelling
    - [Generating_Tech_Indicators.ipynb](https://github.com/ShubhangamPrasad/Technical-Indicator-Evaluator#:~:text=19%20hours%20ago-,Generating_Tech_Indicators.ipynb,-1%20hour%20ago) : In this notebook, each technical indicator was calculated according to their specific requirements and mathematical formula. these technical indicators are then stored in a dataframe for modellling and analysis.

3. Exploratory Data Analysis/ Visualisation
    - [EDA.ipynb](https://github.com/ShubhangamPrasad/Technical-Indicator-Evaluator/blob/main/EDA.ipynb): Data analysis and visualisation are done here as we see the relationship between the various columns and recognise the volatility and skewness of data. 
    - [BollingerBands.ipynb](https://github.com/ShubhangamPrasad/Technical-Indicator-Evaluator/blob/main/BollingerBands.ipynb)
    - [HeadAndShoulders.ipynb](https://github.com/ShubhangamPrasad/Technical-Indicator-Evaluator/blob/main/HeadAndShoulders.ipynb)
    - [RSI.ipynb](https://github.com/ShubhangamPrasad/Technical-Indicator-Evaluator/blob/main/RSI.ipynb)
    - [KeltnerChannels.ipynb](https://github.com/ShubhangamPrasad/Technical-Indicator-Evaluator/blob/main/KeltnerChannels.ipynb)
    - [MovingAverage.ipynb](https://github.com/ShubhangamPrasad/Technical-Indicator-Evaluator/blob/main/MovingAverage.ipynb)

4. Machine Learning Models
    - [Single_Indicator_Logistic_Regression.ipynb](https://github.com/ShubhangamPrasad/Technical-Indicator-Evaluator/blob/main/Single_Indicator_Logistic_Regression.ipynb): We observe the accuracy and relationship of each indicator in predicting future price movement through the Logistic Regression model.
    - [Multi_Indicator_ML_Models.ipynb](https://github.com/ShubhangamPrasad/Technical-Indicator-Evaluator/blob/main/Multi_Indicator_ML_Models.ipynb): We observe the accuracy of using multiple indicators in predicting future price movement through various ML models. 


## Problem Definition:
With the growing popularity and interest surrounding investment, many have begun investing and trading stocks. However, many lack knowledge in determining when to buy or sell their stocks, and how effective technical indicators truly are in determining future price action.

Hence, we deliberated:
How can we utilise ML to model how effective technical indicators are in determining future price action? Would the use of multiple indicators better help us predict future price action?

To address this, we performed exploratory data analysis and used technical indicators such as Bollinger bands, Head and Shoulders, Moving Average, Relatice Strength Indicator (RSI) and Keltner Channels to train our models. 

## Machine Learning
1. Logistic Regression
2. Decision Trees
3. XGBoost
4. Support Vector Machine (SVM)

## Conclusion
- Accuracies of individual indicators are very low and are not reliable to be used alone 
- Investors should use multiple indicators to predict the price movement and utilise the signals from them to buy/sell stocks
- Indicators are not fool-proof and investors should still practice caution while using them
- XGBoost model had the highest accuracy in using multiple indicators to predict future price movement 

## Contributors
- @ShubhangamPrasad (Prasad Shubhangam Rajesh)
- @htuttttt (Saw Thida Htut)
- @Ebe05 (Jason Ebenezer)

## Learning Outcomes
- Using Logistic Regresstion,Decision Trees, XGBoost and Support Vector Machinese (SVM) to model financial time series data
- Uses and Variations of Technical Indicators

## References
- https://www.investopedia.com/terms/h/head-shoulders.asp
- https://www.investopedia.com/terms/k/keltnerchannel.asp
- https://www.investopedia.com/terms/b/bollingerbands.asp
- https://www.investopedia.com/terms/r/rsi.asp
- https://towardsdatascience.com/
- https://www.investopedia.com/terms/m/movingaverage.asp#:~:text=A%20moving%20average%20is%20a,price%20trends%20for%20specific%20securities.





