📊 QuantScope – Live Market Analytics Platform

The QuantScope Live Market Analytics Platform is a real-time cryptocurrency analytics application designed to provide traders and quantitative researchers with fast, interpretable statistical insights into market behavior.

Instead of focusing on price prediction, QuantScope emphasizes market monitoring, statistical signals, and anomaly detection, making it suitable for exploratory analysis, intraday monitoring, and research-driven decision support.

🚀 Core Features
📈 Market Visualization

Interactive candlestick charts with OHLC data

Volume analysis aligned with price action

Smooth zoom, pan, and hover-based exploration using Plotly

⏱️ Timeframe & Aggregation Controls

Historical Timeframe Selection:

Last 24 Hours

Last 3 Days

Last Week

Last Month

Sampling / Aggregation Options:

Raw data

1-minute candles

5-minute candles

This design allows users to independently control how much data they view and how finely it is aggregated.

📊 Statistical & Quantitative Analytics

Price Spread

Captures short-term deviations using lagged price differences

Z-Score Analysis

Identifies statistically significant movements relative to recent history

Rolling Correlation

Tracks evolving relationships in short-term price behavior

These metrics are commonly used in mean-reversion strategies, signal detection, and regime analysis.

🚨 Rule-Based Alerts

User-defined Z-score thresholds

Visual alerts triggered when deviations exceed statistical limits

Helps highlight abnormal market behavior in real time

📁 Data Export

Export analytics-enhanced datasets as CSV files

Enables offline analysis, reporting, or strategy research

🛠️ Technology Stack

Programming Language: Python

Frontend & Backend: Streamlit

Market Data Source: Coinbase Exchange REST API

Data Processing: Pandas, NumPy

Visualization: Plotly

🧠 Design Philosophy

QuantScope is designed with a modular analytics pipeline, separating:

Market data ingestion

Sampling and aggregation

Statistical analytics

Visualization and alerting

This structure allows easy extension to:

WebSocket-based tick feeds

Multi-asset analytics

Additional statistical tests and indicators

🤖 ChatGPT Usage Transparency

ChatGPT was used as a development assistant to:

Help structure the system architecture

Assist with code scaffolding and refactoring

Validate statistical logic

Improve documentation clarity

All final implementation and testing decisions were made by the project author.

⚠️ Disclaimer

This project is intended for educational and research purposes only and does not constitute financial or investment advice.
