# 🧠 Multi-Timeframe Algorithmic Trading Strategy for XAUUSD

This project presents a complete end-to-end **algorithmic trading system** designed, developed, and backtested on the **XAUUSD (Gold vs USD)** market using **Python** and real historical data.

## 📌 Strategy Highlights
- **Multi-Timeframe Setup**: Daily chart for trend filtering, 15-minute chart for precise entries.
- **Indicators Used**: EMA, MACD, ADX, RSI, Stochastic RSI, Volume MA, Fibonacci levels.
- **Risk Controls**: ATR-based stop-loss, trailing stop, dynamic position sizing (1% per trade).
- **Custom Features**: Trendline breakouts using ATR slope logic, swing-based fib entries/exits.
- **Realistic Execution**: Includes slippage, commissions, and leverage (5x) in backtest.

## 💼 Tech Stack
- Python
- Backtrader
- NumPy, Pandas, Plotly

## 📊 Performance Summary
- **Total Return**: 9%
- **Max Drawdown**: 8.46%
- **Profit Factor**: 3.31
- **Win Rate**: 40%
- **Expectancy**: ₹44.99 per trade

> Only 10 trades were taken—focusing on high-probability setups under strict confluence.

## 📁 Files Included
- `Gold analysis.ipynb` – Code and visualization notebook
- `XAUUSD_Strategy_Report.pdf` – Full documentation of strategy logic and results
- `strategy_report.txt` – Summary description
- `trades_log.xls` – Trade logs
- `xauusd_advanced_backtest.zip` – Full code and supporting files

## 🔗 More Info
See the [PDF report](./XAUUSD_Strategy_Report.pdf) for full logic, performance analysis, and visualizations.

---

Feel free to fork, explore, or adapt this strategy for other markets. Contributions and suggestions welcome!
