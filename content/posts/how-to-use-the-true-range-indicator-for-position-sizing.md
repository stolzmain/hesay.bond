+++
title = "How to Use the True Range Indicator for Position Sizing"
date = 2026-07-04
draft = false
tags = ["positionsizing", "ATR", "riskmanagement"]
image = "/images/posts/how-to-use-the-true-range-indicator-for-position-sizing.png"
+++

Position sizing is a cornerstone of successful trading, directly impacting capital preservation and consistency of results. While many traders laser-focus on pinpointing entry points, true long-term profitability often hinges on smart risk managemen

---

Want to test a new trading strategy but afraid of risking your capital? MEXC has an excellent demo account: trade on real charts with virtual money. [Start testing now](https://promote.mexc.com/r/aep0hTSdh1)

---

t. The True Range (TR) indicator and its averaged value, Average True Range (ATR), offer a powerful tool for dynamically calculating position size, adapting to current market volatility for more effective risk control.

##  What is True Range?
True Range is a volatility measure developed by Welles Wilder that accounts for price gaps, which simple High-Low calculations miss. It's the greatest of three values: the current high minus the current low; the absolute value of the current high minus the previous day's close; or the absolute value of the current low minus the previous day's close. This approach ensures the indicator always captures the full price movement over a period, including overnight swings.

##  Volatility and Risk
True Range directly quantifies market volatility. High TR readings signal periods of heightened price action and uncertainty, while low readings suggest a calmer market. For position sizing, Average True Range (ATR) is more commonly used – a moving average of True Range over a specified period (typically 14 or 20 bars). ATR smooths out instantaneous fluctuations, providing a more stable representation of an asset's average volatility. Using ATR allows traders to set stops that appropriately react to current market conditions, rather than arbitrary, fixed levels.

##  Calculating Position Size
The core concept of using True Range (or ATR) for position sizing is to keep your risk per trade a consistent percentage of your trading capital, regardless of asset volatility. This is achieved by dynamically adjusting the number of units traded.
The calculation formula is as follows:

1. Define your risk amount per trade in your account currency. This is typically a fixed percentage of your total trading capital (e.g., 1-2%).
Risk Amount = Capital  Risk Percentage

2. Determine your stop-loss based on ATR. For example, you might set your stop-loss at a distance of 2  ATR from your entry point. This allows the stop to be wide enough to avoid random whipsaws from natural price fluctuations, yet narrow enough to control losses.
Stop Loss Distance (in pips/dollars) = ATR  Multiplier (e.g., 2)

3. Calculate your position size (number of shares, lots, or contracts):
Position Size = Risk Amount / Stop Loss Distance
It's crucial to consider the value of a pip or unit of the asset in your calculation. For instance, with stocks, this would be ATR in dollars; for Forex, it's ATR multiplied by the pip value.

##  Practical Application
Applying True Range for position sizing requires discipline and a clear understanding of your trading system. The choice of ATR period should align with your trading style: shorter periods (e.g., 5-10) might suit intraday trading, while longer periods (14-20) are better for swing trading. Using a dynamic, ATR-based stop-loss allows you to adapt to changing market conditions: in more volatile markets, your stop will be wider, automatically leading to a smaller position size while maintaining constant risk. In less volatile markets, the stop will be tighter, allowing for a larger trade volume.