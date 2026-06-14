<div align="center">

<img src="resources/logo/favicon.ico" width="72" alt="BuyHigh logo" />

# BuyHigh

**무료 주식 AI 분석 플랫폼**

차트 · 밸류에이션 분석부터 AI 리포트까지, 한 곳에서.

[![Live](https://img.shields.io/badge/live-buyhigh.cc-2ea44f?style=flat-square)](https://buyhigh.cc)
![Status](https://img.shields.io/badge/source-private-lightgrey?style=flat-square)
![Java](https://img.shields.io/badge/Java-21-orange?style=flat-square)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5-6DB33F?style=flat-square)

🔗 **[https://buyhigh.cc](https://buyhigh.cc)**

**한국어** · [English](README.en.md) · [日本語](README.ja.md)

</div>

---

> ⚠️ **이 레포지토리는 소개(README) 전용입니다.**
> BuyHigh의 소스 코드는 비공개이며, 본 레포에는 코드가 포함되어 있지 않습니다.
> 서비스는 위 링크에서 직접 이용하실 수 있습니다.

---

## 소개

**BuyHigh**는 국내 주식 종목에 대한 **무료 AI 분석 리포트**를 제공하는 웹 플랫폼입니다.
복잡한 차트와 재무 지표를, 누구나 이해할 수 있는 분석 리포트로 풀어냅니다.

## 주요 기능

- **차트 분석** — 캔들·이동평균·거래량을 AI가 자연어 리포트로 해석하고 대응 방안 제시
- **밸류에이션 분석** — PER·PBR·ROE 등 핵심 지표 기반의 가치 판단과 리스크 요인 정리
- **종목 추천** — 데이터 기반 매매 추천과 포지션·구간 인사이트
- **AI 리포트** — 멀티 LLM(GPT·Gemini) 기반의 종목 분석 자동 생성
- **무료 분석 피드** — 매일 갱신되는 차트/밸류에이션 무료 분석 리스트

## 스크린샷

### 홈
<div align="center">
<img src="resources/screenshots/main.png" width="280" alt="홈 화면 — 지수, 무료 분석 진입, 매매 추천" />
</div>

### 차트 분석
<div align="center">
<img src="resources/screenshots/chart-main.png" width="280" alt="종목 차트 — 캔들·이동평균·거래량" />
<img src="resources/screenshots/chart-analysis.png" width="280" alt="차트 AI 분석 — 대응 방안 리포트" />
</div>

### 밸류에이션 분석
<div align="center">
<img src="resources/screenshots/valuation-main.png" width="280" alt="밸류에이션 — 펀더멘탈 핵심 지표" />
<img src="resources/screenshots/valuation-analysis.png" width="280" alt="밸류에이션 AI 분석 — 종합 판단 리포트" />
</div>

### 무료 분석 피드
<div align="center">
<img src="resources/screenshots/free-chart.png" width="280" alt="무료 차트 분석 리스트" />
<img src="resources/screenshots/free-valuation.png" width="280" alt="무료 밸류에이션 분석 리스트" />
</div>

## 기술 스택

| 영역 | 사용 기술 |
|------|-----------|
| Backend | Java 21, Spring Boot 3.5, Spring WebFlux, Spring Security |
| AI | Spring AI (OpenAI · Google GenAI), MCP Server |
| Frontend | Thymeleaf, HTML/CSS/JS |
| Data | Redis (세션·캐시) |
| Market Data | 한국투자증권 Open API |
| Infra | Docker, Nginx, Cloudflare Tunnel |

## 라이선스 · 소스

소스 코드는 비공개(All rights reserved)이며, 이 레포에는 코드가 포함되어 있지 않습니다.
서비스 관련 문의는 이슈로 남겨주세요.

---

<div align="center">

Made with ☕ by [JeongSeongMok](https://github.com/JeongSeongMok)

</div>
