# stock-analysis

## Overview of Project

### Purpose
The goal with this project is to improve Steve's stock analysis code efficiency. The original code works fine with the given amount of stocks (3000+ stocks with 12 different tickers). However, if Steve were to expand his analysis, he needs to also improve his how efficienty the code runs. That is why I refactored the code to make it more efficient. I did this primarily by avoiding unnecessary loops which can increase run-time especially as data points increase. 

<br/>![Outcomes_vs_Goals](Outcomes_vs_Goals.png)<br/>  

## Results

###Stock Performance 
After refactoring the code, I viewed the data for the same 12 stocks for the years 2017 and 2018. The two main pieces of information is the total daily volume, the number of shares traded, and the return, the performance of the stock. I noticed when comparing the data between the two years that if stock daily volume increased from 2017 to 2018, the return remained positive in 2018. The opposite is also true. If the stock daily volume decreased, the returns were negative. Only 2 stocks that increased in trade volume between 2017 and 2018, ENPH and RUN. In 2018, both of these stocks had a return of over 80%. The remaining 10 stocks decreased in volume and they all had negative returns. <br/>

It is also important to note stock volatility. Some stocks (like DQ and SEDG went from over 100% in returns in 2017 to the negative in 2018. Meanwhile, other stocks remained consistent in return performance between the two years. I have included an image of this dataset below. 

<br/>![2017Data](2017Data.png)  ![2018Data](2018Data.png) <br/>

###Execution Performance

##Summary 

###Advantages and Disadvantages of Refactoring Code and Debrief


