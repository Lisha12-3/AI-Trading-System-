# AI-Trading-System-
This is a cutting-edge AI powered trading bot using Python, integrating reinforcement learning, Quantum computing optimizations, and real-time financial data analysis. This bot predict stock price movements and make autonomous trading decisions in a simulated stock market enviornment. The system includes:
Deep Reinforcement Learning(DRL) Trading Model: The system trains an AI agent using Proximal Policy Optimization(PPO) to trade stocks in a simulated enviornment. It also uses Custom StockTradingEnv class for market simulation. The Decision making based on balance, shares, and market trends.

Sentiment Analysis For Market News: A Transformer-based model analyzes financial news and determines market sentiment. It uses Hugging Face's pipeline. It aggregates sentiment scores for market impact evaluation.

Quantum Portfolio Optimization: This feature applies Quantum Approximate Optimization Algorithm(QAQA) to construct an optimal investment portfolio. It utilizes Qiskit's Quantum Portfolio Optimization module. It is simulated on IBL QASM Simulator.

Performance Metrics For Evaluation: The system calculates critical trading performance metrics to assess risk and return. It uses key elements such as Sharpe Ratio (risk-adjusted return), Sortino Ratio ( downside risk-adjusted return) and Max Drawdown (peak-to-trough decline in portfolio value).

Real Time Data Streaming: The system fetches live stock market data via WebSockets for real-time decision-making. It uses JSON-based processing of incoming market data.
