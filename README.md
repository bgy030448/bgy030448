# Gayeon Baek

**IT Service Planner turning product decisions into buildable systems.**

I work between product planning and frontend implementation—defining the requirement, user state, permission, data/API handoff, and acceptance criteria that a team needs to ship with fewer assumptions.

[Portfolio](https://it-planner-portfolio-gayeonbaek.sungwonhong.chatgpt.site) · [LinkUs case study](https://www.notion.so/LinkUs-IT-3ba807266361817bae22c40d0f20037f?source=copy_link) · [Questlog case study](https://www.notion.so/Questlog-IT-3bb807266361813d944ae247870f46d8?source=copy_link) · [Email](mailto:bgy030448@naver.com)

---

## Selected work

### LinkUs — Location-first local community `Delivered`

**What if nearby posts, conversations, and moderation shared one map context?**

I joined as a frontend contributor and expanded my scope into product planning, interaction policy, exception handling, and cross-functional QA.

| Product definition | Delivery contribution | Implementation evidence | Validation |
|:---:|:---:|:---:|:---:|
| **59 requirements** | **35 / 98 WBS items** | **78 non-merge commits** | **5 end-to-end flows** |
| Screen · Route · Data · API · Acceptance | Planning · UX · Frontend · QA | 57 files · 19,649 changed lines | Auth · Post · Chat · Trust · Admin |

- Opened browsing to guests; required authentication only at write, like, and report actions.
- Separated MySQL as the durable source of truth and Redis as the recent/location index.
- Defined `Initial · Empty · Loaded · Submitting · Failed · Forbidden` states with recovery actions.
- Verified the frontend production build; bundle optimization, backend test setup, and automated E2E remain open.

[Planning source](https://www.notion.so/LinkUs-IT-3ba807266361817bae22c40d0f20037f?source=copy_link) · [Repository](https://github.com/JephyrWing/project_linkus) · [Portfolio case](https://it-planner-portfolio-gayeonbaek.sungwonhong.chatgpt.site/projects/project-01)

### Questlog — Recovery-centered AI routine `In progress`

**The goal is not a perfect streak. It is returning within 48 hours after a miss.**

I own UX and visual direction while sharing product planning and frontend delivery—designing recovery choices, feedback states, accessibility criteria, and the boundary between AI suggestions and deterministic rules.

| Product definition | My delivery scope | Contribution evidence | Data & permission policy |
|:---:|:---:|:---:|:---:|
| **124 requirements** | **11 owned + 18 shared WBS** | **19 GitHub contributions** | **13 tables · 26 RLS · 19 events** |
| Acceptance · WBS · Test IDs | UX · Visual · Frontend · QA | Personal contribution record | Consent-gated analytics; no goal, memo, or email payloads |

- Limited each day to three quests and added 5–10 minute recovery, defer-without-penalty, and move-to-tomorrow options.
- Assigned goal decomposition and difficulty suggestions to AI; kept reward, state, and permission decisions server/rule based.
- Designed consent-gated analytics while excluding goal text, memos, and email from event properties.
- Kept planned scope, implemented code, test evidence, and user outcomes as separate claims.

[Planning source](https://www.notion.so/Questlog-IT-3bb807266361813d944ae247870f46d8?source=copy_link) · [Repository](https://github.com/jongshh/reminder) · [Portfolio case](https://it-planner-portfolio-gayeonbaek.sungwonhong.chatgpt.site/projects/project-02)

---

## How I work

```text
Problem → Success signal → Requirement → State & policy → Data/API → Acceptance → QA
```

- Define what “done” means before a screen enters implementation.
- Design the empty, loading, failed, forbidden, and recovery states—not only the happy path.
- Record the option considered, decision made, trade-off accepted, and evidence still missing.
- Never present an implementation count as a user outcome.

## Working context

**Product** — Requirements · IA · User flows · Feature policy · WBS · Acceptance criteria · QA  
**Technical** — React · JavaScript · REST API · Spring Boot · MySQL · Redis · Supabase · PostgreSQL · RLS

---

If your team needs a planner who can move from product intent to implementation detail, reach me at **[bgy030448@naver.com](mailto:bgy030448@naver.com)**.
