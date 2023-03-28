If you win, please support me on Paypal: clickclone@gmail.com

## Script Trading ES 20223

Please use this one with timeframe 5M: `https://github.com/dearvn/trading-futures-tradingview-script/blob/main/ESH2023-5M.txt`

## Trading GOLD
 
Using script `GOLD_UZ_OZ.txt`

![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/gold.png?raw=true "Gold")


## Using the latest version of `es-futures-no-repaint-v1.x.txt` to alert on 1M ES without REPAINT time trading from 6:30AM to 12:30 PM UTC-8

Alert to auto trade using timeframe 1M: `es-futures-no-repaint-v1.x.txt`

Review history timeframe 30s: `es-futures-repaint-30s.txt`

![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/alerts.png?raw=true "alerts")


## Newbie

**Use `color-trend-lite.txt` to trade easily**

**BLUE: trend up**

**RED: trend down**

**How to use: ex: when I enter CALL if color is still BLUE and high[1] < high then keep CALL. Or when I enter PUT if color is still RED and low[1] > low  then keep PUT. Else EXIT CALL or EXIT PUT**

![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/color-trend.png?raw=true "color-trend")

## Strategy ES 1M

using: `best-strategy-es-1m.txt`

![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/strategy-es.png?raw=true "strategy-es")

## Binance Futures Trading

Ref: https://github.com/dearvn/tradingview-pinscript-futures-binance

## PRIVATE SCRIPT

**11/07/2022**
![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/private.png?raw=true "private")


## WINNING VS LOSING TRADES

![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/today.png?raw=true "today")

![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/gain_loss_report.png?raw=true "gain_loss_report")


## SUPORT ME

I like a cup of coffee at https://www.patreon.com/donaldit

## IMPORTANT
* Currently, I am trading on ```trade-futures.txt``` script
Belong to ticker and timeframe, I set input IN and input OUT
Backtest on timeframe 5M
* ES: input IN = 5, input OUT = 3
* NQ: input IN = 15, input OUT = 12 or input IN = 8, input OUT = 5

Enjoy daily trading Futures and if this script is good please me coffee (https://www.patreon.com/donaldit)
or need implement a script donald.nguyen.it@gmail.com

## WEAK MARKET 
* I implement logic to trade when market is weak this time let use script ```best-indicator.txt```

**Using:**
*GC = Great Call (exit PUT beforce CALL)
*GP = Great PUT (exit CALL beforce PUT)
*Timframe: 5m

![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/best-indicator.png?raw=true "best-indicator.png")

## SWING 
Using indicator `swing.txt` to exit or entry CALL PUT
![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/swing.png?raw=true "swing.png")

## MARKET CRASH
* I implement logic to trade when market crash this time let use script ```win-99.txt```

![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/win100.png?raw=true "WIN100%")


## Alert
* I write some alert and can set webhook to get signal on Wordpress Plugin https://github.com/dearvn/tradingview-alerts

![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/alert.png?raw=true "Alert")


# trading-futures-tradingview-script
I write pine script to trading futures ES1 NQ1 with signal IN (accurate 90%) and now I am trading on that
## Logic to trade futures
I can't use existing indicators to trade future, I lost so much
Few months ago, I backtest on this scripts and my idea is using the point to trade instead of indicator
Absolutely, the point is correct with futures.

For example, when "IN" signal notify I can CALL on Tradovate platform.

![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/nq.png?raw=true "NQ1")

## History Gain/Loss
* 2022-08-30 Gain PUT 253 Points
![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/nq-2022-08-30_at_22.12.05.png?raw=true "NQ1 2022-08-30 at 22.12.05")

* 2022-08-31 Gain/Loss in evidence
![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/nq_2022-30-31_at_17.34.17.png?raw=true "NQ1 2022-08-31 at 17.24.17")

* 2022-09-01 Gain/Loss in evidence
![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/nq_2022-09-01.png?raw=true "NQ1 2022-09-01")

* 2022-09-02 Gain/Loss in evidence
![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/nq_2022-09-02_at_10.13.06.png?raw=true "NQ1 nq_2022-09-02 at 10.13.06")

* 2022-09-06 Gain/Loss in evidence
![Alt text](https://github.com/dearvn/trading-futures-tradingview-script/raw/main/nq-2022-09-06_at_11.02.17.png?raw=true "NQ1 nq-2022-09-06 at 11.02.17")

