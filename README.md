# Algorithmic Stock Trading

## About

> [Report](https://github.com/leonz12345/Algorithmic_Stock_Trading/blob/master/Writeup/IDS%20705%20Final%20Report.pdf) <br>
> [Presentation](https://www.youtube.com/watch?v=fZhkb52XwrM&ab_channel=AshishVinodkumar)

Algorithmic trading executes trade orders based on pre-programmed instructions without human intervention. This form of trading has gained increasing popularity. In 2019, 70% of shares traded on the U.S stock exchanges were placed automatically. (Folger, J. 2020, August 28)
Algorithms have many advantages over human traders. It is a completely passive form of earning money. Once the system is built and deployed, humans no longer need to stay in front of the screens. Moreover, algorithms are detached from emotions, allowing trading to be more consistent. For these reasons, we applied machine learning techniques to this trending topic.
Algorithmic trading takes many forms. In the past, people preferred technical indicators. In recent years, the growing field of machine learning has attracted traders to explore more advanced techniques. In this project, we built trading agents using indicators, supervised learning, and reinforcement learning methods to maximize investment.

![Cover_Page](https://github.com/leonz12345/Algorithmic_Stock_Trading/blob/master/Writeup/algorithmic_stock_trading.png?raw=true)

## What We Did

Algorithmic trading has become a popular strategy to trade more successfully with the assistance of computers and machine learning. We evaluate several algorithmic strategies on Apple, Amazon and SPY (S&P 500 Index fund) over a recent time period. We built an agent framework that begins with an initial amount of money, makes buy/sell decisions according to the selected strategy, and reports a return on investment at the end of the test period. We tested our agent with technical indicators (SMA, RSI, MACD, and ADX) and machine learning models (LSTM, ARIMA, Deep Q Learning, and Evolution Strategy). We found that the success of each strategy varies wildly depending on the stock studied and the time period.  Our machine learning methods fared better than our technical indicators in most cases.

## Models Built

**Technical Indicators:**

> SMA: Smooth moving average index

> MACD: Moving average convergence divergence index

> RSI: Relative strength index

> ADX: Average directional movement index

**ML Models**

> ARIMA: AutoRegressive Integrated Moving Average model

> LSTM: Long short-term memory model

> Deep Q Learning: Model-free deep reinforcement learning model

> Evolution Strategy: Deep neural network optimization model

## Results

#### ML Results

![ML_Results](https://user-images.githubusercontent.com/26104722/115993182-4ba7ff80-a5ef-11eb-939d-4270cc69115f.png)


## Technical Indicator Results

![Technical_Indicators_Results](https://user-images.githubusercontent.com/26104722/115993137-126f8f80-a5ef-11eb-8c36-1edf28094201.png)


## Conclusion

The stock market is very volatile and the best algorithmic trading strategy depends heavily on the stock characteristics and time period.  Keeping this in mind, ADX was the best performing technical indicator, on average, across our stocks.  ADX had an average return of 28.7%, which beat the baseline average ROI of 15.6%.  Our machine learning models had higher average performances overall, but the evolution strategy was our best performing machine learning model with an average performance of 74.1%.

As we look forward to areas of future work - we consider model stacking and including more inputs to be most important. A truly successful trading strategy would make use of the strengths of multiple algorithms.  Model stacking would capitalize on each model’s strengths to create better algorithms.  We also only considered opening prices as our training inputs here, and believe including other inputs such as volume or indicators would be beneficial.

## Contributors
Charile Xie: [@Reinhardt-Xie](https://github.com/Reinhardt-Xie)   <br />
Jasmine Young: [@jgy4](https://github.com/jgy4)   <br />
Ashish Vinodkumar: [@ashishvinokumar](https://github.com/ashishvinodkumar)   <br />
Leon Zhang: [@leonz12345](https://github.com/leonz12345)   <br />
