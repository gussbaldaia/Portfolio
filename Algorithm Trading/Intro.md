<h1 align="left">Algorithmic Trading Project</h1>

***JANUARY, 2023***

<h2 align="left">Summary:</h2>
The Algorithmic Trading Project is a comprehensive initiative aimed at developing and testing different trading strategies in financial markets. Leveraging the OANDA API, the project explores the dynamic world of algorithmic trading, seeking to optimize strategies for better risk management and profitability.

<h4 align="left">Programming Language:</h4> 

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
<h4 align="left">Tools:</h4>

![OANDA API](https://img.shields.io/badge/OANDA_API-A5915F?style=flat-square&logo=python&logoColor=white)
![json](https://img.shields.io/badge/json-A5915F?style=flat-square&logo=python&logoColor=white)
![backtesting](https://img.shields.io/badge/backtesting-A5915F?style=flat-square&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-A5915F?style=flat-square&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-A5915F?style=flat-square&logo=python&logoColor=white)
<h2 align="left">Trading Strategies:</h2>

# **MACD with BBands - Trend Following Strategy**
### **Overview**

This strategy is designed as a trend-following approach, relying on two key indicators to identify potential buy and sell signals, as well as to gauge market trends and volatility.

### Indicators Used:
**Moving Average Convergence Divergence (MACD):**

**Purpose:** Identifying market trends and potential entry/exit points.
**Method:** Crossover between MACD and signal line.
**Additional Use:** Detecting overbought or oversold market conditions.

### Bollinger Bands:

**Purpose:** Confirming market direction, signaling potential trades, and assessing market volatility.
**Method:** Breakout of asset price from Bollinger Bands.

# **Reversal Patterns Strategy**
### **Overview**

This strategy aims to identify potential trend reversals using candlestick chart patterns, specifically Engulfing, Gravestone Doji, and Dragonfly Doji. It combines these reversal patterns with the MACD, SMA, and ATR indicators for a comprehensive approach to generating buy and sell signals.

### Indicators Used:
**MACD (Moving Average Convergence Divergence):**

**Purpose:** Identifying crossovers to determine market trends.

**SMA (Simple Moving Average):**

**Purpose:** Evaluating the overall market trend.

**ATR (Average True Range):**

**Purpose:** Setting Stop Loss and Take Profits limits based on market volatility.

### Strategy Structure:
**Long Entry:**
Criteria:
MACD line crosses above the signal line.
Upward trend indicated by SMA.
Confirmation with Engulfing or Dragonfly Doji patterns.
Exit: Follow ATR-based Stop Loss and Take Profits.

**Short Entry:**
Criteria:
MACD line crosses above the signal line.
Upward trend indicated by SMA.
Confirmation with Engulfing or Gravestone Doji patterns.
Exit: Follow ATR-based Stop Loss and Take Profits.
