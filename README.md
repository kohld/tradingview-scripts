# TradingView Scripts

A collection of Pine Script indicators and strategies for TradingView, focusing on technical analysis and value investing approaches.

## 📊 Scripts Overview

### 1. 200 EMA with Trend Color (`200-ema-with-trend-color.pine`)

A visual indicator that displays the 200-period Exponential Moving Average with dynamic color coding based on price position.

**Features:**
- 200 EMA line that changes color based on trend direction
- Green when price is above EMA (bullish trend)
- Red when price is below EMA (bearish trend)
- Optional background color for enhanced visualization
- Customizable EMA length (default: 200)

**Use Case:** Ideal for identifying long-term trend direction and potential support/resistance levels.

### 2. Buffett-Inspired Value Strategy (`buffett-inspired-value-strategy.pine`)

A systematic trading strategy inspired by Warren Buffett's value investing principles, combining technical indicators with value-focused entry criteria.

**Features:**
- **Entry Logic:** Buy when price is 5% below 200 EMA AND RSI is oversold (<30)
- **Risk Management:** Configurable take profit (default: 10%) and stop loss (default: 5%)
- **Margin of Safety:** Requires significant discount to fair value (EMA) before entry
- **Alert System:** Automated buy signal alerts
- **Visual Signals:** Buy/sell markers on chart

**Parameters:**
- EMA Length: 200 (adjustable)
- RSI Length: 14
- RSI Oversold Level: 30
- RSI Overbought Level: 70
- Take Profit: 10%
- Stop Loss: 5%

**Philosophy:** Combines Buffett's "buy below fair value" approach with technical confirmation through RSI oversold conditions.

## 🚀 How to Use

1. **Installation:**
   - Open TradingView
   - Go to Pine Editor
   - Copy and paste the desired script
   - Click "Add to Chart"

2. **Customization:**
   - Adjust input parameters according to your trading style
   - Modify colors and visual elements as needed
   - Test different timeframes for optimal results

3. **Best Practices:**
   - Use the 200 EMA indicator on daily or higher timeframes
   - Backtest the Buffett strategy before live trading
   - Consider market conditions and fundamental analysis alongside technical signals

## 📈 Recommended Usage

- **200 EMA Indicator:** Best on daily, weekly, or monthly charts for trend identification
- **Buffett Strategy:** Suitable for swing trading and long-term position building on daily charts

## ⚠️ Disclaimer

These scripts are for educational and informational purposes only. Past performance does not guarantee future results. Always conduct your own research and consider your risk tolerance before making investment decisions.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Feel free to fork this repository and submit pull requests with improvements or additional scripts. Please ensure all contributions follow Pine Script best practices and include proper documentation.
