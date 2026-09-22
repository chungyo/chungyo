# 안녕하세요, 김충영입니다 👋

**직접 개발해 온 경험을 바탕으로, 고객의 문제를 구체화하고 제품으로 만듭니다.**

PlaidLabs를 함께 창업해 프론트엔드 개발과 PM 업무를 맡고 있습니다. 고객과 요구사항·일정·개발 범위를 조율하고, React·TypeScript로 직접 구현합니다. 개발 중 드러난 예외와 제약은 다시 기획에 반영합니다.

요즘은 AI를 업무에 어떻게 써야 도움이 될지 고민하고 있습니다. 개발에 필요한 맥락을 문서로 연결하고, 반복되는 확인 작업은 자동화하며, 제가 쓰면서 불편했던 점을 하나씩 바꾸고 있습니다.

[Portfolio](https://chungyo.github.io/) · [Email](mailto:chungyoung.kim98@gmail.com)

## PlaidLabs

**공동창업 · Frontend Development & Product Management** · 2025.06 – 현재

- **리더스클럽 예약 관리 서비스** — 현장 예약과 온라인 예약을 따로 확인하던 업무를 한 화면에서 처리할 수 있도록 만들었습니다. 기획·화면 구성·UI 개발·API 연동을 맡아 약 2주 만에 첫 사용 가능한 버전을 구현했습니다.

- **심케어 3.0 · 1minute PM** — 고객 미팅과 일정·범위 조율을 맡았습니다. 심케어에서는 고객 요구사항, 기능·화면 명세, 회의 결정을 GitHub에 연결해 개발자가 구현에 필요한 정책과 예외 조건을 찾아볼 수 있도록 정리했습니다. 현재 심케어는 개발·검증을 진행하고 있습니다.

- **API 연동 현황 자동화** — 심케어의 API 명세와 프론트엔드 코드를 대조해 연동 현황을 집계하고, GitHub CI와 Confluence로 공유하도록 구성했습니다. 코드상 연동 여부와 실제 API 검증 여부를 구분해 확인할 수 있도록 했습니다.

- **공통 UI 개발** — 여러 제품에서 사용할 디자인 시스템을 개발하고 npm 패키지로 배포했습니다. 이미지 용량과 로딩 방식을 개선하고, UI와 상태 처리 과정에서 발생하는 문제를 해결해 왔습니다.

## Projects

### HASHI

**일본 맛집 발견·예약 서비스 · 프론트엔드 개발**

예약·포인트·관리자 기능을 개발하고, 중복 요청과 인증 복구 흐름을 개선했습니다.

기존 코드 생성 스크립트를 확장해 컴포넌트와 명세·Storybook 파일을 함께 생성하도록 했습니다. API 연동과 검증 절차를 AI 작업 지침으로 정리하고, 실제 개발과 코드리뷰에서 발견한 문제를 반영하고 있습니다.

[서비스](https://www.hashi.kr/) · [생성기 개선](https://github.com/TEAM-HASHI/HASHI-CLIENT/pull/23) · [예약 기능](https://github.com/TEAM-HASHI/HASHI-CLIENT/pull/94) · [코드리뷰](https://github.com/TEAM-HASHI/HASHI-CLIENT/pull/91#discussion_r3567665980)

### LLM Wiki

**업무 기록과 일정을 연결하는 개인 지식 시스템**

따로 일기를 쓰지 않아도 일상과 업무 기록을 남기고, 예전에 내린 결정을 다시 찾고 싶어 만들었습니다. 조사한 자료와 업무 기록을 Obsidian에 출처와 함께 모으고, 원본·일일 기록·정리된 지식을 나눠 연결합니다.

Google Calendar·Tasks와 Telegram을 연동해 아침과 저녁에 일정을 확인하고 대화할 수 있도록 구성했습니다. 실제로 과거 업무 결정을 다시 찾고 하루 일정을 챙기는 데 사용하고 있습니다.

## Open Source

**[Toss · react-simplikit](https://github.com/toss/react-simplikit)**

React 훅의 버그를 재현하고, 수정과 회귀 테스트에 기여했습니다.

| 기여 | PR |
| --- | --- |
| `useStorageState` — 다른 탭에서 저장소 전체 삭제 시 상태가 동기화되지 않는 문제 수정 | [#482 · Merged](https://github.com/toss/react-simplikit/pull/482) |
| `useRefEffect` — 의존성 변경 시 갱신된 콜백이 반영되지 않는 문제 수정 | [#483 · Merged](https://github.com/toss/react-simplikit/pull/483) |

## Community

**[SOPT](https://www.sopt.org/) · 38기 YB** · 2026.03 참여

대학생 연합 IT 벤처 창업 동아리에서 서비스 개발과 팀 프로젝트에 참여했습니다.

**[구름톤 유니브](https://9oormthon.university/)** · 2024.09 – 2025.06

3기 운영진을 거쳐 4기 교내 대표 및 서울 동부 지부 대표로 활동했습니다. 14개 대학 연합 프로젝트 **성장톤**을 기획하고, 첫 프로젝트에 도전하는 참가자들을 위해 팀 구성과 협업 기준, 성과 발표회를 준비했습니다.

## Tech & Tools

| 분야 | 주로 사용하는 기술과 도구 |
| --- | --- |
| Development | TypeScript, JavaScript, React, Next.js, React Native, TanStack Query |
| Testing | Vitest, Testing Library, Playwright |
| Collaboration | GitHub, Jira, Confluence, Slack |
| AI & Knowledge | Codex, Claude Code, Obsidian |
