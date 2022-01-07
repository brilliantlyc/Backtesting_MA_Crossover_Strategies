# PROJECT 1: "HELLO WORLD" QUANTITATVE TRADING

## Context
Moving Average (MA) Crossover Strategy is very well known and the most simple long-only trading strategy. Signals to buy is depending on the crossover of short lookback period over long lookback period. In contrast, the sell signal is triggered when MA long lookback crosses the MA short lookback.

There are 5 most popular strategies:
* 50 SMA crossing 200 SMA [Hanna]
* 50 SMA crossing 100 SMA [Claudia]
* 20 EMA crossing 50 SMA [Atousa]
* 11 EMA crossing the 49 EMA [Jalal]
* 9 EMA crossing 20 EMA

<b> <u> @ TEAM: ACTION NEEDED </u> </b>: each of us will choose one strategy for backtesting  

## Hypothesis
Our goal is to examine whether MA crossover strategies benefit for ETF investor from both return and risk perspective.

Benchmark: SPY, SPY Sharp Ratio 


## The Settings

* Initial investment = $10,000 
* No leverage/margin is used
* Buy and sell is on the close prices
* All profit/loss will be reinvested in one trade
* No commision/fee/tax is taken into consideration
* Time horizon: 30 years - 1/1/1992 - 12/31/2021

## Proposed Timeline

<b> <u> @ TEAM: ACTION NEEDED </u> </b> : let's together decide

With the objectives of :
* collaborating efficiently among team
* each of us having a chance to practise what we have studied and learnt
* making the best use of time in class

 I would like to propose timeline as followings:

| Objective/Members  |01/06                                                      | 01/08     | 01/11   | 01/13   |
|--------------------|:---------------------------------------------------------:|-----------|---------|---------|
|<b> Objective </b>           |Collect,clean data, exploration, & skeleton of the notebook   |Finish calculation and draft notebook |(*) Hard deadline: Consolidate results, discuss key findings, start to build dashboard, edit final version of the notebook | Prepare MD file and presentation file |
|Member 1|   |   |   |   |
|Member 2 |   | | |
|Member 3 |  | | |
|Member 4  | | | |

## Resources
* https://www.stockbrosresearch.com/themoneyblog/do-moving-average-crossover-trading-strategies-really-work-backtesting-golden-crosses-and-more
* https://www.kaggle.com/kalilurrahman/tcs-stock-analysis-and-prediction
(sample of the notebook it is very interesting, it introduces several new libraries for us to use in this project)
* https://www.youtube.com/watch?v=ymQ4WhO5Xc0&ab_channel=CodingWithRuss

## Pending things:

* Group name
* ...
* ...

## Several ideas we can figure out after we consolidate all analysis or for our own understanding purpose 

* can we optimize the best strategy(?) testing whether buying 2- 3 days after the trigger is efficient than just 1 day?
* if we can count the total number of buy and sell order to decide which strategy is the most saving in terms of trading cost 
* test if the strateygy is efficient during certain period. i.e: during booming time or covid period
