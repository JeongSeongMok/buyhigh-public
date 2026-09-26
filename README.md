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

**BuyHigh**는 국내·미국·일본 주식 종목에 대한 **무료 AI 분석 리포트**를 제공하는 웹 플랫폼입니다.
복잡한 차트와 재무 지표를, 누구나 이해할 수 있는 분석 리포트로 풀어냅니다.

## 주요 기능

- **차트 AI 분석** — 추세·모멘텀·변동성·수급을 종합해 포지션(상방·중립·하방)과 구간을 판단하고, 지지·저항선과 대응 방안 제시
- **가치(밸류에이션) AI 분석** — 성장성·재무상태·기업가치를 평가하고 적정주가 밴드를 산출해 저평가/고평가 판단
- **매매 추천** — 차트·가치 분석을 종합한 매수/관망/매도 시그널과 추천 시점 이후 수익률 추적
- **국내·미국 주식 지원** — KOSPI·KOSDAQ부터 NASDAQ·NYSE·AMEX 종목까지 동일한 분석 제공
- **인터랙티브 차트** — 이동평균·볼린저밴드·일목균형표·RSI 등 지표를 갖춘 종목 상세 차트
- **매일 무료 분석 피드** — 거래대금 상위 종목의 리포트를 매일 자동 생성, 로그인 없이 누구나 열람
- **멀티 LLM 에이전트** — Gemini·GPT 에이전트가 시세·수급·재무·뉴스 데이터를 직접 조회해 리포트 작성

## 스크린샷

### 메인
<div align="center">
<img src="resources/screenshots/main.png" width="280" align="top" alt="메인 — 지수·환율, 차트/밸류 분석 진입, 매매 추천" />
</div>

### 분석
<div align="center">
<img src="resources/screenshots/chart.png" width="280" align="top" alt="차트 분석 — 캔들·이동평균·거래량과 AI 리포트" />
<img src="resources/screenshots/valuation.png" width="280" align="top" alt="가치 분석 — 핵심 지표 기반 밸류에이션과 AI 리포트" />
</div>

## 기술 스택

| 영역 | 사용 기술 |
|------|-----------|
| Backend | Java 21, Spring Boot 3.5, Spring WebFlux, Spring Security |
| AI | Spring AI (OpenAI · Google GenAI), MCP Server |
| Frontend | Thymeleaf, HTML/CSS/JS |
| Data | Redis (세션·캐시) |
| Infra | Docker, Nginx, Cloudflare Tunnel |

## 라이선스 · 소스

소스 코드는 비공개(All rights reserved)이며, 이 레포에는 코드가 포함되어 있지 않습니다.
서비스 관련 문의는 이슈로 남겨주세요.

---

<div align="center">

Made with ☕ by [JeongSeongMok](https://github.com/JeongSeongMok)

</div>
