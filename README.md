# 📈 SBI Quantitative Analysis & Algorithmic Trading Strategy

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Quantitative Finance](https://img.shields.io/badge/Quant-Finance-green) 
![Machine Learning](https://img.shields.io/badge/ML-Trading-orange)
![IIT Jodhpur](https://img.shields.io/badge/IIT-Jodhpur-red)

**Advanced Financial Engineering Project | State Bank of India (NSE: SBIN)**

## 🎯 Executive Summary

A comprehensive quantitative research project analyzing SBI stock performance with institutional-grade risk metrics and algorithmic trading strategies. This project demonstrates professional financial engineering capabilities from data acquisition to strategy backtesting.

## 📊 Project Highlights

- **💰 Returns Analysis**: 6.91% Buy & Hold return (2023)
- **⚡ Risk Metrics**: 21.22% Volatility, -2.07% VaR (95% CI)
- **🤖 Trading Strategy**: MA Crossover + RSI Filter backtesting
- **📈 Technical Analysis**: Moving Averages, RSI, Volume-Price analysis

## 🏗️ Core Features

### Technical Analysis
- Multi-timeframe Moving Averages (20-day, 50-day)
- RSI Momentum Indicator with overbought/oversold zones  
- Price Action Analysis (High-Low ranges, volatility clusters)
- Volume-Price Relationship studies

### Risk Management
- Value at Risk (VaR) - Maximum expected loss calculation
- Conditional VaR (CVaR) - Tail risk assessment
- Sharpe Ratio - Risk-adjusted returns (0.43)
- Maximum Drawdown analysis (9.49%)

### Algorithmic Trading
- MA Crossover System with RSI confirmation
- Dynamic Position Sizing based on volatility
- Comprehensive Backtesting framework
- Performance analytics and visualization

## 📈 Performance Results

| Metric | Buy & Hold | Strategy |
|---------|------------|----------|
| **Total Return** | 6.91% | -7.67% |
| **Win Rate** | - | 17.62% |
| **Total Trades** | - | 84 |
| **Best Month** | 13.69% | - |
| **Worst Month** | -9.49% | - |

## 🔍 Key Insights

- **Market Regime Impact**: Range-bound 2023 market challenged trend strategies
- **Strategy Limitations**: MA crossovers underperform in low-trend environments  
- **Risk Management**: Essential during strategy drawdown periods
- **Real-world Validation**: Professional-grade backtesting implementation

## 🛠️ Technical Stack

```python
# Dependencies
yfinance==0.2.18    # Market data
pandas==2.0.3       # Data analysis  
numpy==1.24.3       # Numerical computing
matplotlib==3.7.2   # Visualization
seaborn==0.12.2     # Statistical graphics
```

## 🚀 Quick Start


# Clone repository
git clone https://github.com/sidharth-choudhary786/SBI_Stock_Analyzer.git
cd SBI_Stock_Analyzer

# Install dependencies  
```bash
pip install -r requirements.txt
```
# Run analysis
```bash
python sbi_analysis.py
```


