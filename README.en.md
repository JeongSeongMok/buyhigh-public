<div align="center">

<img src="resources/logo/favicon.ico" width="72" alt="BuyHigh logo" />

# BuyHigh

**Free AI Stock Analysis Platform**

From chart & valuation analysis to AI reports — all in one place.

[![Live](https://img.shields.io/badge/live-buyhigh.cc-2ea44f?style=flat-square)](https://buyhigh.cc)
![Status](https://img.shields.io/badge/source-private-lightgrey?style=flat-square)
![Java](https://img.shields.io/badge/Java-21-orange?style=flat-square)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5-6DB33F?style=flat-square)

🔗 **[https://buyhigh.cc](https://buyhigh.cc)**

[한국어](README.md) · **English** · [日本語](README.ja.md)

</div>

---

> ⚠️ **This repository is for the project introduction (README) only.**
> BuyHigh's source code is private, and no code is included in this repository.
> You can use the service directly at the link above.

---

## About

**BuyHigh** is a web platform that provides **free AI analysis reports** for Korean, US and Japan stocks.
It turns complex charts and financial metrics into reports anyone can understand.

## Features

- **Chart AI Analysis** — Combines trend, momentum, volatility, and supply/demand to call a position (bullish · neutral · bearish) and market phase, with support/resistance levels and an action plan
- **Valuation AI Analysis** — Assesses growth, financial health, and enterprise value, computing a fair-price band and an under/over-valuation verdict
- **Trade Signals** — Synthesizes chart and valuation reports into buy/hold/sell recommendations, with return tracking since the signal date
- **Korean & US Stocks** — The same analysis for KOSPI · KOSDAQ and NASDAQ · NYSE · AMEX tickers
- **Interactive Charts** — Stock detail charts with moving averages, Bollinger Bands, Ichimoku, RSI, and more
- **Daily Free Feed** — Reports for top-traded stocks auto-generated every day, open to everyone with no sign-up
- **Multi-LLM Agents** — Gemini and GPT agents query price, flow, fundamentals, and news data directly to write each report

## Screenshots

### Home
<div align="center">
<img src="resources/screenshots/main.png" width="280" align="top" alt="Home — indices & FX, chart/valuation entry, trade recommendations" />
</div>

### Analysis
<div align="center">
<img src="resources/screenshots/chart.png" width="280" align="top" alt="Chart analysis — candles, moving averages, volume with AI report" />
<img src="resources/screenshots/valuation.png" width="280" align="top" alt="Valuation analysis — key-metric valuation with AI report" />
</div>

## Tech Stack

| Area | Technologies |
|------|-----------|
| Backend | Java 21, Spring Boot 3.5, Spring WebFlux, Spring Security |
| AI | Spring AI (OpenAI · Google GenAI), MCP Server |
| Frontend | Thymeleaf, HTML/CSS/JS |
| Data | Redis (session · cache) |
| Infra | Docker, Nginx, Cloudflare Tunnel |

## License · Source

The source code is private (All rights reserved), and no code is included in this repository.
For service-related inquiries, please open an issue.

---

<div align="center">

Made with ☕ by [JeongSeongMok](https://github.com/JeongSeongMok)

</div>
