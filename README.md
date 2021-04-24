
![coronavirus-u s -economy](https://user-images.githubusercontent.com/898144/115945411-b2aba400-a489-11eb-9810-4cc7a2d49347.jpg)


# Covid Capitalism
## Welcome
The Covid-19 Virus sent the world into a global frenzy like never seen before, and perhaps gave birth to the rise of the retail trader. Robinhood made it easy for the average Joe to full blown dive into securities trading, cold turkey. The combination of easy access from apps like Robinhood and the market conditions of the global Coronavirus pandemic created a massive shakedown of the stock market. It is March 09, 2020 and you are anxiously watching the impact of the Covid-19 pandemic unfold into society. 

The stock market crash of 2020 has just begun on Monday, with history’s largest point plunge for the Dow Jones Industrial Average (DJIA) up to that date. It was followed by two more record-setting point drops on March 12 and March 16. The stock market crash included the three worst point drops in U.S. stock market history. Amidst the global frenzy, your good buddy, seasoned trading veteran, Jon Raccah is convinced that there is no better time ever to take advantage of the huge drop in share prices and capitalize on this opportunity under the assumption that share prices will rebound sooner rather than later, leading to glorious gains. 

After consulting with John and all things considered, you are convinced that it is indeed the ultimate opportunity to capitalize on chaos and decide to invest $200,000 into the stock market and cryptocurrency on March 17, 2020. You decide to invest half of your portfolio in blue chips to mitigate long term risk, and the other half in crypto currency, volatile stocks, pandemic related airline stocks and pandemic related hospitality stocks. You are locked and loaded, eager to see how your investment plays out, and how soon the economy recovers from the initial shock of the Covid-19 scare.

### Your Portfolio consists of the following:
![stocks](https://user-images.githubusercontent.com/898144/115946286-2ea7eb00-a48e-11eb-9d80-600fe78b06bc.jpg)

## Meet The Team ###
![head_shots](https://user-images.githubusercontent.com/898144/115945153-5c8a3100-a488-11eb-8db8-fefa8b493527.png)

## Overview
![overview_chart](images/overview_chart.jpg)

## Preliminary Analysis!
The first step is to pull all the closing prices for each individual security using Alpaca Keys and Yahoo Finance alongside our two benchmarks for measurement, SP500 and Nasdaq. We create a dataframe containing each individual asset including the two benchmarks to prepare comprehensive analysis.

![All_assets_Volatility.png](images/All_assets_Volatility.png)

**Analysis:** SP500 is the benchmark, least riskiest least volatile while Tesla and Gamestop lead the pack in volatility.

![All_assets_Daily_RReturns.png](images/All_assets_Daily_RReturns.png)
![Maximum_portfolio_percent_change.jpg](images/Maximum_portfolio_percent_change.jpg)

**Analysis:** The maximum daily return of our portfolio belongs to Gamestop at +136% on January 27, 2021. The minimum daily return also belongs to GameStop at -60% on February 02, 2021. This summarizes the volatility value of Gamestop referenced above.

![All_assets_Cumulative_Returns.png](images/All_assets_Cumulative_Returns.png) ![All_assets_average_cumulative_returns.png](images/All_assets_average_cumulative_returns.png)

**Analysis:**  GameStop, ETH, BTC, MGM, Tesla, WYNN, AMZN, Boeing and Micrsosoft all had higher average cumulative returns than SP500. GameStop,ETH, BTC, MGM, Tesla, WYNN and AMZN all had higher average cumulative returns than Nasdaq. AAPL has the lowest cumulative returns in our portfolio.

![All_assets_Correlation.png](images/All_assets_Correlation.png) ![All_assets_Sharpe.png](images/All_assets_Sharpe.png)

**Analysis:** BTC and ETH have the best return to risk ratios far above SP500 and Nasdaq at 3.76 and 3.39, respectively. AAPL has the lowest sharpe ratio at 0.07, least favorable return to risk.

![All_assets_daily_std.png](images/All_assets_daily_std.png) ![All_assets_rolling7_std.png](images/All_assets_rolling7_std.png)

**Analysis:** GameStop has the higest standard deviation, most risk. BRK.A has the lowest std and is the least riskiest of our investments. All of our assets are riskier than the SP500.



## Our Portfolio
Next, we create a dataframe containing only the individual assets comprising our portfolio, and assign the distribution weights to calculate the daily returns, cumulative returns and cumulative profit of our portfolio as a whole.

![Our_assets_Daily_Returns.png](images/Our_assets_Daily_Returns.png)

**Analysis:** Our Portfolio's greatest daily return was on March 24, 2020 at +11.18%, and the lowest daily return was on August 31, 2020 as our portfolio fell -13%. 

![Our_assets_cumulative_returns.png](images/Our_assets_cumulative_returns.png)

**Analysis:** As of April 13, 2021 Our Portfolio is worth $762,572.78. A net profit of $567,572.78 off our investment, and a total return of +381.29%




## Our Performance Measure
Next, we created a dataframe containing the daily returns of our portfolio, SP500 and Nasdaq to measure our portfolio’s performance against the benchmarks.

![Performance_daily_returns.png](images/Performance_daily_returns.png)
![Performance_cumulative_returns.png](images/Performance_cumulative_returns.png)

**Analysis:** Our Portfolio Cumulative Returns were greater than both SP500 and Nasdaq cumulative returns throughout the entire period.


![Peformance_annualized_std.png](images/Peformance_annualized_std.png)
![Performance_rolling21_std.png](images/Performance_rolling21_std.png)

**Analysis:** Our Portfolio is exponentially riskier than both SP500 and Nasdaq given the volatile nature of our individual investments.


![Performance_Correlation.png](images/Performance_Correlation.png)
![Peformance_Rolling30_beta.png](images/Peformance_Rolling30_beta.png)
![Peformance_Rolling60_beta.png](images/Peformance_Rolling60_beta.png)
![Peformance_Rolling120_beta.png](images/Peformance_Rolling120_beta.png)

**Analysis:** The covariance between our portfolio and the SP500 is positive and extremely low which means that there is a weak positive relationship between the two. The variance between our portfolio and the SP500 is positive and extremely low also which means that there is low correlation between securities in our portfolio. With a beta value of 1.14, our portfolio is slightly more volatile than the market, approximately 14%.


![Performance_Annual_Sharpe.png](images/Performance_Annual_Sharpe.png)

**Analysis:** Our Portfolio signigficantly Outperformed the Nasdaq which slightly outperformed the SP500. Sharpe ratio of 3.4 is considered excellent and a farabove average risk to return ratio.

## Portfolio Optimization
Next, we measured the returns of our original portfolio versus two optimized versions of our portfolio. In the diversified portfolio, we dropped the two most highly correlated assets (MGM, WYNN).  In the diversified and return-to-risk optimized portfolio, we drop the two most highly correlated assets (MGM, WYNN) and also dropped the three lowest sharpe ratio assets ( BA, DAL, AAPL).  The results are shown below.

![Overlay_Hypothetical.png](images/Overlay_Hypothetical.png)

**Analysis:** When optimized with less correlation and eliminating those with the lowest sharpe ratios, our returns were astronomical, exponentially greater than our original portfolio.


## Forecasting Analysis

![forcasting_chart_1](images/forcasting_chart_1.jpg)
![forcasting_chart_2](images/forcasting_chart_2_update.jpg)
![forcasting_chart_3](images/forcasting_chart_3.jpg)
![forcasting_chart_4](images/forcasting_chart_4.jpg)


# Conclusion
If you failed to take John’s sound advice on March 17, 2020, you quite possibly missed a once in a lifetime opportunity for overnight stock market glory. Our decision to invest $200,000 to creating our portfolio gave us a +381% return on our investment, in just over a year. Our Portfolio is now worth, $762,572.78, with a net profit of $567,572.78. 

The question now remains, can our portfolio sustain at this seemingly unreal rate of return, or should we sell and take our half million-dollar profit to the bank? According to our simulations it would be incompetent and outright foolish to sell off.  Over the span of one year’s worth of trading days, our forecasting algorithm predicts that the worst our portfolio can perform is a return of 172.55% on our investment and could reach over 800%. We are treating John to a steak dinner at the Four Seasons hotel, and gifting him a new Rolex Submariner watch, to discuss strategy going forward.




![stock](https://media.giphy.com/media/l0HlDDyxBfSaPpU88/giphy.gif)

