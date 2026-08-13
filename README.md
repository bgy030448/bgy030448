# Gayeon Baek | 백가연

IT Service Planner turning product decisions into buildable systems.

제품의 의도를 구현 가능한 요구사항·정책·데이터/API·검증 기준으로 바꾸는 IT 서비스 기획자입니다. 프론트엔드 구현 경험을 바탕으로 기획과 개발 사이의 빈틈을 줄입니다.

[Portfolio](https://it-planner-portfolio-gayeonbaek.sungwonhong.chatgpt.site) · [LinkUs 기획서](https://www.notion.so/LinkUs-IT-3ba807266361817bae22c40d0f20037f?source=copy_link) · [Questlog 기획서](https://www.notion.so/Questlog-IT-3bb807266361813d944ae247870f46d8?source=copy_link) · [Email](mailto:bgy030448@naver.com)

---

## Selected Work | 주요 프로젝트

### LinkUs — Location-first Local Community `Delivered`

내 주변의 게시물·대화·운영이 하나의 지도 맥락에서 이어진다면?

프론트엔드 담당으로 시작해 요구사항 정리, 화면 정책, 예외 처리, 통합 QA까지 역할을 확장했습니다.

| Product Definition | Delivery Scope | Implementation | Validation |
|:---:|:---:|:---:|:---:|
| 59 requirements | 35 / 98 WBS | 78 non-merge commits | 5 end-to-end flows |
| Screen · Route · Data · API · Acceptance | Planning · UX · Frontend · QA | 57 files · 19,649 changed lines | Auth · Post · Chat · Trust · Admin |

- 열람은 Guest에게 열고 작성·좋아요·신고 시점에 인증을 요구하도록 정책을 나눴습니다.
- MySQL은 영구 원장, Redis는 최근·위치 정보 인덱스로 책임을 분리했습니다.
- `Initial · Empty · Loaded · Submitting · Failed · Forbidden` 상태와 복구 행동을 정의했습니다.
- Frontend production build와 5개 핵심 여정을 확인했습니다. 번들 최적화·Backend 테스트 환경·자동 E2E는 남은 과제입니다.

[Planning Source](https://www.notion.so/LinkUs-IT-3ba807266361817bae22c40d0f20037f?source=copy_link) · [Repository](https://github.com/JephyrWing/project_linkus) · [Portfolio Case](https://it-planner-portfolio-gayeonbaek.sungwonhong.chatgpt.site/projects/project-01)

### Questlog — Recovery-centered AI Routine `In Progress`

완벽한 연속 기록보다, 실패 후 48시간 안에 다시 돌아오는 경험을 설계합니다.

UX·Visual 방향을 맡고 기획과 프론트엔드 구현을 공동으로 수행하며, 회복 선택지와 접근성 기준, AI 제안과 규칙 기반 판단의 경계를 설계하고 있습니다.

| Product Definition | My Delivery Scope | Contribution | Data & Permission Policy |
|:---:|:---:|:---:|:---:|
| 124 requirements | 11 owned + 18 shared WBS | 19 GitHub contributions | 13 tables · 26 RLS · 19 events |
| Acceptance · WBS · Test IDs | UX · Visual · Frontend · QA | 개인 기여 기록 | 동의 기반 분석 · PII 제외 |

- 하루 퀘스트를 최대 3개로 제한하고, 5–10분 회복 버전·무감점 보류·내일 이동을 제공합니다.
- AI는 목표 분해와 난이도를 제안하고, 보상·상태·권한은 예측 가능한 Server/Rule이 결정합니다.
- 분석 동의 이후에만 이벤트를 수집하며 목표·메모·이메일은 분석 속성에서 제외합니다.
- Planned scope, implemented code, test evidence, user outcome을 서로 다른 근거로 구분합니다.

[Planning Source](https://www.notion.so/Questlog-IT-3bb807266361813d944ae247870f46d8?source=copy_link) · [Repository](https://github.com/jongshh/reminder) · [Portfolio Case](https://it-planner-portfolio-gayeonbaek.sungwonhong.chatgpt.site/projects/project-02)

---

## How I Work | 일하는 방식

```text
Problem → Success Signal → Requirement → State & Policy → Data/API → Acceptance → QA
```

- 화면을 그리기 전에 무엇을 `Done`으로 볼지 먼저 정의합니다.
- Happy path뿐 아니라 Empty·Loading·Failed·Forbidden·Recovery 상태를 함께 설계합니다.
- 검토한 대안, 선택 이유, 감수한 Trade-off, 아직 부족한 Evidence를 기록합니다.
- 구현 수치를 사용자 성과처럼 표현하지 않습니다.

## Working Context | 협업 영역

Product — Requirements · IA · User Flow · Feature Policy · WBS · Acceptance Criteria · QA  
Technical — React · JavaScript · REST API · Spring Boot · MySQL · Redis · Supabase · PostgreSQL · RLS

---

기획 의도부터 구현 세부사항까지 함께 연결할 기획자를 찾고 있다면 [bgy030448@naver.com](mailto:bgy030448@naver.com)으로 연락해 주세요.
