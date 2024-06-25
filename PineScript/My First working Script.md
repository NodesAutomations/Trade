### Script 
```
//@version=5
indicator("My First Script",overlay = true)
//Plot Horizontal Line to Existing Chart
hline(2000)
//Plot line connecting closing price of chart
closingPlot=plot(close,color = color.red)//close is closing price and open is for open price
openingPlot=plot(open,color = color.green)//close is closing price and open is for open price
//Fill part between two plot
fill(openingPlot,closingPlot,color = color.white)
```
- `//@version=5`
    - This is a compiler annotation telling the compiler the script will use version 5 of Pine Script™.
- `indicator("My First Script",overlay = true)`
    - Defines the name of the script that will appear on the chart as “My First Script”.
-  `hline(2000)`
    - Plot Horizontal Line with 2000Yaxis value to Existing Chart
- `closingPlot=plot(close,color = color.red)`
    - Plot graph using closing price
- `fill(openingPlot,closingPlot,color = color.white)`
    - Fill Part between two plots