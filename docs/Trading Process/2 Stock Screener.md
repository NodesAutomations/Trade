# Stock Screening

## Overview
- Stock screening is the process of filtering stocks based on specific criteria to identify potential investment opportunities. It helps investors narrow down the vast universe of stocks to a manageable list that meets their investment goals and risk tolerance.
- I have developed two method for Stock Screening
    - Trading view screener good for live scans
    - Excel screener good for daily or weekly scans 
- Run Screener everyday to figure out new breakout or to catch good looking setups early

## Selection Criteria for Stock Screening
- Exchange
    - We will only focus on stocks listed on the NSE due to better liquidity more regulation
    - BSE stocks can be more volatile and less liquid only consider if it's a very promising stock that is not listed on NSE
- Market Cap
    - Range : 500cr - 2,00,000cr
    - We are looking for mid-cap and small-cap stocks that have the potential for significant growth
    - Large-cap stocks are generally more stable but may not offer the same growth opportunities
- Price
    - Range : 30 - 7000
    - We want to avoid penny stocks (below 30) which can be highly volatile and risky
    - We also want to avoid very high-priced stocks (above 7000) that we can't buy in significant quantities with our budget plus avoid liquidity issues that can arise with very high-priced stocks
- EMA 21
    - Only consider stocks that are trading above their 21-day Exponential Moving Average (EMA) to ensure we are looking at stocks in an uptrend 
- All time High
    - Only consider stocks that are within 20% of their all-time high to ensure we are looking at stocks with strong momentum and potential for further growth
- Price change %
    - Only consider stock with a price change of -2% or more today to identify stocks that may be experiencing a temporary pullback and could be good buying opportunities
    - You can remove this criteria if you're doing weekly screening as it may not be relevant for longer-term analysis
