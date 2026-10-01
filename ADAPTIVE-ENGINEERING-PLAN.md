# Adaptive 8–10 Month Engineering Career, Skill, Portfolio & Public-Positioning System
## Final Execution Plan — Phase 2

**Params locked:** Systems = C → C++ (Rust read-only) | Flagship decision = C4→C5 review | Time = 5–8h/day | Start = Thu Oct 01, 2026 | End = Wed Jul 07, 2027 (40 weeks, Thu–Wed weeks)

**Legend:** `[M]` = manual, no agent | `[A]` = agent allowed | `E` = evidence gate | `MVW` 25h / `SW` 38–42h / `HOW` 50–54h

---

## MENU — QUICK NAVIGATION

- [0. How to use this file](#0-how-to-use-this-file)
- [1. Calendar index (C1–C10, W01–W40)](#1-calendar-index)
- [2. Time system + daily rhythms](#2-time-system--daily-rhythms)
- [3. Strategic spine + dependency graphs](#3-strategic-spine--dependency-graphs)
- [4. Stack locks + AI operating system](#4-stack-locks--ai-operating-system)
- [5. Learning method + mastery tests](#5-learning-method--mastery-tests)
- [6. Project ladder + flagship decision gate](#6-project-ladder--flagship-decision-gate)
- [7. Week-by-week day-by-day execution](#7-week-by-week-day-by-day-execution)
  - [C1 W01–W04 Foundation](#c1-foundation--w01-w04--oct-01--oct-28-2026)
  - [C2 W05–W08 TypeScript + Frontend](#c2-typescript--frontend--w05-w08--oct-29--nov-25-2026)
  - [C3 W09–W12 Backend + DB + Auth](#c3-backend--db--auth--w09-w12--nov-26--dec-23-2026)
  - [C4 W13–W16 Prod + C Systems + Three.js](#c4-prod--c-systems--threejs--w13-w16--dec-24-2026--jan-20-2027)
  - [C5 W17–W20 System thinking + flagship lock](#c5-system-thinking--flagship-lock--w17-w20--jan-21--feb-17-2027)
  - [C6 W21–W24 Agent leverage + WebGPU](#c6-agent-leverage--webgpu--w21-w24--feb-18--mar-17-2027)
  - [C7 W25–W28 Flagship MVP](#c7-flagship-mvp--w25-w28--mar-18--apr-14-2027)
  - [C8 W29–W32 Harden + OSS + proof](#c8-harden--oss--proof--w29-w32--apr-15--may-12-2027)
  - [C9 W33–W36 Distribution + interviews](#c9-distribution--interviews--w33-w36--may-13--jun-09-2027)
  - [C10 W37–W40 Pipeline + close](#c10-pipeline--close--w37-w40--jun-10--jul-07-2027)
- [8. Public presence (LinkedIn / X / Peerlist / GitHub)](#8-public-presence)
- [9. OSS strategy](#9-oss-strategy)
- [10. Career / application system](#10-career--application-system)
- [11. Metrics](#11-metrics)
- [12. Adaptation + failsafes + backup routes](#12-adaptation--failsafes--backup-routes)
- [13. Resources](#13-resources)
- [14. Review templates + deliverables](#14-review-templates--deliverables)

---

## 0. HOW TO USE THIS FILE

1. Weeks run **Thu–Wed** to match start date Thu Oct 01, 2026. `D1=Thu, D2=Fri, D3=Sat, D4=Sun, D5=Mon, D6=Tue, D7=Wed`.
2. Each week: Objective / Tech / Manual / Agent / Project / Public / Career / Evidence / Fail→Recovery + 7-day table. `Done =` column is your checkbox.
3. Build days (Thu/Fri/Mon/Tue): Deep-1 manual 2h + Deep-2 project 2h + Proof 30–45m. Sat: ship+deploy. Sun: light review. Wed: close + plan.
4. Rule: no day without commit after W02. No week without deploy touch after C1. If Evidence missed 2 weeks → failsafe, do not silently extend.
5. Strategy vs Execution vs Adaptation vs Recovery are separated (see §12). Stable core never changes mid-cycle; adaptive layer changes only on Wed of W04/W08/...

---

## 1. CALENDAR INDEX

| Cycle | Weeks | Dates | Phase | Hours | Gate |
|---|---|---|---|---|---|
| C1 | W01–W04 | Oct 01–Oct 28, 2026 | Foundation | SW | 2 manual deploys + event-loop whiteboard |
| C2 | W05–W08 | Oct 29–Nov 25, 2026 | TS + Frontend | SW | TS app + C taste + 30 postings analyzed |
| C3 | W09–W12 | Nov 26–Dec 23, 2026 | Backend + DB + Auth | SW | L2 fullstack live + Docker + CI |
| C4 | W13–W16 | Dec 24, 2026–Jan 20, 2027 | Prod + C + Three.js | MVW/SW holiday | k6 numbers + C echo + cube + flagship scored |
| C5 | W17–W20 | Jan 21–Feb 17, 2027 | System thinking + flagship lock | SW | L4 spike + SPEC v1 locked |
| C6 | W21–W24 | Feb 18–Mar 17, 2027 | Agent leverage + WebGPU | SW/HOW | MVP 0.5 + compute numbers |
| C7 | W25–W28 | Mar 18–Apr 14, 2027 | Flagship MVP | SW/HOW | v0.9 + postmortem + demo video |
| C8 | W29–W32 | Apr 15–May 12, 2027 | Harden + OSS | SW | v1.0-rc + merged OSS + mocks |
| C9 | W33–W36 | May 13–Jun 09, 2027 | Distribution | SW/HOW | 80 apps + bottleneck fixed |
| C10 | W37–W40 | Jun 10–Jul 07, 2027 | Pipeline + close | SW | 300+ touches + final retro |

W01 D1 = Thu Oct 01, 2026. W40 D7 = Wed Jul 07, 2027. Buffer to Aug 07 allowed only by cutting scope, never by adding.

---

## 2. TIME SYSTEM + DAILY RHYTHMS

**MVW (25h, 5h×5d):** 1 learning block + repo touch + 15-min log/day. No new tech.
**SW (38–42h, ~6.5h×6d):** normal. ~4.5h real deep work from 6.5h clock by design.
**HOW (50–54h, 8h×6–7d):** max 2 in a row, then 1 SW. Adds benchmark + outreach.

| Cycle | Learn | Manual | Projects | Systems C/C++ | Graphics | Public | Network/Apps | Review |
|---|---|---|---|---|---|---|---|---|
| C1 | 35 | 30 | 15 | 3 | 2 | 5 | 5 | 5 |
| C2–C3 | 25 | 25 | 25 | 8 | 4 | 5 | 3 | 5 |
| C4–C5 | 20 | 15 | 30 | 12 | 8 | 7 | 5 | 3 |
| C6–C7 | 15 | 10 | 32 | 6 | 14 | 10 | 10 | 3 |
| C8–C10 | 10 | 8 | 30 | 4 | 8 | 12 | 25 | 3 |

Systems cap: never >8h/week SW. If bleed → cut systems task.

**Daily template — Build (Thu/Fri/Mon/Tue, 6.5h):** 09:30–11:30 Deep-1 manual (phone off) + 15:00–17:00 Deep-2 project + 17:00–17:45 Proof (commit, README, GIF, post draft).
**Ship (Sat, 6h):** harden 3h + deploy + demo + post publish.
**Light (Sun, 3h):** metrics 1h + plan 1h + README 1h + rest.
**Close (Wed, 5h + review if W04):** finish + push + log + plan next week.
Daily log in `log.md`: `Date | Deep hrs | Commit | Test? | Blocked? | Tomorrow 1 thing`

---

## 3. STRATEGIC SPINE + DEPENDENCY GRAPHS

**Pillars (fixed):** 1 Web employability | 2 Systems depth | 3 Graphics/WebGPU differentiation | 4 AI leverage A→D | 5 Real construction L1→L5 | 6 Public proof | 7 Career distribution.
**Engine:** Web 60–70% early → 45–55% late. Depth Systems 15%→10%. Differentiation Graphics 10%→15%. Multiplier AI embedded. Distribution 5%→25%.

**Branch A — Web (primary):** Linux+Git → HTML/CSS → JS (closures, event loop, fetch) → Browser (DOM, CORS, DevTools) → HTTP+REST → TS strict → React (components, Router, Query) → Node+Express (middleware, Zod) → Postgres (schema, joins, indexes, tx) + Redis → Auth (bcrypt, sessions, OAuth, OWASP) → Test (Vitest/Supertest/Playwright) → Docker+Actions+Vercel/Railway/Fly → Prod (Pino, /metrics, k6, rate-limit) → System design lite.

**Branch B — Systems C/C++ (time-boxed, supports A):** GCC/Make/GDB → C pointers/arrays/structs/malloc → processes/FDs/sockets (Beej) + Valgrind → C++ RAII/refs/classes → threads/mutex/TSan (pool + race fix) → strace//proc/signals → hand HTTP server once → benchmark C++ vs Node (k6). Rust read-only ≤2h (C9 interview note only).

**Branch C — Graphics:** JS + vectors/matrices → Canvas → Three.js scene → WebGL triangle once (buffers, GLSL) → TSL nodes (GLSL→TSL convert) → WebGPU (`three/webgpu`, fallback) + compute + timestamps → particles/post-processing.

---

## 4. STACK LOCKS + AI OPERATING SYSTEM

**Locks:** TS strict (JS only C1) | React+Vite+Tailwind+Router+Query | Node+Express → Fastify/Nest pattern only if review says | Postgres+Prisma/Drizzle+Redis | Session+bcrypt+GitHub OAuth | Vitest+Supertest+Playwright | Docker+Actions+Vercel+Railway/Fly | Pino+k6 | GCC/Clang+Make+GDB+Valgrind | Three r17x+ `three/webgpu` | 1 CLI agent (Claude Code OR Codex, pick W05, stick 1 cycle) + Copilot inline.

**AI stages:** C1 Stage A (no agent impl, tutor only) | C2–C3 A→B (manual types/routes/schema/auth; agent boilerplate/CSS/tests after yours) + weekly `agent-review.md` with 1 rejection | C4–C5 B (SPEC, agent scaffolds, you verify; require files-changed + run + test plan) | C6+ C→D (SPEC.md + AGENTS.md + eval checklist: builds? tests? perf? auth? demo? + `agent-failures.md`).
**Bans:** no secrets in prompts, no `.env` committed, no agent→main without CI + diff read, if you cannot whiteboard it you cannot claim it.

`SPEC.md` template: goal / non-goals / constraints / acceptance criteria / perf budget. `AGENTS.md` template: stack / commands (`npm run dev/test/build`) / conventions / forbidden.

---

## 5. LEARNING METHOD + MASTERY TESTS

Per skill: 1 Why (transfer/pay) | 2 Prereqs | 3 Must-understand | 4 Manual [M] | 5 Delegable [A] | 6 Project | 7 Mastery test | 8 Evidence (live + README + numbers).
Example DB index: Why N+1 kills apps → Prereq joins → Understand B-tree/EXPLAIN → Manual create+EXPLAIN ANALYZE 50k rows → Delegate migrations → Project prod-notes → Test fix <100ms → Evidence screenshot+writeup.

**Gates (must pass to advance):** JS rebuild todo <2h + event-loop whiteboard | TS `tsc` clean + narrowing/generics | React add search <3h + data-flow | Node curl CRUD + middleware + break/fix validation | DB EXPLAIN before/after + N+1 fix | Auth session-vs-JWT + OWASP checklist | Docker stranger `compose up` <5m | C vector/list Valgrind clean + heap/stack + sockets | C++ RAII + pool TSan clean + race fix | Three cube + WebGL triangle + pipeline | TSL convert + both renderers + fps | Agent SPEC→deploy + rejection log | Flagship 10-min arch no notes + k6 + postmortem.

---

## 6. PROJECT LADDER + FLAGSHIP DECISION GATE

L1 C1 `static-portfolio` + `js-primitives` (GH Pages+Vercel) | L2 C2–C3 `fullstack-notes` (React+TS+Node+Postgres+auth+tests+Docker) | L3 C4 `prod-notes` (Redis, rate-limit, Pino, /metrics, k6 + fix) + `c-labs` + `three-playground` | L4 C5–C6 ONE spike: RT presence (WS) OR 100k-particle WebGPU + profile OR C++ file-server/KV vs Node | L5 C7–C8 ONE flagship.
Flagship options: **A Playground+Backend** (save/share scenes, leaderboard) | **B Realtime Viz+Ingest** (WS + Three + ingest benchmark) | **C Agent-Eval Harness** (bench AI code correctness/speed). Score 1–5 in W16 on employability/differentiation/feasibility/perf/demo. SPEC v0 W17, lock W20, thin-slice MVP <3 weeks. Must-have: live URL, README (problem, <5m quickstart, arch diagram, decisions, perf, what broke), tests+CI, observability, docs, 2 writeups, postmortem, GIF/video. No new projects after C7 without killing one.

---

## 7. WEEK-BY-WEEK DAY-BY-DAY EXECUTION

> Weeks Thu–Wed. Hours = clock. Adjust MVW/SW within % caps.

### C1 FOUNDATION — W01–W04 — OCT 01 – OCT 28, 2026

#### W01 — Linux/Git/HTML/CSS — Oct 01–07 — SW 38h — E: live static URL
Obj: terminal + deploy static. Tech: CLI, Git branch/PR, semantic HTML, Flex/Grid. [M]: portfolio v0 blank, no template. [A]: explain git errors only. Proj: `static-portfolio`→GH Pages. Public: X 2 logs + Peerlist create. Career: LinkedIn cleanup + 20 follows. Fail no deploy → 1-page cut, deploy Mon.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof/Shallow | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Oct 01 | 6.5 | Linux CLI files/perms/ssh [M] | Git init/branch/merge [M] | log.md + repo init | |
| D2 Fri | Oct 02 | 6.5 | Semantic HTML 1 page [M] | Flex/Grid responsive [M] | commit + push | |
| D3 Sat | Oct 03 | 6 | Polish 1 page [M] | Deploy GH Pages + README | X log #1 | |
| D4 Sun | Oct 04 | 3 | Review + fix links | Plan W01 close | rest | |
| D5 Mon | Oct 05 | 6.5 | CSS layout drill [M] | v0 second section [M] | X log #2 | |
| D6 Tue | Oct 06 | 6.5 | A11y basics + Lighthouse run | Fix issues [M] | Peerlist create+pin | |
| D7 Wed | Oct 07 | 5 | Freeze v0, tag | LinkedIn cleanup | plan W02 | |

#### W02 — JS Core — Oct 08–14 — SW 40h — E: rebuild todo <2h
Obj: closures/prototypes/event-loop. Tech: JS core+modules+JSON. [M]: todo-localStorage + fetch-list + emitter, no agent. [A]: quiz/review only. Public: X benchmark for-vs-map measured + LinkedIn 3 models. Career: 2 Discords, 1Q+1A.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Oct 08 | 6.5 | Closures/hoisting/this [M] | todo add/delete [M] | commit | |
| D2 Fri | Oct 09 | 6.5 | Array methods/modules [M] | todo persist+edit [M] | X benchmark draft | |
| D3 Sat | Oct 10 | 6 | fetch-list API render [M] | emitter [M] + deploy Vercel | X post | |
| D4 Sun | Oct 11 | 3 | Review blind-rebuild drill | rest | | |
| D5 Mon | Oct 12 | 6.5 | Edge cases+bugs [M] | chunked commits | LinkedIn draft | |
| D6 Tue | Oct 13 | 6.5 | Rebuild todo timed [M] | fix gaps | publish LinkedIn | |
| D7 Wed | Oct 14 | 5 | Freeze `js-primitives` | Peerlist pin | plan W03 | |

#### W03 — Browser + HTTP — Oct 15–21 — SW 40h — E: whiteboard lifecycle + CORS fix
Obj: request lifecycle. Tech: DOM/events/CORS/DevTools/HTTP/cache/DNS/TLS. [M]: gallery+validation, break+fix CORS, throttle debug. [A]: CSS boilerplate only. Proj: site v1 Vercel preview. Public: LinkedIn waterfall before/after. Career: Peerlist 2 READMEs.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Oct 15 | 6.5 | DOM/events/bubbling [M] | gallery [M] | commit | |
| D2 Fri | Oct 16 | 6.5 | HTTP methods/headers/cookies [M] | fetch + Network panel | X log | |
| D3 Sat | Oct 17 | 6 | CORS break+fix [M] | throttle + cache demo | GIF waterfall | |
| D4 Sun | Oct 18 | 3 | Review + diagram draw | rest | | |
| D5 Mon | Oct 19 | 6.5 | Storage/forms validation [M] | site v1 assemble | README | |
| D6 Tue | Oct 20 | 6.5 | Perf pass [M] | deploy preview | LinkedIn post | |
| D7 Wed | Oct 21 | 5 | Whiteboard drill | Peerlist update | plan W04 | |

#### W04 — Harden + Review C1 — Oct 22–28 — SW 35h — E: stranger clone-run <5m
Obj: consolidate. Tech: a11y/Lighthouse + `curl/strace//proc` + GCC hello. [M]: Lighthouse >90 + postmortem. [A]: agent refactors 1 file, reject ≥1 logged. Proj: freeze C1 (2–3 repos). Public: LinkedIn deep + X summary. Career: 0 apps, 5 profile analyses.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Oct 22 | 6.5 | A11y+Lighthouse >90 [M] | postmortem 1 bug | commit | |
| D2 Fri | Oct 23 | 6.5 | GCC hello + curl/strace taste [M] | agent refactor review [A] | rejection log | |
| D3 Sat | Oct 24 | 6 | Freeze READMEs + demos | LinkedIn deep publish | X summary | |
| D4 Sun | Oct 25 | 3 | Profile README | rest | | |
| D5 Mon | Oct 26 | 6.5 | Clone-run test (friend or fresh dir) | fix gaps | Peerlist polish | |
| D6 Tue | Oct 27 | 6.5 | C1 review template fill | lock C2 versions | | |
| D7 Wed | Oct 28 | 5 | Retro post + plan C2 | | | |

### C2 TYPESCRIPT + FRONTEND — W05–W08 — OCT 29 – NOV 25, 2026

#### W05 — TypeScript — Oct 29–Nov 04 — SW 40h — E: `tsc` clean + unknown-vs-any blind
Tech: types/narrowing/generics/fetch wrappers. [M]: port fetch-list TS strict. [A]: pick CLI (Claude/Codex), error-explain only. Proj: `ts-lab` + `fullstack-notes` init + AGENTS.md. Public: X narrowing lesson. Career: analyze 30 postings.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Oct 29 | 6.5 | TS setup strict [M] | port fetch-list [M] | commit | |
| D2 Fri | Oct 30 | 6.5 | Narrowing/generics [M] | API wrapper types [M] | X draft | |
| D3 Sat | Oct 31 | 6 | Fix `any`→`unknown` [M] | repo + AGENTS.md | X post | |
| D4 Sun | Nov 01 | 3 | Review + postings 10/30 | rest | | |
| D5 Mon | Nov 02 | 6.5 | Postings 30/30 table | notes repo scaffold | README | |
| D6 Tue | Nov 03 | 6.5 | Agent pick + test | TS drill blind | LinkedIn TS-vs-JS note | |
| D7 Wed | Nov 04 | 5 | Freeze ts-lab | plan W06 | | |

#### W06 — React Core — Nov 05–11 — SW 40h — E: add search <3h no tutorial + CI build
Tech: React/Router/Query/Tailwind. [M]: notes UI hand-built. [A]: Tailwind variants after base. Proj: FE + mock API. Public: X GIF. Career: 5 connects.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Nov 05 | 6.5 | Components/state [M] | notes list [M] | commit | |
| D2 Fri | Nov 06 | 6.5 | Router+Query [M] | mock wiring [M] | X GIF draft | |
| D3 Sat | Nov 07 | 6 | Loading/error states [M] | deploy preview | X post | |
| D4 Sun | Nov 08 | 3 | Review + connects | rest | | |
| D5 Mon | Nov 09 | 6.5 | Tailwind polish [M/A] | search feature [M] | commit | |
| D6 Tue | Nov 10 | 6.5 | Actions lint+build | fix CI | README | |
| D7 Wed | Nov 11 | 5 | Freeze FE-mock | plan W07 | | |

#### W07 — Frontend Testing — Nov 12–18 — SW 40h — E: CI green
Tech: Vitest/Playwright/a11y. [M]: 5 unit +1 e2e manually. [A]: scaffold extras. Public: X test GIF. Career: Peerlist.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Nov 12 | 6.5 | Vitest 5 tests [M] | fix | commit | |
| D2 Fri | Nov 13 | 6.5 | Playwright smoke [M] | CI | X draft | |
| D3 Sat | Nov 14 | 6 | A11y pass | deploy | X post | |
| D4 Sun | Nov 15 | 3 | Review | rest | | |
| D5 Mon | Nov 16 | 6.5 | Agent tests review [A] | harden | README tests section | |
| D6 Tue | Nov 17 | 6.5 | Blind add-filter drill | Peerlist | | |
| D7 Wed | Nov 18 | 5 | Freeze | plan W08 | | |

#### W08 — C Taste + Review C2 — Nov 19–25 — SW 38h — E: malloc/stack-heap blind
Tech: C pointers/arrays/structs/GCC/Make/GDB. [M]: vector+list+file-copy Valgrind clean. [A]: compiler-explain only. Proj: `c-labs` init. Public: LinkedIn C→JS arrays. Career: 3 calibration apps.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Nov 19 | 6.5 | Pointers/arrays [M] | vector [M] | commit | |
| D2 Fri | Nov 20 | 6.5 | Structs/list [M] | file copy [M] | Valgrind log | |
| D3 Sat | Nov 21 | 6 | GDB+Make [M] | `c-labs` README | LinkedIn post | |
| D4 Sun | Nov 22 | 3 | Review C2 template | rest | | |
| D5 Mon | Nov 23 | 6.5 | 3 apps + whiteboard drill | fix gaps | X log | |
| D6 Tue | Nov 24 | 6.5 | Lock C3 versions | | | |
| D7 Wed | Nov 25 | 5 | Retro + plan C3 | | | |

### C3 BACKEND + DB + AUTH — W09–W12 — NOV 26 – DEC 23, 2026

#### W09 — Node API — Nov 26–Dec 02 — SW 40h — E: curl CRUD + middleware blind
Tech: Express/middleware/Zod/errors. [M]: CRUD+validation hand-written. [A]: boilerplate after yours. Public: X API demo. Career: 5 apps.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Nov 26 | 6.5 | Routes [M] | middleware [M] | commit | |
| D2 Fri | Nov 27 | 6.5 | Zod validation [M] | errors [M] | curl log | |
| D3 Sat | Nov 28 | 6 | FE–BE wire | deploy BE preview | X post | |
| D4 Sun | Nov 29 | 3 | Review | rest | | |
| D5 Mon | Nov 30 | 6.5 | Break/fix validation [M] | tests 3 [M] | README API table | |
| D6 Tue | Dec 01 | 6.5 | 5 apps | polish | | |
| D7 Wed | Dec 02 | 5 | Freeze API | plan W10 | | |

#### W10 — Postgres + Redis — Dec 03–09 — SW 40h — E: EXPLAIN before/after + p95 doc
Tech: schema/joins/indexes/tx/EXPLAIN/Redis one endpoint. [M]: schema+joins+index+measure 50k seeds. [A]: migration boilerplate. Public: LinkedIn index numbers. Career: 5 apps. OSS: docs PR #1.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Dec 03 | 6.5 | Schema [M] | seed [M] | commit | |
| D2 Fri | Dec 04 | 6.5 | Joins+EXPLAIN [M] | index+measure [M] | numbers draft | |
| D3 Sat | Dec 05 | 6 | Redis cache [M/A] | LinkedIn post | X numbers | |
| D4 Sun | Dec 06 | 3 | OSS docs PR scout | rest | | |
| D5 Mon | Dec 07 | 6.5 | OSS PR open | 5 apps | | |
| D6 Tue | Dec 08 | 6.5 | Tx + tests [M] | README perf section | | |
| D7 Wed | Dec 09 | 5 | Freeze DB | plan W11 | | |

#### W11 — Auth + Security — Dec 10–16 — SW 40h — E: session-vs-JWT blind + checklist
Tech: bcrypt/sessions/OAuth/OWASP/rate-limit. [M]: session+hash once. [A]: OAuth scaffold audit. Proj: auth live, `.env.example`. Public: X pitfall. Career: 7 apps.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Dec 10 | 6.5 | bcrypt+sessions [M] | protected routes [M] | commit | |
| D2 Fri | Dec 11 | 6.5 | OAuth GitHub [A audit] | rate-limit | checklist | |
| D3 Sat | Dec 12 | 6 | OWASP pass | deploy | X post | |
| D4 Sun | Dec 13 | 3 | Review | rest | | |
| D5 Mon | Dec 14 | 6.5 | 7 apps | tests auth [M] | | |
| D6 Tue | Dec 15 | 6.5 | Whiteboard drill | README auth | | |
| D7 Wed | Dec 16 | 5 | Freeze auth | plan W12 | | |

#### W12 — Docker/CI/Deploy + Review C3 — Dec 17–23 — SW 40h — E: L2 DONE stranger-run <5m
Tech: Dockerfile/compose/Actions/Vercel+Railway. [M]: Dockerfile+compose once. [A]: CI logs. Proj: L2 live FE+BE+DB README <5m. Public: LinkedIn launch+video. Career: 7 apps. OSS: PR #2.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Dec 17 | 6.5 | Dockerfile [M] | compose [M] | commit | |
| D2 Fri | Dec 18 | 6.5 | Actions [A] | fix CI | badge | |
| D3 Sat | Dec 19 | 6 | Deploy prod + video | LinkedIn launch | X demo | |
| D4 Sun | Dec 20 | 3 | OSS PR #2 | rest | | |
| D5 Mon | Dec 21 | 6.5 | 7 apps + clone-run test | fix | Peerlist | |
| D6 Tue | Dec 22 | 6.5 | C3 review | decide C4 explore | | |
| D7 Wed | Dec 23 | 5 | Retro + plan C4 | | | |

### C4 PROD + C SYSTEMS + THREE.JS — W13–W16 — DEC 24, 2026 – JAN 20, 2027

#### W13 — Observability + Perf — Dec 24–31 — MVW 25h (holiday) — E: k6 50 VUs + p95
Tech: Pino//metrics/k6/cache. [M]: logs/metrics+k6+fix N+1. [A]: analyze output. Public: LinkedIn load numbers. Career: 5 apps.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Dec 24 | 5 | Pino [M] | /metrics | commit | |
| D2 Fri | Dec 25 | 0–3 | Off / light log | | | |
| D3 Sat | Dec 26 | 5 | k6 50 VUs [M] | fix one bottleneck | numbers | |
| D4 Sun | Dec 27 | 3 | Review | rest | | |
| D5 Mon | Dec 28 | 6.5 | Cache verify | README perf | LinkedIn draft | |
| D6 Tue | Dec 29 | 5 | 5 apps + publish | | | |
| D7 Wed | Dec 30–31 | 5 | Freeze buffer New Year | plan W14 | | |

#### W14 — C Deep — Jan 01–07 — SW 38h — E: echo + socket lifecycle blind
Tech: malloc/FDs/TCP (Beej)/strace/Valgrind. [M]: TCP echo + strace + clean. [A]: syscall-explain. Public: X strace find. Career: 5 apps + 3 connects. Cap 8h systems.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Jan 01 | 5 | FDs/malloc review [M] | echo start | commit | |
| D2 Fri | Jan 02 | 6.5 | TCP echo [M] | Valgrind | log | |
| D3 Sat | Jan 03 | 6 | strace log | X post | README | |
| D4 Sun | Jan 04 | 3 | Review | rest | | |
| D5 Mon | Jan 05 | 6.5 | Whiteboard drill | 5 apps | | |
| D6 Tue | Jan 06 | 6.5 | Polish + 3 connects | | | |
| D7 Wed | Jan 07 | 5 | Freeze | plan W15 | | |

#### W15 — C++ + Three.js — Jan 08–14 — SW 40h — E: RAII blind + cube live
Tech: C++ refs/classes/RAII + Three scene/loop. [M]: C vector→C++ class + cube tweak. [A]: Three boilerplate. Public: X GIF + LinkedIn C-vs-JS. Career: 7 apps.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Jan 08 | 6.5 | RAII/class [M] | port [M] | commit | |
| D2 Fri | Jan 09 | 6.5 | Three scene [M] | lights/loop | GIF draft | |
| D3 Sat | Jan 10 | 6 | Interactive controls | deploy playground | X post | |
| D4 Sun | Jan 11 | 3 | Review | rest | | |
| D5 Mon | Jan 12 | 6.5 | 7 apps | polish | LinkedIn post | |
| D6 Tue | Jan 13 | 6.5 | Drill RAII vs malloc | README | | |
| D7 Wed | Jan 14 | 5 | Freeze | plan W16 | | |

#### W16 — WebGL Once + Review C4 — Jan 15? (actual Jan 14–20 window, Thu Jan 15–Wed Jan 20 + overlap) — SW 40h — E: triangle + flagship scoresheet
Tech: buffers/GLSL triangle/draw calls. [M]: hand triangle once. [A]: shader-error explain. Public: LinkedIn WebGL-vs-Three. Career: 10 apps. Review C4 + score A/B/C.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Jan 15 | 6.5 | WebGL triangle [M] | screenshot | commit | |
| D2 Fri | Jan 16 | 6.5 | Draw-call notes | playground update | LinkedIn post | |
| D3 Sat | Jan 17 | 6 | 10 apps | demo | X log | |
| D4 Sun | Jan 18 | 3 | Scoresheet A/B/C draft | rest | | |
| D5 Mon | Jan 19 | 6.5 | C4 review template | fix gaps | | |
| D6 Tue | Jan 20 | 6.5 | Finalize scores + SPEC v0 idea | | | |
| D7 Wed | Jan 20 | 2 | Retro + plan C5 (absorb overlap) | | | |

### C5 SYSTEM THINKING + FLAGSHIP LOCK — W17–W20 — JAN 21 – FEB 17, 2027

#### W17 — Concurrency — Jan 21–27 — SW 40h — E: TSan clean + race blind + SPEC v0
Tech: thread/mutex/TSan pool. [M]: pool + race fix. Proj: C++ vs Node k6 numbers. Public: LinkedIn benchmark. Career: 10 apps.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Jan 21 | 6.5 | threads/mutex [M] | pool start | commit | |
| D2 Fri | Jan 22 | 6.5 | Race fix TSan [M] | k6 compare | numbers | |
| D3 Sat | Jan 23 | 6 | README bench | LinkedIn post | X thread | |
| D4 Sun | Jan 24 | 3 | SPEC v0 1-page | rest | | |
| D5 Mon | Jan 25 | 6.5 | 10 apps | polish | | |
| D6 Tue | Jan 26 | 6.5 | Drill | | | |
| D7 Wed | Jan 27 | 5 | Freeze + plan W18 | | | |

#### W18 — Networking Applied — Jan 28–Feb 03 — SW 40h — E: C HTTP serves page
Tech: hand HTTP GET once/TLS/DNS. [M]: minimal HTTP server. Public: X numbers. Career: 10 apps + 2 outreaches.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Jan 28 | 6.5 | HTTP parse [M] | server start | commit | |
| D2 Fri | Jan 29 | 6.5 | Serve file [M] | compare Express | numbers | |
| D3 Sat | Jan 30 | 6 | Postmortem | X post | | |
| D4 Sun | Jan 31 | 3 | Outreach list 20 | rest | | |
| D5 Mon | Feb 01 | 6.5 | 10 apps + 2 outreaches | | | |
| D6 Tue | Feb 02 | 6.5 | Polish | | | |
| D7 Wed | Feb 03 | 5 | Freeze + plan | | | |

#### W19 — TSL + WebGPU Taste — Feb 04–10 — SW 40h — E: GLSL→TSL + both renderers
Tech: TSL/`three/webgpu`/RenderPipeline. [M]: convert once. Public: GIF. Career: 10 apps.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Feb 04 | 6.5 | TSL nodes [M] | convert [M] | commit | |
| D2 Fri | Feb 05 | 6.5 | webgpu branch | fallback test | GIF | |
| D3 Sat | Feb 06 | 6 | Deploy branch | X post | | |
| D4 Sun | Feb 07 | 3 | Review | rest | | |
| D5 Mon | Feb 08 | 6.5 | 10 apps | docs | | |
| D6 Tue | Feb 09 | 6.5 | Drill TSL-why | | | |
| D7 Wed | Feb 10 | 5 | Freeze + plan W20 | | | |

#### W20 — L4 Spike + LOCK — Feb 11–17 — SW 42h — E: L4 live + SPEC v1 locked
Tech: ONE L4 15h box. [M]: core loop. Public: LinkedIn numbers. Career: 12 apps. Review C5, LOCK A/B/C + MVP <3w.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Feb 11 | 6.5 | L4 core [M] | | commit | |
| D2 Fri | Feb 12 | 6.5 | L4 bench | | numbers | |
| D3 Sat | Feb 13 | 6 | Deploy L4 + writeup | LinkedIn post | | |
| D4 Sun | Feb 14 | 3 | C5 review + lock decision | rest | | |
| D5 Mon | Feb 15 | 6.5 | 12 apps | SPEC v1 | | |
| D6 Tue | Feb 16 | 6.5 | MVP slice <3w plan | | | |
| D7 Wed | Feb 17 | 5 | Retro + plan C6 | | | |

### C6 AGENT LEVERAGE + WEBGPU — W21–W24 — FEB 18 – MAR 17, 2027

#### W21 — Spec Builds — Feb 18–24 — SW 42h — E: slice deployed + failures log
[M]: SPEC yourself. [A]: parallel UI/API/tests, you integrate. Public: agent-failure post. Career: 12+3.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Feb 18 | 6.5 | SPEC slice-1 | parallel kick [A] | commit | |
| D2 Fri | Feb 19 | 6.5 | Integrate [M review] | tests | failures log | |
| D3 Sat | Feb 20 | 6 | Deploy slice-1 | LinkedIn failure post | | |
| D4 Sun | Feb 21 | 3 | Review eval checklist | rest | | |
| D5 Mon | Feb 22 | 6.5 | 12 apps + 3 outreaches | fix | | |
| D6 Tue | Feb 23 | 6.5 | Reject ≥1 arch w/ reason | | | |
| D7 Wed | Feb 24 | 5 | Freeze + plan | | | |

#### W22 — Compute — Feb 25–Mar 03 — SW/HOW 45h — E: 100k particles + frame times
[M]: sim core + profile. Public: viral GIF + profiling lesson. Career: 10 apps.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Feb 25 | 7 | Compute setup [M] | particles | commit | |
| D2 Fri | Feb 26 | 7 | Timestamps profile [M] | optimize | numbers | |
| D3 Sat | Feb 27 | 6 | Deploy + GIF | LinkedIn+X | | |
| D4 Sun | Feb 28 | 3 | Review | rest | | |
| D5 Mon | Mar 01 | 7 | 10 apps | polish | | |
| D6 Tue | Mar 02 | 7 | Drill | README fps | | |
| D7 Wed | Mar 03 | 5 | Freeze | | | |

#### W23 — Backend Perf — Mar 04–10 — SW 42h — E: p95 improved + test + OSS PR
[M]: fix one flagship bottleneck measured. Public: before/after. Career: 12 apps. OSS test/bugfix 30–50 lines.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Mar 04 | 6.5 | Profile flagship [M] | fix | commit | |
| D2 Fri | Mar 05 | 6.5 | OSS reproduce+test [M] | PR draft | | |
| D3 Sat | Mar 06 | 6 | OSS PR open + perf post | | | |
| D4 Sun | Mar 07 | 3 | Review | rest | | |
| D5 Mon | Mar 08 | 6.5 | 12 apps | verify | | |
| D6 Tue | Mar 09 | 6.5 | Polish slice-2 | | | |
| D7 Wed | Mar 10 | 5 | Freeze | | | |

#### W24 — Polish + Review C6 — Mar 11–17 — SW 40h — E: MVP 0.5 + diagram
[M]: arch diagram yourself. [A]: docs draft rewrite. Public: demo video. Career: 15 apps.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Mar 11 | 6.5 | Errors/empty states [M] | diagram [M] | commit | |
| D2 Fri | Mar 12 | 6.5 | Docs rewrite | video | | |
| D3 Sat | Mar 13 | 6 | Deploy 0.5 + video | | | |
| D4 Sun | Mar 14 | 3 | C6 review | rest | | |
| D5 Mon | Mar 15 | 6.5 | 15 apps | fix | | |
| D6 Tue | Mar 16 | 6.5 | Stranger-use test | | | |
| D7 Wed | Mar 17 | 5 | Retro + plan C7 | | | |

### C7 FLAGSHIP MVP — W25–W28 — MAR 18 – APR 14, 2027

#### W25 — Feature Complete — Mar 18–24 — HOW 50h — E: acceptance all green, freeze
No scope creep; cut to freeze.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Mar 18 | 8 | Critical path review | build | commit | |
| D2 Fri | Mar 19 | 8 | Finish slice | tests | | |
| D3 Sat | Mar 20 | 7 | Deploy freeze + launch post | | | |
| D4 Sun | Mar 21 | 3 | Review | rest | | |
| D5 Mon | Mar 22 | 8 | 15 apps + 5 founder outreaches | | | |
| D6 Tue | Mar 23 | 8 | Fix blockers only | | | |
| D7 Wed | Mar 24 | 5 | Freeze | | | |

#### W26 — Tests + Security — Mar 25–31 — SW 42h — E: CI green + OWASP checklist
[M]: 3 critical tests yourself. OSS 2nd PR.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Mar 25 | 6.5 | Critical tests [M] | CI | commit | |
| D2 Fri | Mar 26 | 6.5 | OWASP+rate-limit | checklist README | | |
| D3 Sat | Mar 27 | 6 | OSS PR + X CI post | | | |
| D4 Sun | Mar 28 | 3 | Review | rest | | |
| D5 Mon | Mar 29 | 6.5 | 15 apps | | | |
| D6 Tue | Mar 30 | 6.5 | Polish | | | |
| D7 Wed | Mar 31 | 5 | Freeze | | | |

#### W27 — Observability + Postmortem — Apr 01–07 — SW 42h — E: k6 100 VUs + postmortem
[M]: run k6 + fix one bottleneck. Public: postmortem (top hiring signal). Career: 15 apps + mock #1.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Apr 01 | 6.5 | Logs/metrics/traces | k6 100 [M] | commit | |
| D2 Fri | Apr 02 | 6.5 | Fix bottleneck | numbers | postmortem draft | |
| D3 Sat | Apr 03 | 6 | Publish postmortem | | | |
| D4 Sun | Apr 04 | 3 | Mock #1 | rest | | |
| D5 Mon | Apr 05 | 6.5 | 15 apps | fix from mock | | |
| D6 Tue | Apr 06 | 6.5 | Polish | | | |
| D7 Wed | Apr 07 | 5 | Freeze | | | |

#### W28 — Docs + Demo + Review C7 — Apr 08–14 — SW 40h — E: v0.9 passes 60-sec recruiter test
[M]: README+diagram yourself. Public: X+LinkedIn+Peerlist launch. Career: 18 apps.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Apr 08 | 6.5 | README [M] | diagram | commit | |
| D2 Fri | Apr 09 | 6.5 | GIF/video | Peerlist pin | launch | |
| D3 Sat | Apr 10 | 6 | Launch day posts | | | |
| D4 Sun | Apr 11 | 3 | C7 review | rest | | |
| D5 Mon | Apr 12 | 6.5 | 18 apps | | | |
| D6 Tue | Apr 13 | 6.5 | Fix launch bugs | | | |
| D7 Wed | Apr 14 | 5 | Retro + plan C8 | | | |

### C8 HARDEN + OSS + PROOF — W29–W32 — APR 15 – MAY 12, 2027

#### W29 — Hardening — Apr 15–21 — SW 42h — E: 0 critical + Lighthouse >90
Fix 5 bugs manually. Public: bug thread. Career: 18+5.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Apr 15 | 6.5 | Bug bash 5 [M] | | commit | |
| D2 Fri | Apr 16 | 6.5 | Perf budget + a11y | | | |
| D3 Sat | Apr 17 | 6 | v1.0-rc + X thread | | | |
| D4 Sun | Apr 18 | 3 | Review | rest | | |
| D5 Mon | Apr 19 | 6.5 | 18 apps + 5 outreaches | | | |
| D6 Tue | Apr 20 | 6.5 | Polish | | | |
| D7 Wed | Apr 21 | 5 | Freeze | | | |

#### W30 — OSS Push — Apr 22–28 — SW 40h — E: PR merged or revision addressed
Target 1 mid-size used repo. [M]: reproduce+test.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Apr 22 | 6.5 | Reproduce [M] | test | commit | |
| D2 Fri | Apr 23 | 6.5 | Fix draft [A verify] | PR open | | |
| D3 Sat | Apr 24 | 6 | LinkedIn OSS lesson | 18 apps | | |
| D4 Sun | Apr 25 | 3 | Review | rest | | |
| D5 Mon | Apr 26 | 6.5 | Address review | | | |
| D6 Tue | Apr 27 | 6.5 | Polish | | | |
| D7 Wed | Apr 28 | 5 | Freeze | | | |

#### W31 — Second Proof — Apr 29–May 05 — SW 42h — E: 2nd demo + numbers
Finish other L4 if gap. Public: benchmark thread. Career: 18 + referrals after help.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Apr 29 | 6.5 | 2nd spike core [M] | | commit | |
| D2 Fri | Apr 30 | 6.5 | Bench + writeup | | | |
| D3 Sat | May 01 | 6 | Deploy + thread | | | |
| D4 Sun | May 02 | 3 | Help in Discord (referral seed) | rest | | |
| D5 Mon | May 03 | 6.5 | 18 apps | | | |
| D6 Tue | May 04 | 6.5 | Polish | | | |
| D7 Wed | May 05 | 5 | Freeze | | | |

#### W32 — Interview Prep + Review C8 — May 06–12 — SW 40h — E: 10-min arch no notes
DSA pragmatic (hash/map/array/string) 3/w by hand + system-design junior (URL shortener) + STAR 5 stories.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | May 06 | 6.5 | DSA 3 [M] + mock [A] | STAR 2 | commit | |
| D2 Fri | May 07 | 6.5 | System design drill | STAR 3 | | |
| D3 Sat | May 08 | 6 | Freeze builds + deep post | | | |
| D4 Sun | May 09 | 3 | C8 review | rest | | |
| D5 Mon | May 10 | 6.5 | 20 apps + 2 mocks | | | |
| D6 Tue | May 11 | 6.5 | Fix gaps | | | |
| D7 Wed | May 12 | 5 | Retro + plan C9 | | | |

### C9 DISTRIBUTION + INTERVIEWS — W33–W36 — MAY 13 – JUN 09, 2027

#### W33 — Aggressive — May 13–19 — HOW 50h — E: response % logged
[M]: tailor first paragraph yourself. No new features.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | May 13 | 8 | 5 apps tailored | fix only | commit | |
| D2 Fri | May 14 | 8 | 5 apps + follow-ups | | | |
| D3 Sat | May 15 | 7 | Retro post publish | 5 apps | | |
| D4 Sun | May 16 | 3 | Tracker review | rest | | |
| D5 Mon | May 17 | 8 | 5 apps | | | |
| D6 Tue | May 18 | 8 | Outreaches 5 | | | |
| D7 Wed | May 19 | 5 | Log + plan | | | |

#### W34 — Outreach — May 20–26 — HOW 50h — E: 3+ conversations
Research 20 founders/EMs/maintainers. Personalized note each (stack observation + demo link). 5 substantive X replies.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | May 20 | 8 | Research 20 | 5 notes [M] | log | |
| D2 Fri | May 21 | 8 | 5 notes + 5 apps | replies 3 | | |
| D3 Sat | May 22 | 7 | Demo links per persona | replies 2 | | |
| D4 Sun | May 23 | 3 | OSS triage | rest | | |
| D5 Mon | May 24 | 8 | 10 apps | | | |
| D6 Tue | May 25 | 8 | Follow-ups | | | |
| D7 Wed | May 26 | 5 | Log conversations | | | |

#### W35 — Interview Sprint — May 27–Jun 02 — SW 42h — E: STAR 5 ready
2 mocks + record + fix. Polish only if requested.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | May 27 | 6.5 | Mock + fix | STAR drill | log | |
| D2 Fri | May 28 | 6.5 | Live-code drill | 10 apps | | |
| D3 Sat | May 29 | 6 | Polish + post | | | |
| D4 Sun | May 30 | 3 | Review | rest | | |
| D5 Mon | May 31 | 6.5 | 10 apps + interviews | | | |
| D6 Tue | Jun 01 | 6.5 | Fix | | | |
| D7 Wed | Jun 02 | 5 | Log | | | |

#### W36 — Bottleneck Fix + Review C9 — Jun 03–09 — SW 40h — E: bottleneck metric improved
If views→no reply fix README/demo; if interviews→no offer fix fundamentals.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Jun 03 | 6.5 | Diagnose bottleneck | fix 1 fully [M] | commit | |
| D2 Fri | Jun 04 | 6.5 | Patch release | fix post | | |
| D3 Sat | Jun 05 | 6 | 10 apps | | | |
| D4 Sun | Jun 06 | 3 | C9 review | rest | | |
| D5 Mon | Jun 07 | 6.5 | 10 apps | | | |
| D6 Tue | Jun 08 | 6.5 | Verify metric | | | |
| D7 Wed | Jun 09 | 5 | Retro + plan C10 | | | |

### C10 PIPELINE + CLOSE — W37–W40 — JUN 10 – JUL 07, 2027

#### W37 — Max — Jun 10–16 — SW 42h — E: tracker 100%
Re-apply where allowed + new boards. Freeze features.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Jun 10 | 6.5 | 5 apps | | log | |
| D2 Fri | Jun 11 | 6.5 | 5 apps + follow-ups | | | |
| D3 Sat | Jun 12 | 6 | 5 apps + proof post | | | |
| D4 Sun | Jun 13 | 3 | Tracker 100% check | rest | | |
| D5 Mon | Jun 14 | 6.5 | 5 apps | | | |
| D6 Tue | Jun 15 | 6.5 | Outreaches 5 | | | |
| D7 Wed | Jun 16 | 5 | Log | | | |

#### W38 — Options — Jun 17–23 — SW 40h — E: 2+ active convos
Parallel freelance/contract pitches + OSS.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Jun 17 | 6.5 | 5 apps + 2 pitches [M] | | log | |
| D2 Fri | Jun 18 | 6.5 | 5 apps + 2 pitches | | | |
| D3 Sat | Jun 19 | 6 | OSS final PR | | | |
| D4 Sun | Jun 20 | 3 | Review | rest | | |
| D5 Mon | Jun 21 | 6.5 | 5 apps | | | |
| D6 Tue | Jun 22 | 6.5 | Follow-ups | | | |
| D7 Wed | Jun 23 | 5 | Log convos | | | |

#### W39 — Sustain — Jun 24–30 — SW 38h — E: docs complete
Small flagship improvement + final retro thread.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Jun 24 | 6.5 | Small improvement | docs | commit | |
| D2 Fri | Jun 25 | 6.5 | Docs complete | retro draft | | |
| D3 Sat | Jun 26 | 6 | Publish thread + 10 apps | | | |
| D4 Sun | Jun 27 | 3 | Review | rest | | |
| D5 Mon | Jun 28 | 6.5 | 5 apps | | | |
| D6 Tue | Jun 29 | 6.5 | Archive tutorials | | | |
| D7 Wed | Jun 30 | 5 | Log | | | |

#### W40 — Final Review — Jul 01–07 — SW 35h — E: 60-sec test + 200+ touches + 3–4 deploys + 2–4 OSS
Audit repos, LinkedIn 10-mo numbers retro, handoff 10/w pipeline.

| Day | Date | Hrs | Deep-1 | Deep-2 | Proof | Done = |
|---|---|---|---|---|---|---|
| D1 Thu | Jul 01 | 6.5 | Repo audit + archive | README final | commit | |
| D2 Fri | Jul 02 | 6.5 | Final retro post (numbers+demos) | | publish | |
| D3 Sat | Jul 03 | 6 | 60-sec test with stranger | fix | | |
| D4 Sun | Jul 04 | 3 | Final review template | rest | | |
| D5 Mon | Jul 05 | 6.5 | Pipeline handoff 10/w plan | | | |
| D6 Tue | Jul 06 | 6.5 | Next 6-mo plan | | | |
| D7 Wed | Jul 07 | 3 | Close: tag v1.0-final, log | | | |

---

## 8. PUBLIC PRESENCE

**Principle:** Work → Artifact → Distribution. No post without commit/bench/demo/fix.
**X (2–3/w C1–C3 → 3–5/w C4+):** Mon log, Wed bench/GIF, Fri failure. Always image/metric/link. Reply substantively to 3 builders/week. Track builder replies, not impressions.
**LinkedIn (1/2w → 1/w):** hook result → context → tries → measurement → link, 150–250 words + image. Profile: headline role+proof, banner screenshot, featured demo+writeup+GitHub. 5–10 connects/week personalized + 3 substantive comments/week. Track views + recruiter msgs.
**Peerlist:** durable evidence only, update per release. Top 3 + live links + outcome metric + GitHub/LinkedIn/X/site.
**GitHub:** profile README (who/stack/best-3/contact), pin 3–6 best, each repo one-liner+topics+demo-top+<5m setup+arch (C4+)+CI badge+`.env.example`+LICENSE, PR workflow from C2, audit W32+W40, no streak farming.

---

## 9. OSS STRATEGY

C1–C3 docs/typos/examples/repro in used projects (Vite, Three docs, small TS libs) → 1–2 merged. C4–C6 tests/small fix <50 lines, comment-first with plan, wait ack → 1/cycle. C7+ substantive fix/feature/bench + triage. Filter `good first issue` + `help wanted`, TS/JS/C, mid-size active <7d. Never first-PR auth/security/migration. Log in `oss.md`. Targets to validate: three.js, Vite, Prisma/Drizzle, TanStack Query. Goal 4–6 opened, 2–4 merged by W40.

---

## 10. CAREER / APPLICATION SYSTEM

Exploration C1–C2: analyze 50 postings → core vs company-specific vs noise; target remote-first startups, YC, OSS-friendly. Boards: Simplify, Startup.jobs, internshipp.com, YC jobs, Wellfound, LinkedIn.
Calibration C3–C4: 5–10/w low-stakes, expect <5% early.
Positioning C5–C6: fix bottleneck (no views→README/demo; views→no reply→positioning; interviews→no offer→fundamentals).
Aggressive C7–C10: 15–20/w tailored first paragraph + demo link + 5 outreaches/w founders/EMs/maintainers (stack observation + proof) + Day-7 follow-up once.
Tracker: date/company/role/link/tailoring/response/stage/notes/follow-up. Weekly response% + conversion + hypothesis.
Interview from C6: DSA pragmatic, JS via building, junior system design (shortener/todo backend), STAR from postmortems.

---

## 11. METRICS

Capability: blind-rebuilds + debugging wins. Output: deploys/releases/OSS/benches. Public: artifact posts, views, builder replies, demo visits. Career: apps, response%, interviews, convos, referrals. Learning: retention + test pass + integration. AI: delegation success, rejection rate (>0 healthy), throughput vs defects. Review monthly; flat 2 cycles → change tactic.

---

## 12. ADAPTATION + FAILSAFES + BACKUP ROUTES

**Adaptation every W04/W08/...:** Observe (postings, agent changelogs, Three releases) → Compare vs spine → Classify (priority/impl/project/tool/position/apps) → Modify adaptive only + reason → Preserve core unless 2 cycles contrary. Core: pillars, manual-first, deploy-all, evidence>claims. Adaptive: versions, host, DB, agent, flagship A/B/C, cadence. Experiments 1-week box + kill criteria. No mid-cycle switch except breakage. New tech must win on employability/proof in 4w.

**Failsafes (Detect → Immediate → Recovery → MV → Return):** A 1w behind: evidence miss → cut 50% ship Sun → 1w → deploy>polish → 2 on-time. B 2–3w: 2 misses → freeze learning 2w finish-started → 1 deploy → test pass. C Burnout: 3d dread/halved → 3d rest + MVW 50% 1–2w → small win. D Overwhelm >3d same bug: slice 1/10th, 2h box then help/issue, postmortem counts → smaller shipped. E Obsolete: 2-cycle shift → keep concept port core 1w → ported deploy. F Agents better: credible 2x → 1w experiment adopt if defects flat → boilerplate first → throughput up. G Agents blocked: quota → manual+free+docs → MVW manual → restored/adapted. H Market down: response halved → freelance/OSS/hybrid + 5+1/w → stable. I <3% after 30 tailored: audit demo/README/keywords fix 1/w → rewrite top README+loom → >5% or interview. J 0 builder replies 4w: GIF/bench + reply others → 2/w → 1 thread. K 3 new techs/2w: backlog + 48h cool-off → finish slice → 1w clean. L >2w no deploy: 1w ship sprint no courses → deploy anything → 2w streak. M 5 repos no tests: freeze harden best-1 to L3 → tests+CI+README → audit pass. N Cannot explain shipped: 2w Stage-A rebuild → whiteboard → mastery pass. O Flagship blocked 3w: postmortem + pivot thin slice reusing auth/DB → salvage module → new MVP <4w.

**Backup MV path (if overbroad):** drop C++ deep + WebGPU compute after demo, keep TS/React/Node/Postgres + 2 hardened apps + 1 OSS + pipeline. Systems/graphics optional. Never restart. Re-add one after 4 stable weeks.

**Anti-delusion:** Aspirational flagship+users+remote startup. Probable (if consistent) strong TS/React/Node/Postgres, 3–4 deploys, MVP, WebGPU demos, verified agent flow, OSS, interviews. Minimum 2 fullstack + CI/READMEs + 1 bench + 100+ apps = career value. Never assume guaranteed job/remote/salary/virality/senior.

---

## 13. RESOURCES

MDN JS https://developer.mozilla.org/en-US/docs/Web/JavaScript + javascript.info https://javascript.info + YDKJS https://github.com/getify/You-Dont-Know-JS | HTTP MDN https://developer.mozilla.org/en-US/docs/Web/HTTP + HPBN https://hpbn.co | TS Handbook https://www.typescriptlang.org/docs/handbook/intro.html + TotalTS https://www.totaltypescript.com | React https://react.dev + Query https://tanstack.com/query/latest + Tailwind https://tailwindcss.com/docs | Node https://nodejs.org/en/docs + Express https://expressjs.com + Postgres https://www.postgresql.org/docs/ + EXPLAIN https://www.postgresql.org/docs/current/using-explain.html + Prisma https://www.prisma.io/docs + Redis https://redis.io/docs | OWASP https://owasp.org/www-project-top-ten/ + PortSwigger https://portswigger.net/web-security | Vitest https://vitest.dev + Playwright https://playwright.dev + Docker https://docs.docker.com + Actions https://docs.github.com/en/actions + Vercel https://vercel.com/docs + Railway https://docs.railway.com + Fly https://fly.io/docs + k6 https://k6.io/docs | GCC https://gcc.gnu.org/onlinedocs/ + Beej C https://beej.us/guide/bgc/ + Beej Net https://beej.us/guide/bgnet/ + OSTEP https://pages.cs.wisc.edu/~remzi/OSTEP/ + cppreference https://en.cppreference.com + Valgrind https://valgrind.org/docs/manual/ | Three https://threejs.org/docs/ + Roadmap https://threejsroadmap.com/blog + WebGPU MDN https://developer.mozilla.org/en-US/docs/Web/API/WebGPU_API + Fundamentals https://webgpufundamentals.org | Claude Code https://docs.anthropic.com/en/docs/claude-code + Codex https://developers.openai.com/codex | Jobs: internshipp https://internshipp.com/location/remote + Startup https://startup.jobs + YC https://www.ycombinator.com/jobs + Simplify https://simplify.jobs + GoodFirstIssue https://goodfirstissue.dev. One primary/cycle; if no commit in 7d drop it.

---

## 14. REVIEW TEMPLATES + DELIVERABLES

**Daily `log.md`:** `Date | Deep hrs | Commit | Test? | Blocked? | Tomorrow 1`
**Weekly (Wed 30m):** shipped? evidence? response%? waste? next-1-thing?
**4-week (3h, publish 1-para retro):**
```
CYCLE Cx (dates):
CAPABILITY: [build/explain/debug + tests]
PROJECT: [URLs, releases, CI]
PUBLIC: [posts+links, views, replies, visits]
CAREER: [apps, %, interviews, convos, OSS]
MARKET: [postings/agent/three shifts]
FAILURES / WASTE / BOTTLENECK (single biggest)
NEXT ADAPTATION: [adaptive change + reason]
CORE UNCHANGED: [confirm]
```

**Deliverables:** W12 L2 + Docker/CI + 1–2 OSS docs + 30 postings | W20 prod k6 + C echo/pool/HTTP + bench + playground + TSL + L4 + SPEC locked + 100+ touches | W28 MVP 0.9 + tests/CI + observability + diagram + postmortem + video + compute + 2nd OSS + 200+ touches | W40 v1.0 + 2nd proof + 3–4 pins 60-sec pass + 2–4 merged OSS + 20+ artifact posts + 200+ connects + 300–450 touches + STAR/mocks + 10/w handoff.
**End-state test:** stranger clone-run <5m, 10-min arch no notes, numbers shown, failures shown. Standard: “I can build it manually. I understand it. I can make an agent build it faster. I can tell when wrong. I can measure. I can explain. I have proof.”

Start D1 Thu Oct 01 tonight: init repos + log.md + first commit.
