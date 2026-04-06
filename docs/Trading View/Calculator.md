# Calculator

## Overview
- I use this indicator to calculate the gain and risk of current stock during active trade.
- It also gives me some helper values like stoploss value and quantity to buy based on position size defined in settings.

## Features
- Gain and Risk of Current stock
- Trigger % if stock is about to breakout and part of my watchlist
- Current Day stats
    - Relative volume
    - Open %
    - Gap %
    - DCR
- Helper values
    - Stoploss %
    - Stoploss value
    - Stoploss type
    - Quantiy for position size define in settings


## Relative volume Classification

| Range % | Color | Detail |
| --- | --- | --- |
| [80,] | Green | stock is with good Daily volume |
| [50,) | No Color | Normal volume |
| [30,50) | Orange | Acceptable volume |
| [0,30) | Red | Not enough volume |

## Daily Closing range Classification

| Range % | Color | Detail |
| --- | --- | --- |
| [80,] | Green | Strong Closing |
| [50,80) | No Color | Normal Closing |
| [30,50) | Orange | Acceptable closing |
| [0,30) | Red | Weak closing |

## Stoploss Classification

| Range % | Color | Detail |
| --- | --- | --- |
| [0,1] | Green | Low Risk |
| [1,2.5) | No Color | Normal Risk |
| [2.5,4) | Orange | Acceptable Risk |
| [4,0) | Red | High Risk |
 
## Gain Classification

| Profit % | Color | Detail |
| --- | --- | --- |
| [16,] | Green | Good Profit |
| [8,16) | No Color | Normal Profit |
| [0,8) | Orange | Not much Profit |
| [,0) | Red | Loss |

## Open Classification

| Profit % | Color | Detail |
| --- | --- | --- |
| [2,] | Green | Gap Up |
| [-0.25,2) | No Color | Normal Opening |
| [-2,-0.25) | Orange | Weak Opening |
| [,-2) | Red | Gap Down |

## Gap Classification

| Profit % | Color | Detail |
| --- | --- | --- |
| [2,] | Green | Gap Up |
| [-0.25,2) | No Color | Normal Opening |
| [-2,-0.25) | Orange | Weak Opening |
| [,-2) | Red | Gap Down |
- I am Still not fully sure how to classify this, so not keeping same as Open