# Quantitative Momentum
## Ch 1-4
Introductory and unnecessary.

## Ch 5
| Name | Lookback Window | Holding Period | Reversal | 
| ------ | --------------- | -------------- |----- |
| Long-term | 36-60 Monhs | 1 Month| True | 
| Short-term | 1 Month | 1 Month | True |
| Intermediate-term | 6-to 12-Month | 3 Months | False |

 For Intermediate-term Momentum (12M) ignore the previous month to account for the short-term reversal effect.  
 
 Use Overlapping Portfolios - depending on the rebalance frequency and signal length.  
 Buy 1/N of the portfolio where N is the signal length/rebalance frequency.  
 In the case of Intermediate Momentum, where signal length = 3M, if your rebalance frequency is 1M then 1/(3/1)
 of your portfolio is allocated to each portfolio constructed every rebalance period. Idk if that explains it very well...  
 
 Use *Value Weighting* - each stock is given its "weight" in the portfolio, depending on the size of the firm.  
 
 Holding fewer stocks (50) and re-balancing more frequently leads to higher compound annual growth rates (CAGRs).  
 
 ## Ch 6 
 
 One of the core ways to improve on a generic momentum strategy is to focus on the time-series characteristics of a momentum stock.  

"Smooth" high-momentum stocks tend to outperform "choppy" high-momentum stocks. 

Avoid Lottery stocks using a MAX ranking - maximum daily return over the past month.  
The top decile represents "lottery" stocks and the bottom decile reflects "boring" stocks.  

The lottery characteristic is especially powerful among high beta stocks.  
Within the high beta decile, there is a monotonically decreasing relationship on the average returns as
the "lottery" ranking increases.  

Both lottery and Beta metric can help.  

### Information Discreteness

Proxy for information discreteness (ID) that measures the relative frequency of small signals.  
A large ID means more discrete information, and a small ID denotes continuous information about small changes.  
For past winners with a high past return, a high percentage of positive returns (% positive > % negative) implies 
there are a large number of small positive returns. The exact measure is described by the equation:  
    ID = sign(Past Return) * [% negative - % positive]

Using ID from the preceding 12 M returns, continuous information does better than discrete information over 6 month holding periods.  

## Ch 7

Incorporate Window Dressing and Tax-Incentive Seasonality into Momentum. 
Near the end of a quarter, managers  window dress their portfolios, so winning stocks do well
(because they're being bought) while losing stocks do poorly (because they're being sold),
and December has the strongest momentum returns across all months.  

This suggests re-balancing on the close of trading in Feb, May, August, and November using
non-overlapping portfolios is the best approach.  

## Ch 8

Steps
1. Identify Investable Universe
2. Generic Momentum Screen
3. Momentum Quality Screen (ID)
4. Momentum Seasonality Screen
5. Invest With Conviction

Equal weighted portfolio will accentuate the small-cap effect, potentially boosting returns.  

## Ch 9
Momentum portfolios are best used in combination with high conviction value portfolios.  

You can do a Positive trend risk management as well.
When the 12M rolling Total return of the bench index is positive, go with the strategy. Otherwise, go with Tbills. 

Another way is to use a core-satellite mix.
use a passive benchmark strategy as the core and only adds small component of an active strategy around the edges.
80% to S&P and 20% to Value/Momentum strategy.  

# Appendix
## Earnings Momentum
Earnings Momentum does better than Price Momentum on its own, but when both are combined with Value, the Price Momentum does better.  

## 52-Week High
long (short) positions in stocks whose current price is close to (far from) the 52-week high.
Measured by the price of the stock one month ago divided by the 52-week high over the previous year.
Not much robust evidence to support strategy.  

## Stop-Loss
Adding a stop loss can improve the risk management of the portfolio, but the benefit is muted for long-only.
Switching to bonds when stop. Doesn't really help that much.  

If you want to do some Risk Management look into simple trend-following and time-series momentum type rules to facilitate portfolio
level risk management.  

