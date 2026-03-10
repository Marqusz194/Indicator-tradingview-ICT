# Indicator-tradingview-ICT
An algorithmic trading strategy for the S&amp;P 500 based on the ICT PM Session Killzone and Displacement concepts."

# 🇺🇸 Gemini ICT V11 [Extended Dashboard] - S&P 500

This is an open-source Pine Script (v5) quantitative trading strategy built for the **S&P 500 (US500)** on the **5-minute (5m)** timeframe. 

It heavily relies on Smart Money Concepts (SMC) and the Inner Circle Trader (ICT) methodology, specifically targeting the PM Session Killzone.

## ⚙️ How to Test It on TradingView
1. Open [TradingView](https://www.tradingview.com/) and load any **S&P 500** chart (e.g., SPX, US500 from Vantage or OANDA).
2. Set your timeframe to **5 minutes (5m)**.
3. Open the **"Pine Editor"** at the bottom.
4. Paste the entire code from `Gemini_ICT_V11.pine` found in this repository.
5. Click **"Add to chart"**. 
6. Play with the risk settings and session times in the Indicator Settings!

## 📊 Core Strategy Logic
* **The Killzone:** The algorithm is completely dormant most of the day. It only activates during the New York PM Session (default is 15:30 - 16:30 NY Time).
* **Displacement:** It looks for a sudden, aggressive burst in price (momentum shift) that breaks market structure.
* **The Pullback Entry:** Instead of chasing the breakout, it waits for a micro-pullback into the newly created Fair Value Gap (FVG) / imbalance area to execute the trade.

## 🤝 I Need Your Feedback & Testing!
I am sharing this publicly to gather insights from the quant and trading community. If you run backtests, find better optimized Stop Loss buffers, or know how to filter out choppy days:
* Please go to the **[Issues](../../issues)** tab above.
* Click **"New Issue"** and share your backtest results, screenshots, or code optimization ideas! Let's build a better bot together.
