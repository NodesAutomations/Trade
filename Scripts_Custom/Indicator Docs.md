# Common Formating Rules

### Colors Classification
| Color | Meaning |
| --- | --- |
| Green | Perfect Range |
| No Color | Normal Range |
| Orange | Below Average but acceptable Range |
| Red | Warning Bad Value |


# Main Indicator

### What does it contain
- Moving Averages 10/21/50/100/200
- All time high line
- Bull snort Candle marker
- Inside bar candle marker
- Dashboard to help with stock screening it contain
    - % distance from Moving averate
    - % distance form all time high
    - ADR for daily timeframe


### Ema formatting

| Range % | Color | Detail |
| --- | --- | --- |
| [3,) | no color | stock is strongly trading above moving average |
| [0-3) | Green | Stock is close to moving average |
| [-1,0) | Orange | Stock is below moving average but within |
| [,-1) | Red | Stock is trading below moving average |

### ATH formatting

| Range % | Color | Detail |
| --- | --- | --- |
| [-5,0]% | Green | Stock is close to All time high |
| [-15,-5) | no color | stock is withing acceptable range of ATH |
| [-20,-15) | Orange | Stock is on extreme edge of ATH |
| [,-20) | Red | Stock is trading far below ATH |

### ADR formatting

| Range % | Color | Detail |
| --- | --- | --- |
| [5,] | Green | Fast moving stock |
| [3.5,5) | no color | Regular stock |
| [2.5,-3.5) | Orange | Passable Range |
| [,-2.5) | Red | Slow moving stock |

# Helper

### What does it contain
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

### Relative volume

| Range % | Color | Detail |
| --- | --- | --- |
| [80,] | Green | stock is with good Daily volume |
| [50,) | No Color | Normal volume |
| [30,50) | Orange | Acceptable volume |
| [0,30) | Red | Not enough volume |

### Daily Closing range

| Range % | Color | Detail |
| --- | --- | --- |
| [80,] | Green | Strong Closing |
| [50,80) | No Color | Normal Closing |
| [30,50) | Orange | Acceptable closing |
| [0,30) | Red | Weak closing |

### Stoploss

| Range % | Color | Detail |
| --- | --- | --- |
| [0,1] | Green | Low Risk |
| [1,2.5) | No Color | Normal Risk |
| [2.5,4) | Orange | Acceptable Risk |
| [4,0) | Red | High Risk |

### Gain

| Profit % | Color | Detail |
| --- | --- | --- |
| [16,] | Green | Good Profit |
| [8,16) | No Color | Normal Profit |
| [0,8) | Orange | Not much Profit |
| [,0) | Red | Loss |

### Open

| Profit % | Color | Detail |
| --- | --- | --- |
| [2,] | Green | Gap Up |
| [-0.25,2) | No Color | Normal Opening |
| [-2,-0.25) | Orange | Weak Opening |
| [,-2) | Red | Gap Down |

### Gap

| Profit % | Color | Detail |
| --- | --- | --- |
| [2,] | Green | Gap Up |
| [-0.25,2) | No Color | Normal Opening |
| [-2,-0.25) | Orange | Weak Opening |
| [,-2) | Red | Gap Down |
- I am Still not fully sure how to classify this, so not keeping same as Open