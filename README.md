# 📊 ESG 경영 종합 대시보드 (ESG Executive Dashboard)

> C-Level 및 ESG 담당자를 위한 실시간 ESG 지표 시각화 및 AI 분석 대시보드

---

## 1. 🎯 프로젝트 개요
- **개발 기간**: 202X.XX ~ 202X.XX
- **인원**: 1인 개인 프로젝트
- **주요 목적**: 기업 비재무적 지표(E·S·G) 모니터링, 공시 데이터 관리 및 AI 코파일럿을 통한 인사이트 제공

## 2. 🛠 기술 스택
- **Frontend**: React / TypeScript / Tailwind CSS / Recharts
- **Backend/DB**: [사용하신 백엔드 스택] / [사용하신 로컬 DB 스택]
- **AI & Workflow**: VS Code, MCP (Model Context Protocol), Claude

## 3. 📐 시스템 구조 및 기획 명세
- **[기획 및 UI/UX 사양서 (v2.0)](./ESG_대시보드_전체화면_사양서_v2.md)**
- **DB ERD 구조**: [DB 구조 이미지/링크]
- **주요 레이아웃**: 3열 구조 (Left Navigation Bar - Main Board - Right AI Assistant)

## 4. ✨ 핵심 기능 및 화면
1. **L1. 종합 현황 모니터링**: E/S/G 종합 점수 및 달성률 시각화
2. **로컬 DB 데이터 실시간 연동**: ~데이터 CRUD 및 스키마 연동
3. **AI 대화형 인사이트 패널**: 대시보드 데이터 기반 질의응답 UI

## 5. 💡 기술적 도전 및 해결 (Troubleshooting)
- **[이슈 1]** 로컬 DB 스키마와 사양서 UI 컴포넌트 간 데이터 매핑 구조 설계
  - *해결*: ~
- **[이슈 2]** 다크 테마 기반 디자인 시스템(Design System) 토큰화 및 공통 컴포넌트 재사용성 확보
  - *해결*: CSS 변수 기반 전역 토큰 설계
