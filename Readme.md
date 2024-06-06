# Lydia's Trading Bots

My Ninjatrader strategy bots. To view spreadsheet of my bots and their estimated historic performance, go to [My Spreadsheet](https://docs.google.com/spreadsheets/d/1Dzkn98K6t8bCk7rMwND_1eEDjMVcMsebt0tExMt18JU/edit?usp=sharing)

## Lydia 8
Same as Lydia3 with all the SMA lines drawn onto chart.

## Lydia18
Improving Lydia10 by adding RSI as condition. 
Long: RSI crosses above 34. One candle back was green. Now this one is too. ATR also needs to be above 2.

## Lyda19
Short:  RSI crosses below 70. Reversing Lydia18. One candle back was red. Now this one is too. The ATR also needs to be above 2 to trigger it.

## Lydia24
This is the Long side only of Lydia22 (which was previously JR1). SMA 4 crosses above SMA 50. One bar back was green. Current bar is green so far. Volume is 1.3 times that of previous bars and ATR is at least .6

