<div align="center">

<img src="resources/logo/favicon.ico" width="72" alt="BuyHigh logo" />

# BuyHigh

**無料の株式AI分析プラットフォーム**

チャート・バリュエーション分析からAIレポートまで、ひとつの場所で。

[![Live](https://img.shields.io/badge/live-buyhigh.cc-2ea44f?style=flat-square)](https://buyhigh.cc)
![Status](https://img.shields.io/badge/source-private-lightgrey?style=flat-square)
![Java](https://img.shields.io/badge/Java-21-orange?style=flat-square)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5-6DB33F?style=flat-square)

🔗 **[https://buyhigh.cc](https://buyhigh.cc)**

[한국어](README.md) · [English](README.en.md) · **日本語**

</div>

---

> ⚠️ **このリポジトリはプロジェクト紹介（README）専用です。**
> BuyHigh のソースコードは非公開であり、本リポジトリにはコードは含まれていません。
> サービスは上記のリンクから直接ご利用いただけます。

---

## 概要

**BuyHigh** は、韓国株の銘柄に対して **無料のAI分析レポート** を提供するWebプラットフォームです。
複雑なチャートや財務指標を、誰にでも理解できる分析レポートに変換します。

## 主な機能

- **チャート分析** — ローソク足・移動平均・出来高をAIが自然言語のレポートに解釈し、対応方針を提示
- **バリュエーション分析** — PER・PBR・ROE などの主要指標に基づく価値判断とリスク要因の整理
- **銘柄推奨** — データに基づく売買アイデアと、ポジション・レンジのインサイト
- **AIレポート** — 複数のLLM（GPT・Gemini）による銘柄分析の自動生成
- **無料分析フィード** — 毎日更新されるチャート／バリュエーションの無料分析リスト

## スクリーンショット

### ホーム・指数
<div align="center">
<img src="resources/screenshots/home.png" width="280" alt="ホーム — 指数・為替、チャート／バリュエーション分析への導線、売買推奨" />
<img src="resources/screenshots/market-indices.png" width="280" alt="主要指数 — KOSPI・NASDAQ・S&P500 などとドル/ウォン為替" />
</div>

### チャート
<div align="center">
<img src="resources/screenshots/chart-basic.png" width="280" alt="基本 — ローソク足・移動平均・出来高・RSI" />
<img src="resources/screenshots/chart-supply.png" width="280" alt="需給 — プログラム・純買い越し推移" />
<img src="resources/screenshots/chart-trend.png" width="280" alt="トレンド — 相対強度・オプションMax Pain・52週位置" />
</div>

### バリュエーション
<div align="center">
<img src="resources/screenshots/valuation-fundamental.png" width="280" alt="ファンダメンタル — 予想実績・EPS・PER" />
<img src="resources/screenshots/valuation-sector.png" width="280" alt="セクター・テーマ — テーマ構成銘柄" />
<img src="resources/screenshots/valuation-disclosure.png" width="280" alt="ニュース・開示 — 自社株・開示内容" />
</div>

### 分析
<div align="center">
<img src="resources/screenshots/chart-ai-analysis.png" width="280" alt="チャートAI分析 — チャートに基づく対応方針レポート" />
<img src="resources/screenshots/valuation-ai-analysis.png" width="280" alt="バリュエーションAI分析 — 適正株価・総合判断レポート" />
</div>

## 技術スタック

| 領域 | 使用技術 |
|------|-----------|
| Backend | Java 21, Spring Boot 3.5, Spring WebFlux, Spring Security |
| AI | Spring AI (OpenAI · Google GenAI), MCP Server |
| Frontend | Thymeleaf, HTML/CSS/JS |
| Data | Redis（セッション・キャッシュ） |
| Market Data | 韓国投資証券 Open API |
| Infra | Docker, Nginx, Cloudflare Tunnel |

## ライセンス・ソース

ソースコードは非公開（All rights reserved）であり、本リポジトリにはコードは含まれていません。
サービスに関するお問い合わせは Issue にてお願いします。

---

<div align="center">

Made with ☕ by [JeongSeongMok](https://github.com/JeongSeongMok)

</div>
