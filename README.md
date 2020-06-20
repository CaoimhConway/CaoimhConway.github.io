# Data science portfolio by Caoimh Conway

This portfolio contains a series of data analyses, visualizations, machine learning algorithms, statistical models and data structures that I have created.

## [Stock Market Portfolio Generator](https://nbviewer.jupyter.org/github/CaoimhConway/StockMarketPortfolioGenerator/blob/master/StockMarketPortfolioGenerator.ipynb)
[Github repo](https://github.com/CaoimhConway/StockMarketPortfolioGenerator/blob/master/StockMarketPortfolioGenerator.ipynb)

In this notebook I clean, organize, and analyze company fundamentals data in **R** in order to train a model that recommends a portfolio of 12 company investments that maximizes 12-month return of an overall $1,000,000 investment made at the end of quarter 4 of year 2018.


## [Neural Network Flexibility](https://github.com/CaoimhConway/NeuralNetworkFlexibility)

I created this project to demonstrate the flexibility of neural networks in **Python** by using the same neural network to identify hand written digits, identify the language of a text, and to model real number functions, such as sin(x).


## [Double Ended Queue](https://github.com/CaoimhConway/DoubleEndedQueue)
This is a **Java** implementation of a double ended queue, which is usually referred to by its irregular acronym, Deque (pronounced "Deck").  Deques are sequence containers with dynamic sizes that can be expanded or contracted on both ends (either its front or its back). 

## [Investigating Food Safety Data](https://nbviewer.jupyter.org/github/CaoimhConway/InvestigatingFoodSafetyData/blob/master/Investigating%20Food%20Safety%20Data.ipynb)
[Github repo](https://github.com/CaoimhConway/InvestigatingFoodSafetyData)

In this notebook I examine data collected by the Department of Public Health in San Francisco, and demonstrate multiple methods for data manipulation, visualization, imputation, and representation in **Python**. I also investigate patterns that appear in the data, and what insights we can glean from the distributions in the dataset.

## Algorithmic Trading Strategies for QuantConnect

This is a collection of algorithims created in **Python** created in order to research, backtest, and develop trading and investment strategies. Intended for use with the open-source platform QuantConnect. 


### Strategies

#### Asset Class Momentum

This strategy considers 5 ETFs (SPY – US stocks, EFA – foreign stocks, BND – bonds, VNQ – REITs, GSG – commodities). It picks the 3 ETFs with the strongest 12-month momentum, weighting them equally, and rebalances once a month. This strategy has a CAGR of 9.8%, a max drawdown of 70.5%, and a Sharpe ratio of .49.

<script src='https://www.quantconnect.com/terminal/backtest.js?sid=434dbef842cee46850dbfba07cc4534d'></script>


#### All Weather Portfolio 

The "All Weather" Portfolio, popularized by hedge fund manager Ray Dalio, is designed to minimize drawdowns through financial downturns. It is composed of 40% long-term bonds, 30% stocks, 15% intermediate-term bonds, 7.5% gold, and 7.5% commodities. The portfolio rebalances itself to these levels once a year. This strategy has a CAGR of 9.2%, a max drawdown of 21.7%, and a Sharpe ratio of .88.

<script src='https://www.quantconnect.com/terminal/backtest.js?sid=1bb306edc363c0c80b9580744d8dfc26'></script>
