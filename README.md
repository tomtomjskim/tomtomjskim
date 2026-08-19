# 김정식 · TOM

> **I build systems, developer tools, and experiments that make complex work easier to understand and operate.**

복잡한 업무 규칙과 오래 운영되는 시스템을 이해 가능한 구조로 정리하는 일을 좋아합니다.  
백엔드 시스템을 중심으로 일하며, 반복되는 개발 작업을 줄이는 내부도구와 검증 가능한 AI 활용 방식도 함께 만들고 있습니다.

## Explore

- **[Engineering Portfolio](https://github.com/tomtomjskim/portfolio)**
- [General Backend](https://github.com/tomtomjskim/portfolio/blob/main/PORTFOLIO.md)
- [AI-assisted / Internal Tools](https://github.com/tomtomjskim/portfolio/blob/main/PORTFOLIO-AX.md)

## What I build

- 운영 중인 업무시스템의 변경 영향을 확인하고 안전하게 개선하는 백엔드 기능
- 모호한 업무 요청을 상태·데이터·권한·인터페이스 조건으로 바꾸는 설계
- 반복되는 설정과 검증을 줄이는 개발자 도구
- LLM·일반 코드·사람 검수의 책임을 나눈 실용적 자동화

## Selected case studies

| Case | Focus |
|---|---|
| [Commerce / Logistics Change Impact](https://github.com/tomtomjskim/portfolio/blob/main/cases/commerce-change-impact.md) | 화면 증상 뒤의 DB 상태·권한·관리자·batch·외부 연동 범위를 추적 |
| [Manufacturing MES Requirement Modeling](https://github.com/tomtomjskim/portfolio/blob/main/cases/mes-requirement-modeling.md) | 현장 요청을 입력·조회·상태·통계·권한·DB 규칙으로 분해 |
| [Practical AI Automation](https://github.com/tomtomjskim/portfolio/blob/main/cases/practical-ai-automation.md) | Local LLM·일반 코드·사람 판단의 책임 경계를 실제 반복 업무에 적용 |

## Public engineering

### Systems and evidence

- [stackforge-atlas](https://github.com/tomtomjskim/stackforge-atlas) — 제품 의도에서 인터페이스·검증 근거·복구 경계까지 연결하는 engineering atlas

### Developer tooling and workflow

- [harness-kit](https://github.com/tomtomjskim/harness-kit) — 프로젝트별 AI coding 설정을 모듈과 재현 가능한 build로 관리하는 internal tool
- [codex-workflow-skills](https://github.com/tomtomjskim/codex-workflow-skills) — intake·독립 검토·실패 상태·완료 검증을 분리한 Workflow Skills
- [claude-code-guide](https://github.com/tomtomjskim/claude-code-guide) — Skill·Hook·Agent·Handoff·Failure Recovery 운영 가이드와 템플릿

## Engineering principles

- 눈에 보이는 증상부터 고치기보다 **변경 영향 범위**를 먼저 확인합니다.
- 암묵적인 업무 규칙을 상태·데이터·권한·인터페이스로 드러냅니다.
- 반복 가능한 부분은 자동화하되 판단이 필요한 경계에는 사람의 검수를 남깁니다.
- 테스트와 CI는 근거로 사용하지만 배포·채택·성과를 대신하는 수치로 확대하지 않습니다.
- 공개 R&D와 실제 업무 경험의 역할을 구분합니다.

## Current interests

Backend systems · Business systems · Developer tools · Internal tooling · AI-assisted engineering
