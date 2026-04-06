# Dashboard Indicator

## Overview
- Help me to with basic information about the active chart
- Give me quick overview of current stock
- Help with screening stocks based on some basic parameters

## Features
- Market Cap
- Free Float
- EMA Check
- % from ATH, 10EMA, 21EMA, 50EMA
- ADR Value of this stock
- If stock is part of FNO or not
- If stock is part of preferred Sector
- If you have Holding in stock then Current Gain, BreakEven%, Days in Stock, GTT Value

## Ema formatting

| Range % | Color | Detail |
| --- | --- | --- |
| [3,) | no color | stock is strongly trading above moving average |
| [0-3) | Green | Stock is close to moving average |
| [-1,0) | Orange | Stock is below moving average but within |
| [,-1) | Red | Stock is trading below moving average |

## ATH formatting

| Range % | Color | Detail |
| --- | --- | --- |
| [-5,0]% | Green | Stock is close to All time high |
| [-15,-5) | no color | stock is withing acceptable range of ATH |
| [-20,-15) | Orange | Stock is on extreme edge of ATH |
| [,-20) | Red | Stock is trading far below ATH |

## ADR formatting

| Range % | Color | Detail |
| --- | --- | --- |
| [5,] | Green | Fast moving stock |
| [3.5,5) | no color | Regular stock |
| [2.5,-3.5) | Orange | Passable Range |
| [,-2.5) | Red | Slow moving stock |