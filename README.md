# 📈 Market Trend Analyzer - TradingView Indicator

The **Market Trend Analyzer** is a visual Pine Script indicator for TradingView that identifies market trends (Uptrend, Downtrend, or Consolidation) based on moving averages, ADX strength, and price range compression. It provides an intuitive overlay with real-time data metrics and color-coded context for rapid decision-making.

---

## 🔍 Features

- 🧭 **Trend Detection**:
  - Uptrend: Fast MA > Slow MA, price above Fast MA, strong ADX
  - Downtrend: Fast MA < Slow MA, price below Fast MA, strong ADX
  - Consolidation: Based on narrow price range or weak ADX

- 🎨 **Visual Tools**:
  - Background color shading based on detected trend
  - End-of-chart label showing current market condition
  - Table with ADX values, price range, and market state

- ⚙️ **Customization Options**:
  - Choose between SMA, EMA, or WMA for moving averages
  - Adjustable lookback periods, threshold levels, and MA lengths
  - Clean overlay for both intraday and swing timeframes

---

## 🧠 How It Works

- Uses ADX and DMI to assess trend strength
- Compares Fast and Slow MA alignment
- Evaluates price range compression for consolidation detection
- Automatically updates at last bar to reflect live market state

---

## 🛠 Inputs Explained

| Input                   | Description                                   |
|------------------------|-----------------------------------------------|
| `Moving Average Type`   | Choose between EMA, SMA, WMA                 |
| `Fast / Slow MA`        | Trend speed filtering via MA lengths         |
| `ADX Threshold`         | Minimum ADX level required for trend         |
| `Consolidation %`       | Determines range compression threshold       |
| `Trend Lookback Period` | Lookback window for range calculation        |

---

## 📈 Visual Outputs

- Fast MA (blue line)
- Slow MA (purple line)
- Market trend label (Uptrend / Downtrend / Consolidation)
- Background tint for instant context
- Bottom-right table with live metrics

---

## 🧑‍💻 Author

Developed by [Rao Aksee Nasir], strategic thinker blending AI automation and global tech solutions for market intelligence.

---

## 📄 License

MIT License — open for community use, attribution appreciated.

---

## 💬 Contributions

Found a bug or want new features? Submit a pull request or open an issue to help improve!
