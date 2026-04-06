# My Trading process

!!! quote "William J. O'Neil"
    *"Goal of trading is to buy right stock at right time with right size"*

## Market Health Analysis
- Before we start trading, it's crucial to analyze the overall market conditions to check if the market is in a favorable state for trading.

```mermaid
graph TD
    Start --> MH{Market Health}
    MH --Bad--> StayOnSideLine[Stay On Sidelines]
    MH --Good--> SectorAnalysis{Sector Analysis}
    SectorAnalysis--No Trending Sectors--> StayOnSideLine
    SectorAnalysis--Multiple Trending Sectors--> Watchlist[Prepare Stock Watchlist]
```

## Stock Selection Process

```mermaid
graph TD
    StockScreener[ATH20 Run Stock Screener]
    StockScreener--Stock removed which do not meet criteria--> StockSelection[Stock Selection]
    StockSelection--Stocks with Best Price Action--> ReadyToBuyStocks[Ready to Buy Stocks]
    ReadyToBuyStocks--Select Best stock with low Risk--> ExecuteTrade{Execute Trade}
    ExecuteTrade --Trades are working--> PositionSizing[Go All In]
    ExecuteTrade --Trades not working--> ReduceExposure[Reduce Exposure]
```