# AI_Trading_Bot
This bot implements a layered drawdown exit strategy, progressively reducing position size at predefined drawdown levels to control downside risk.

The project includes two broker integrations:
- **Alpaca SDK** (paper trading)
- **Trading 212** (via a lightweight REST wrapper)

A Tkinter-based GUI provides real-time visibility into active strategies and positions, alongside an integrated AI chat interface for portfolio analysis and risk-focused commentary based on current holdings and open orders.

