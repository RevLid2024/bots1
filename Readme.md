# Lydia's Trading Bots

My Ninjatrader strategy bots. To view spreadsheet of my bots and their estimated historic performance, go to [My Spreadsheet](https://docs.google.com/spreadsheets/d/1Dzkn98K6t8bCk7rMwND_1eEDjMVcMsebt0tExMt18JU/edit?usp=sharing)

## Bot performance summary

| Name         | Profit        | Max Drawdown |   Ratio  |  % Wins   |  Trades/day 
| ----------   | ------        | ---------  | ----- | ----- |  ------- |
| Lydia3       | 8950      |  975       |   9.18 |    9.18 |  1 |
 Lydia8     | 8950       |  975       |   9.18  |  9.18 |   1
| Lydia10      | 4600      |  700       |   6.57  |  9.18 |   1
| Lydia12      | 4000      |  375       |   10.67  | 9.18 | .8
 Lydia15       | 7362      |  1950      |   3.7  |   9.18 |  5
 Lydia18

## Lydia3

My first working Bot.

Long after Series of shorter timeframe SMAs above longer SMAs. EMA slope is up. Previously named "Winner Long". Treid the exact opposite with a short, but it didn't work.

## Lydia 8

Same as Lydia3 with all the SMA lines drawn onto chart.

## Lydia10

Long: RSI crosses above 34. One candle back was green. Now this one is too.

## Lydia15

Long entry: Using the 1-minute chart, price crosses above the SMA20 and current candle is green. The advantage of using this bot to work from, is that it too 288 trades --  an average of almost 5 perday. 

## Lydia18

Improving Lydia10 by adding RSI as condition. 
Long: RSI crosses above 34. One candle back was green. Now this one is too. ATR also needs to be above 2.