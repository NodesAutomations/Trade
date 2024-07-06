### Daily Values
- use can use `open`, `close`, `high`,`low ` variable to get ohlc values of last candle
- use use `open[1]`, `close[1]`, `high[1]`,`low[1]` to get ohlc value of second last candle
- in short use Array [] with different index to get value of previous candles

### Weekly values

Sample code to get weekly values
```
weeklyHigh = request.security(syminfo.tickerid, "W", high)
weeklyLow = request.security(syminfo.tickerid, "W", low)
weeklyClose = request.security(syminfo.tickerid, "W", close)
```