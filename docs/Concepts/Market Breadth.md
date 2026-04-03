# Market Breadth

## Overview
- market breath is way to gauge current market Health
- Market breadth measures the degree of participation & the conviction in the overall mood of the underlying index
- There's multiple indicator this job some uses percentage, some used new highs and lows
- I mostly rely on NSE Percentage of Stocks because it's very dynamic and can be checked for daily basis


## NSE Percentage of Stocks
- NSE Percentage of Stocks is a market breadth indicator that measures the percentage of stocks in the Nifty 50 index that are trading above their 10/20/50/200-day moving average.
- Sample Data for Percentage of Stock above 10,20 and 50 Day Moving Average

    | Date | 10 | 20 | 50 |
    | -------- | ------- |-------- | ------- |
    |17 May|64.49|56.8|54.95|
    |16 May|54.26|50.31|49.23|
    |15 May|50.85|47.41|47.77|
    |14 May|43.38|40.45|44.92|
    |13 May|24.31|27.87|37.49|
    |10 May|21.25|27.52|38.50|
    |9 May|14.43|21.77|34.96|
    |8 May|28.89|38.48|47.10|
    |7 May|22.82|33.18|44.62|
    |6 May|35.16|47.21|53.71|
    |3 May|49.08|60.56|62.00|
    |2 May|60.74|67.35|65.40|

- I am only interested in percentage of stock 10,20,50 day
- I mostly look at 10 and 20 day percentage value to figure out daily trend. 50 day is trend confirmation
- This table explains how to interpret percentage of stock above 10/20/50 day moving average and what action to take based on it.

    | Percentage | Market |
    | -------- | ------- |
    | 0-20 | Oversold |
    | 20-50 | Weak market |
    | 50-80 | Healthy Market |
    | 80-100 | Overbought Market |

- When Should I start Buying

    | Above 50% | Action |
    | -------- | ------- |
    |10 | 25% Market Exposure|
    | 21 | 50% market exposure|
    | 50 | Go all in |

- When shoud i start selling

    | below 55% | Action |
    | --- | --- |
    | 10 | No New Buy, Start Booking Profits, basically sell anything below 10EMA or low profit margin |
    | 20 | Sell everything without profit margin |
    | 50 | Sell everything and move to cash |

- From Sample data you can clearly identify when market starting get weak from 2-3 may to 6-7 may
- This is my current favorite method to adjust my market exposure, this is much more reliable than just watching index

!!! Tip
    It's hard to pin point exact moment when market turn bad, so just use your best judgement. Also when market look bad don't focus on risk reward when booking profits just sell, don't try to be perfect.

## Net New Highs and Lows
- Displays the net number of stocks on NSE (India) making 52-week highs or lows. The count is displayed as a fraction of the total number of stocks in the NSE universe.
- Net New Highs (NNH) are calculated by taking the number of new 52-week highs on any given day and subtracting from it the number of new 52-week lows.
- A market is considered strong (bullish) when NNH are positive, or, in other words, when new highs exceed new lows.
- We consider the bias as positive (bullish) when NNH stays positive for 3 consecutive days, & negative (bullish) when NNH stays negative for 3 consecutive days.
- Sample data for Net New Highs and Lows

    | Date | NNH | NNH Percentage |
    | -------- | ------- | ------- |
    |17 May|0.12| 12 |
    |16 May|0.08| 8 |
    |15 May|0.05| 5 |
    |14 May|-0.02| -2 |
    |13 May|-0.10| -10 |
    |10 May|-0.15| -15 |
    |9 May|-0.20| -20 |
    |8 May|0.05| 5 |
    |7 May|0.10| 10 |
    |6 May|0.20| 20 |
