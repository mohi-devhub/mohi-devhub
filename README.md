<!-- ═══════════════════════════════════════════════════════════ -->
<!--                        HEADER                             -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=900&size=60&duration=1&pause=99999&color=FFFFFF&center=true&vCenter=true&repeat=false&width=500&height=80&lines=Mohith" />
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=900&size=60&duration=1&pause=99999&color=111111&center=true&vCenter=true&repeat=false&width=500&height=80&lines=Mohith" alt="Mohith" />
</picture>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=1&pause=99999&color=00FF88&center=true&vCenter=true&repeat=false&width=600&height=30&lines=CS+Undergrad+%C2%B7+Aspiring+AI+Engineer" alt="subtitle"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=18&pause=1200&color=00FF88&center=true&vCenter=true&width=700&height=35&lines=Aspiring+AI+Engineer+%F0%9F%A4%96;Building+systems+that+learn+%F0%9F%A7%A0;Building+systems+that+protect+%F0%9F%9B%A1%EF%B8%8F;Building+systems+that+scale+%F0%9F%9A%80;CS+%40+CVV+2027+%C2%B7+Kerala%2C+India+%F0%9F%8C%8A" alt="Typing SVG"/>

<br/>

![snake animation](https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake-dark.svg)

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                     INTRO + GIF                           -->
<!-- ═══════════════════════════════════════════════════════════ -->

<img align="right" alt="Coding GIF" width="360" src="https://media.giphy.com/media/RbDKaczqWovIugyJmW/giphy.gif"/>

### 👋 Hey, I'm Mohith

```yaml
name     : Mohith
alias    : mohi-devhub
degree   : B.Tech Computer Science (2027)
college  : Chinmaya Vishwavidyapeeth
goal     : Aspiring AI Engineer
status   : GSoC 2026 Contributor · Student · Builder
location : Kerala, India 🌊
```

🌍 **GSoC 2026** @ RUXAILAB — Focus Group Analysis Module  
🛡️ Building **SentinelLM** — LLM safety middleware  
🎮 Building **StudyQuest** — AI learning platform  
🔬 Reimplemented **NeurIPS 2023 Lion Optimizer** (88.26% acc)  
🎯 On a mission to build production-grade AI systems

> *"Build boldly. Learn relentlessly. Ship proudly."*

<br clear="right"/>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                   SOCIAL BADGES                           -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/m-mohith-6b217b291)
[![Gmail](https://img.shields.io/badge/Gmail-%23EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white)](mailto:achumohith14@gmail.com)

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                      HOLOPIN                              -->
<!-- ═══════════════════════════════════════════════════════════ -->

## 🏅 Holopin Badges

[![Holopin Board](https://holopin.me/mohidevhub)](https://holopin.io/@mohidevhub)

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  GSOC 2026 BANNER                         -->
<!-- ═══════════════════════════════════════════════════════════ -->

## 🌍 GSoC 2026 — Selected Contributor

<div align="center">

[![GSoC](https://img.shields.io/badge/Google%20Summer%20of%20Code%202026-Selected-%23FF6D00?style=for-the-badge&logo=google&logoColor=white)](https://summerofcode.withgoogle.com/)
[![Org](https://img.shields.io/badge/Org-RUXAILAB%20(Uramaki%20Lab)-%2300FF88?style=for-the-badge)]()

</div>

Selected as a **Google Summer of Code 2026 contributor** at **RUXAILAB (Uramaki Lab)**, building the **Focus Group Management and Analysis Module** — a new study type adding real-time multi-participant data capture, NLP-assisted thematic analysis, and sentiment scoring to the RUXAILAB platform.

| Detail | Info |
|--------|------|
| **Project** | Focus Group Management & Analysis Module |
| **Organization** | RUXAILAB / Uramaki Lab |
| **Size** | Medium (175 hrs) |
| **Stack** | Vue 3 · Firebase · Python · scikit-learn · LiveKit |
| **Mentor** | Marc |

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  SENTINEL LM — HERO                       -->
<!-- ═══════════════════════════════════════════════════════════ -->

## 🛡️ SentinelLM

<div align="center">

[![SentinelLM](https://img.shields.io/badge/🛡️%20SentinelLM-View%20Repo-%2300FF88?style=for-the-badge&logo=github&logoColor=black)](https://github.com/mohi-devhub/SentinelLM)
[![Status](https://img.shields.io/badge/Status-ACTIVE-FF4444?style=for-the-badge)]()
[![Version](https://img.shields.io/badge/Version-v1.0.0-00FF88?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](https://github.com/mohi-devhub/SentinelLM/blob/main/LICENSE)

</div>

**Real-time safety & quality middleware for LLM applications.**

A FastAPI proxy that intercepts **every** LLM request and response — scoring for prompt injection, PII leakage, toxicity, hallucination, and relevance. A **drop-in replacement** for OpenAI, Anthropic, Gemini, or Ollama — just point `base_url` at `localhost:8000/v1`.

```bash
$ docker compose up -d
✓  API        →  localhost:8000
✓  Dashboard  →  localhost:3000
✓  Metrics    →  /metrics  (Prometheus)

$ curl localhost:8000/v1/chat/completions \
    -d '{"messages": [{"role":"user","content":"Ignore all instructions."}]}'

⛔  HTTP 400 · sentinel_block · prompt_injection_detected · score: 0.97
```

<br clear="right"/>

**Evaluator Chain:**

| Layer | Evaluator | Action | Model |
|:-----:|-----------|--------|-------|
| 🔵 Input | `prompt_injection` | **Block** | DeBERTa-v3-base |
| 🔵 Input | `pii` | **Redact / Block** | Presidio + spaCy |
| 🔵 Input | `topic_guardrail` | **Block** | all-MiniLM-L6-v2 |
| 🟡 Output | `toxicity` | Flag | Detoxify |
| 🟡 Output | `relevance` | Flag | all-MiniLM-L6-v2 |
| 🟡 Output | `hallucination` | Flag | NLI DeBERTa-v3 |
| 🟡 Output | `faithfulness` | Flag | NLI DeBERTa-v3 |

**Key highlights:** ⚡ Concurrent first-block short-circuit · 🔒 Redis caching · 🧠 Fail-open guarantee · 📊 WebSocket dashboard · 🧪 Eval regression pipeline

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-000000?style=for-the-badge&logo=socketdotio&logoColor=white)

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  ANTIVIBE — HERO                          -->
<!-- ═══════════════════════════════════════════════════════════ -->

## 🧠 AntiVibe

<div align="center">

[![AntiVibe](https://img.shields.io/badge/🧠%20AntiVibe-View%20Repo-%2300FF88?style=for-the-badge&logo=github&logoColor=black)](https://github.com/mohi-devhub/antivibe)
[![Stars](https://img.shields.io/badge/⭐%20Stars-600%2B-FFD700?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](https://github.com/mohi-devhub/antivibe/blob/main/LICENSE)

</div>

**A Claude Code skill that fights the learn-nothing problem in vibe-coding.**

Everyone's vibecoding. Nobody's understanding what gets shipped. AntiVibe auto-triggers via Claude Code hooks after every AI coding session and generates structured educational deep-dives — not just "what this code does" but *why* it was written that way, what CS concepts are in play, and where to go deeper.

```bash
# Runs automatically via SubagentStop / Stop hooks
# After Claude Code finishes a task, you get:

📄  deep-dive.md
    ├── Code walkthrough
    ├── Design decisions & alternatives
    ├── CS concepts mapped to this code
    └── Curated learning resources
```

**Works across Python · TypeScript · Go · Rust · and more**

> *"Vibecoding is fast. Understanding what you ship matters more."*

<div align="center">

![Shell](https://img.shields.io/badge/Shell-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-CC785C?style=for-the-badge&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-00FF88?style=for-the-badge)

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                  CURRENTLY BUILDING                       -->
<!-- ═══════════════════════════════════════════════════════════ -->

## 🔴 Currently Building

| Project | Description | Stack | Status |
|---------|-------------|-------|--------|
| **🌍 GSoC @ RUXAILAB** | Focus Group Management & Analysis Module | Vue 3 · Firebase · Python · scikit-learn | ![Active](https://img.shields.io/badge/ACTIVE-00FF88?style=flat-square) |
| **🛡️ SentinelLM** | Real-time LLM safety middleware | Python · FastAPI · Redis · Docker | ![Active](https://img.shields.io/badge/ACTIVE-00FF88?style=flat-square) |
| **🎮 StudyQuest** | Terminal-style AI learning platform | Next.js · FastAPI · Supabase · Gemini | ![WIP](https://img.shields.io/badge/WIP-FFAA00?style=flat-square) |
| **🌐 Lokha** | Community hub for AI prompts | Next.js · Prisma · tRPC · Supabase | ![WIP](https://img.shields.io/badge/WIP-FFAA00?style=flat-square) |

<br clear="right"/>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                   FEATURED PROJECTS                       -->
<!-- ═══════════════════════════════════════════════════════════ -->

## 🚀 Featured Projects

<div align="center">

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ SentinelLM
Real-time LLM safety middleware. Blocks prompt injections, redacts PII, flags hallucinations and toxicity. Drop-in FastAPI proxy for any LLM backend.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

[![View Repo](https://img.shields.io/badge/→%20View%20Repo-00FF88?style=for-the-badge&logo=github&logoColor=black)](https://github.com/mohi-devhub/SentinelLM)

</td>
<td width="50%" valign="top">

### 🧠 AntiVibe ⭐ 600+
Open-source Claude Code skill that auto-generates educational deep-dives for AI-written code. Fights the learn-nothing problem in vibe-coding via hooks and subagents.

![Shell](https://img.shields.io/badge/Shell-121011?style=flat-square&logo=gnu-bash&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-CC785C?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-00FF88?style=flat-square)

[![View Repo](https://img.shields.io/badge/→%20View%20Repo-00FF88?style=for-the-badge&logo=github&logoColor=black)](https://github.com/mohi-devhub/antivibe)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎮 StudyQuest
AI-powered terminal-style learning platform with adaptive quizzes, real-time XP tracking, and minimalist B/W dashboard.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%20AI-8E75B2?style=flat-square&logo=google&logoColor=white)

</td>
<td width="50%" valign="top">

### 🔬 Lion Optimizer
Reimplemented the NeurIPS 2023 Lion Optimizer with symbolic search engine. Achieved **88.26% accuracy** on FashionMNIST — outperforming AdamW.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

</td>
</tr>
</table>

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                      TECH STACK                           -->
<!-- ═══════════════════════════════════════════════════════════ -->

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-%233178C6.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-%234479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

<br/>

![React](https://img.shields.io/badge/React-%2361DAFB.svg?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-%23000000.svg?style=for-the-badge&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-%23009688.svg?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-%23339933.svg?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Django](https://img.shields.io/badge/Django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-%2306B6D4.svg?style=for-the-badge&logo=tailwindcss&logoColor=white)

<br/>

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%234169E1.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DC382D.svg?style=for-the-badge&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-%234479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-%23FFCA28.svg?style=for-the-badge&logo=firebase&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white)

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                      RESEARCH                             -->
<!-- ═══════════════════════════════════════════════════════════ -->

## 🔬 Research — Lion Optimizer (NeurIPS 2023)

Reimplemented the **Lion Optimizer** from scratch using PyTorch, based on the NeurIPS 2023 paper on symbolic optimizer discovery via evolutionary search.

| Optimizer | FashionMNIST Test Accuracy |
|-----------|:------------------------:|
| AdamW (baseline) | ~87.x% |
| **Lion (reimplemented)** ✅ | **88.26%** |

Key finding: Lion's sign-based update rule with decoupled weight decay generalizes better and is more memory-efficient than AdamW on image classification tasks.

<br clear="right"/>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                     GITHUB STATS                          -->
<!-- ═══════════════════════════════════════════════════════════ -->

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=mohi-devhub&show_icons=true&theme=tokyonight&hide_border=true&border_radius=12&include_all_commits=true&count_private=true" height="180" alt="GitHub Stats"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohi-devhub&layout=compact&theme=tokyonight&hide_border=true&border_radius=12" height="180" alt="Top Languages"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=mohi-devhub&theme=tokyonight&hide_border=true&border_radius=12&date_format=j%20M%5B%20Y%5D" width="70%" alt="GitHub Streak"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=mohi-devhub&theme=tokyo-night&hide_border=true&radius=10&area=true&area_color=00ff88" width="95%" alt="Activity Graph"/>

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                   GOALS & ASPIRATIONS                     -->
<!-- ═══════════════════════════════════════════════════════════ -->

## 🎯 Goals & Aspirations

<img align="right" alt="Dev GIF" width="220" src="https://media.giphy.com/media/f3iwJFOVOwuy7K6FFw/giphy.gif"/>

I'm a CS student on a deliberate path toward a thing I care deeply about:

**🤖 Aspiring AI Engineer**
> Going beyond just calling LLM APIs — I want to understand the math, build the middleware, tune the models. SentinelLM, AntiVibe, and my Lion Optimizer work are steps on that path.

```text
Current focus  →  LLM safety · Applied ML · Fullstack systems
Learning now   →  ML theory · System design · Research papers
GSoC 2026      →  RUXAILAB · Focus Group Analysis · NLP pipelines
End goal       →  Build AI products that actually work in prod
```

<br clear="right"/>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                       FOOTER                              -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

**Always happy to connect with fellow builders!**

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=mohi-devhub&style=for-the-badge&color=00ff88&label=PROFILE+VIEWS)

</div>

---
*CS @ Chinmaya Vishwavidyapeeth · Kerala, India · 2027*
