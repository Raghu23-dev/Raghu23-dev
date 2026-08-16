<!-- ═══════════════════════════════ HERO BANNER ═══════════════════════════════ -->
<a href="https://github.com/Raghu23-dev">
  <img width="100%" alt="Raghuram P — GenAI Full-Stack Engineer" src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1021,45:4c1d95,100:6d28d9&height=210&section=header&text=Raghuram%20P&fontSize=58&fontColor=ffffff&fontAlignY=34&desc=GenAI%20Full-Stack%20Engineer%20%C2%B7%20I%20build%20the%20AI%20tools%20other%20engineers%20build%20with&descSize=17&descAlignY=56&animation=fadeIn" />
</a>

<!-- ═══════════════════════════════ TYPING TAGLINE ═══════════════════════════════ -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&pause=1100&color=A78BFA&center=true&vCenter=true&width=880&height=45&lines=GenAI+Full-Stack+Engineer;Multi-Agent+Systems+%C2%B7+RAG+%C2%B7+Real-Time+Streaming;Angular+%C2%B7+FastAPI+%C2%B7+Python+%C2%B7+TypeScript;I+build+the+AI+tools+other+engineers+build+with." alt="What I do" />
</div>

<!-- ═══════════════════════════════ SOCIAL / STATUS BADGES ═══════════════════════════════ -->
<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Raghu23-dev&label=Profile%20views&color=6d28d9&style=flat-square" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/Raghu23-dev?label=Followers&style=flat-square&color=4c1d95&logo=github&logoColor=white" alt="Followers" />
  <a href="https://www.linkedin.com/in/raghuram-p"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://raghuram.vercel.app"><img src="https://img.shields.io/badge/Portfolio-1d5fd4?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://github.com/Raghu23-dev/Raghu23-dev/raw/main/Raghuram_P_Resume.pdf"><img src="https://img.shields.io/badge/R%C3%A9sum%C3%A9-b91c1c?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Résumé" /></a>
  <a href="mailto:raghu.builds&#64;gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Open%20to-GenAI%20%C2%B7%20Full--Stack%20%C2%B7%20LLM%20Systems-1f6feb?style=flat-square" alt="Open to work" />
</div>

<!-- ═══════════════════════════════ IMPACT STRIP ═══════════════════════════════ -->
<div align="center">
  <br />
  <img src="https://img.shields.io/badge/Production%20Systems-6-6d28d9?style=for-the-badge" alt="6 systems" />
  <img src="https://img.shields.io/badge/Daily%20Users-3K%2B-7c3aed?style=for-the-badge" alt="3K+ users" />
  <img src="https://img.shields.io/badge/Design%20System-90%2B%20components-4c1d95?style=for-the-badge" alt="90+ components" />
</div>

---

<!-- ═══════════════════════════════ ABOUT ═══════════════════════════════ -->
### 🚀 About Me

> **I build the AI tools other engineers build with.**

- 🧠 **GenAI Full-Stack Engineer** — I design and ship AI-native enterprise platforms end-to-end: from **multi-agent LLM orchestration** and **RAG retrieval** down to Angular frontends, async FastAPI services, and the **real-time streaming backbones** that hold them together. My work reaches **thousands of developers, designers, and product teams daily**.
- 🤖 **Co-built & production-hardened an AI process-orchestration engine** — multi-step LLM workflows with **human-in-the-loop approval gates**, governed multi-provider model routing, **Kafka** multi-pod streaming, conversation compaction, and per-run cost tracking. *(2K+ daily users.)*
- 🧑‍💻 **Built the backend for an AI coding plugin for VS Code** (a Cursor / Claude-Code-class tool) — re-architected a single-agent prototype into a **multi-agent orchestration system** (Main-Agent + sub-agents on CrewAI, 30+ tools, skills & command frameworks, conversational memory, streaming). *(3K+ daily users across 5+ enterprise environments.)*
- 🔎 **Contributed to a hybrid code-retrieval RAG pipeline** — Tree-sitter parsing + SQLite FTS5 BM25 + sqlite-vec + embeddings + **Cohere rerank** + **RRF fusion** + an 8-intent query planner. **Owned the ingestion path**: resumable multi-phase indexing, SSE progress streaming, two-tier admission control.
- ⚡ **Designed an SSE + Redis Streams real-time backbone** — replaced client polling with a decoupled pub/sub transport: per-session connection deduplication, exponential backoff, `Last-Event-ID` checkpointing, and history backfill on zero-replay reconnect.
- 🎨 **Co-built a GenAI wireframe generator** (briefs/sketches/prompts → UI artifacts) and a **prompt-to-React code-gen system**; **led a React → Angular re-architecture**; and shipped a **90+ component enterprise design system** as a private NPM package.
- 🌱 Currently going deeper on **LLMOps, evaluation harnesses, and distributed-systems design**.
- 💬 Ask me about **multi-agent orchestration, production RAG, and real-time streaming at scale**.
- 📫 Reach me at **raghu.builds&#64;gmail.com** · 🌐 [Portfolio](https://raghuram.vercel.app) · 💼 [LinkedIn](https://www.linkedin.com/in/raghuram-p) · 📄 [Résumé (PDF)](https://github.com/Raghu23-dev/Raghu23-dev/raw/main/Raghuram_P_Resume.pdf)

---

<!-- ═══════════════════════════════ SYSTEMS SHIPPED ═══════════════════════════════ -->
### 📦 Open Source

*All three published on PyPI. Every metric below is measured and reproducible from the repo.*

| Project | What it does | Stack |
|---|---|---|
| **[tessera](https://github.com/Raghu23-dev/tessera)**<br/>`pip install tessera-transcript` | Keeps LLM transcripts valid when a stream is cut, a retry fires, or context is compacted. Guarantees every `tool_use` has a matching `tool_result` across compaction, interruption and provider swap — the error behind **1,331 open GitHub issues**. Property-tested with Hypothesis, 97% coverage on an enforced floor, zero runtime dependencies. | `Python` · `Hypothesis` · `mypy --strict` |
| **[verity](https://github.com/Raghu23-dev/verity)**<br/>`pip install verity-retrieval` | Measures retrieval instead of assuming it, and fixes filtered vector search that silently returns fewer results than requested. At 3% filter selectivity, measured against an exhaustive oracle: post-filtering returns **0.36 of 10** results; predicate pushdown returns **10.00 of 10**. Deterministic recall@k / nDCG@k — no LLM judge. | `Python` · `numpy` · `Hypothesis` |
| **[sentinel](https://github.com/Raghu23-dev/sentinel)**<br/>`pip install sentinel-gate` | Human-in-the-loop approval for agents. The timeout direction follows the risk — recoverable work proceeds unattended, irreversible work does not — and **eight distinct failure modes all produce a refusal rather than a permit**, because a permission check that cannot complete has not granted permission. | `Python` · `SQLite` · `Hypothesis` |
| **[atlas](https://github.com/Raghu23-dev/atlas)** | This profile's [portfolio site](https://raghuram.vercel.app). One content layer feeds every page, the sitemap and `llms.txt`; attribution is a typed field; the build fails on a dead link. | `Next.js 16` · `React 19` · `TypeScript` · `Velite` |

---

### ✍️ Writing

Findings and postmortems, not tutorials. Every measured claim links to something you can re-run.

| Piece | |
|---|---|
| **[Your filtered vector search is returning 3 results when you asked for 10](https://raghuram.vercel.app/writing/filtered-vector-search-returns-fewer-results)** | Most vector stores apply metadata filters *after* the index returns. Measured at 3% selectivity: **0.36 of 10** results, **100% of queries short** — and no error, so nothing tells you. Reproducible with `verity bench`. |
| **[The check passed. The thing it checks was broken.](https://raghuram.vercel.app/writing/checks-that-pass-while-broken)** | Four false-greens in one day: a link checker that followed a redirect into a login page and reported 200, a compiler that logged an error and exited zero, a rule that only printed the number it was supposed to enforce, and a fuzzer whose oracle flagged correct behaviour as 1,300 failures. |

---

### 🧩 Systems I've Shipped

> Built for enterprise clients across hardware, banking & fintech domains. Source is proprietary — **company and product names withheld**; architecture, tech, and scale are summarized below.

#### 🤖 AI Coding & Agent Infrastructure

| System | What it is & tech | Scale |
|---|---|:--:|
| **AI Coding Assistant** *(VS Code plugin)* | In-editor AI pair-programmer grounded in your codebase — multi-agent orchestration (Main-Agent + sub-agents), 30+ tools, skills & command frameworks, conversational memory, compaction, human-in-the-loop execution, real-time streaming.<br>`Python` · `FastAPI` · `CrewAI` · `ReAct` · `SSE` · `AWS Bedrock` · `Azure OpenAI` | **3K+**<br>daily |
| **AI Process-Orchestration Engine** | Runs multi-step LLM workflows as pluggable process-packs — HITL approval gates, governed multi-provider routing, Kafka multi-pod streaming, compaction, per-run cost tracking.<br>`Python` · `FastAPI` · `CrewAI` · `Apache Kafka` · `SSE` · `Redis` · `OpenTelemetry` | **2K+**<br>daily |
| **Hybrid Code-RAG Pipeline** *(contributor; owned ingestion)* | Codebase indexing + hybrid retrieval grounding the agents — lexical + semantic + structural signals fused with RRF and an 8-intent query planner.<br>`Tree-sitter` · `SQLite FTS5 BM25` · `sqlite-vec` · `Azure OpenAI` · `Cohere Rerank` · `RRF` | powers<br>the agents |

#### 🎨 AI App-Generation & Platforms

| System | What it is & tech | Impact |
|---|---|:--:|
| **AI App-Generation Platform** | Prompt-to-app, image-to-app & wireframe generation — designed the **SSE + Redis Streams** real-time backbone; re-architected the frontend **React → Angular**.<br>`Angular` · `RxJS` · `Signals` · `FastAPI` · `Redis Streams` · `SSE` | prompt →<br>running app |
| **AI Product-Planning Platform** | Multi-step AI-assisted planning flow (Brainstormer → Persona → SWOT → Roadmap → Summary) — async services on Postgres.<br>`Angular` · `FastAPI` · `PostgreSQL` · `asyncpg` · `AWS RDS IAM` · `Alembic` · `Redis` | end-to-end<br>owner |
| **Enterprise Angular Design System** | 90+ standalone components — OnPush change detection, tree-shaking, token-driven theming, GSAP animation infra; published as a private NPM package.<br>`Angular` · `TypeScript` · `SCSS` · `GSAP` · `ng-packagr` | **90+**<br>components |

---

<!-- ═══════════════════════════════ TECH STACK ═══════════════════════════════ -->
### 🛠️ Tech Stack

<div align="center">
  <table>
    <tr>
      <td align="center" width="80"><img src="https://techstack-generator.vercel.app/python-icon.svg" width="48" height="48" /><br><sub><b>Python</b></sub></td>
      <td align="center" width="80"><img src="https://techstack-generator.vercel.app/ts-icon.svg" width="48" height="48" /><br><sub><b>TypeScript</b></sub></td>
      <td align="center" width="80"><img src="https://techstack-generator.vercel.app/js-icon.svg" width="48" height="48" /><br><sub><b>JavaScript</b></sub></td>
      <td align="center" width="80"><img src="https://skillicons.dev/icons?i=fastapi" width="48" height="48" /><br><sub><b>FastAPI</b></sub></td>
      <td align="center" width="80"><img src="https://skillicons.dev/icons?i=angular" width="48" height="48" /><br><sub><b>Angular</b></sub></td>
      <td align="center" width="80"><img src="https://techstack-generator.vercel.app/react-icon.svg" width="48" height="48" /><br><sub><b>React</b></sub></td>
      <td align="center" width="80"><img src="https://skillicons.dev/icons?i=nextjs" width="48" height="48" /><br><sub><b>Next.js</b></sub></td>
    </tr>
    <tr>
      <td align="center" width="80"><img src="https://skillicons.dev/icons?i=tailwind" width="48" height="48" /><br><sub><b>Tailwind</b></sub></td>
      <td align="center" width="80"><img src="https://skillicons.dev/icons?i=sass" width="48" height="48" /><br><sub><b>SCSS</b></sub></td>
      <td align="center" width="80"><img width="46" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/grpc.png"/><br><sub><b>gRPC</b></sub></td>
      <td align="center" width="80"><img width="46" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/websocket.png"/><br><sub><b>WebSocket</b></sub></td>
      <td align="center" width="80"><img src="https://techstack-generator.vercel.app/nginx-icon.svg" width="48" height="48" /><br><sub><b>Nginx</b></sub></td>
      <td align="center" width="80"><img src="https://skillicons.dev/icons?i=postgres" width="48" height="48" /><br><sub><b>PostgreSQL</b></sub></td>
      <td align="center" width="80"><img src="https://skillicons.dev/icons?i=redis" width="48" height="48" /><br><sub><b>Redis</b></sub></td>
    </tr>
    <tr>
      <td align="center" width="80"><img src="https://skillicons.dev/icons?i=kafka" width="48" height="48" /><br><sub><b>Kafka</b></sub></td>
      <td align="center" width="80"><img src="https://skillicons.dev/icons?i=sqlite" width="48" height="48" /><br><sub><b>SQLite</b></sub></td>
      <td align="center" width="80"><img src="https://skillicons.dev/icons?i=mongodb" width="48" height="48" /><br><sub><b>MongoDB</b></sub></td>
      <td align="center" width="80"><img src="https://techstack-generator.vercel.app/docker-icon.svg" width="48" height="48" /><br><sub><b>Docker</b></sub></td>
      <td align="center" width="80"><img src="https://techstack-generator.vercel.app/kubernetes-icon.svg" width="48" height="48" /><br><sub><b>K8s</b></sub></td>
      <td align="center" width="80"><img src="https://techstack-generator.vercel.app/aws-icon.svg" width="48" height="48" /><br><sub><b>AWS</b></sub></td>
      <td align="center" width="80"><img src="https://skillicons.dev/icons?i=azure" width="48" height="48" /><br><sub><b>Azure</b></sub></td>
    </tr>
    <tr>
      <td align="center" width="80"><img src="https://skillicons.dev/icons?i=prometheus" width="48" height="48" /><br><sub><b>Prometheus</b></sub></td>
      <td align="center" width="80"><img src="https://skillicons.dev/icons?i=grafana" width="48" height="48" /><br><sub><b>Grafana</b></sub></td>
      <td align="center" width="80"><img width="46" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/playwright.png"/><br><sub><b>Playwright</b></sub></td>
      <td align="center" width="80"><img src="https://skillicons.dev/icons?i=linux" width="48" height="48" /><br><sub><b>Linux</b></sub></td>
      <td align="center" width="80"><img src="https://skillicons.dev/icons?i=git" width="48" height="48" /><br><sub><b>Git</b></sub></td>
      <td align="center" width="80"><img src="https://techstack-generator.vercel.app/github-icon.svg" width="48" height="48" /><br><sub><b>GitHub</b></sub></td>
      <td align="center" width="80"><img src="https://skillicons.dev/icons?i=vscode" width="48" height="48" /><br><sub><b>VS Code</b></sub></td>
    </tr>
  </table>
  <sub>Every icon above maps to a line in my verified skills inventory — ask me to walk you through any of them.</sub>
</div>

**🧠 GenAI / LLM**
&nbsp;
![CrewAI](https://img.shields.io/badge/CrewAI-FF5A50?style=flat-square&logo=robotframework&logoColor=white)
![Multi-Agent](https://img.shields.io/badge/Multi--Agent%20Systems-4c1d95?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-6d28d9?style=flat-square)
![ReAct](https://img.shields.io/badge/ReAct-7c3aed?style=flat-square)
![HITL](https://img.shields.io/badge/Human--in--the--Loop-1f6feb?style=flat-square)
![AWS Bedrock](https://img.shields.io/badge/AWS%20Bedrock-232F3E?style=flat-square&logo=amazonaws&logoColor=FF9900)
![Azure OpenAI](https://img.shields.io/badge/Azure%20OpenAI-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Cohere](https://img.shields.io/badge/Cohere%20Rerank-39594D?style=flat-square)
![Tree-sitter](https://img.shields.io/badge/Tree--sitter-333333?style=flat-square)
![Vector DBs](https://img.shields.io/badge/Vector%20DBs%20%26%20Embeddings-5b21b6?style=flat-square)

**⚙️ Backend · Real-Time · Observability**
&nbsp;
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![SSE](https://img.shields.io/badge/Server--Sent%20Events-f97316?style=flat-square)
![Redis Streams](https://img.shields.io/badge/Redis%20Streams-DC382D?style=flat-square&logo=redis&logoColor=white)
![Event-Driven](https://img.shields.io/badge/Event--Driven-6d28d9?style=flat-square)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)

**🎨 Frontend extras**
&nbsp;
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=flat-square&logo=reactivex&logoColor=white)
![Signals](https://img.shields.io/badge/Angular%20Signals-c3002f?style=flat-square)
![Monaco](https://img.shields.io/badge/Monaco%20Editor-1f6feb?style=flat-square&logo=visualstudiocode&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=white)

---

<!--
  ═══════════════════════════════ GITHUB STATS — INTENTIONALLY ABSENT ═══════════════════════════════

  Removed 2026-08-16: the activity graph and contribution snake.

  Not because they were broken — they rendered fine. Because they rendered a near-flat line
  directly beneath badges claiming 6 production systems and 3K+ daily users, and that
  contradiction reads as inflation.

  Root cause is not inactivity: substantive commits were authored under a work-domain email
  that GitHub cannot link to this account, so real work never reached the contribution graph.
  Identity is fixed going forward (raghu2308.dev@gmail.com).

  These come back when the graph reflects the work — not before. A decoration that argues
  against your own claims is worse than no decoration.

  Earlier removal, 2026-08-06: github-profile-summary-cards and streak-stats.demolab.com —
  provider-wide 500/503 outages, verified against control usernames.
-->

<!-- ═══════════════════════════════ PHILOSOPHY ═══════════════════════════════ -->
### ⚡ Philosophy

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&pause=1500&color=A78BFA&center=true&vCenter=true&width=820&height=40&lines=Design+deep+modules%2C+ship+thin+interfaces.;Ground+every+agent+in+real+context.;Make+it+stream%2C+make+it+survive+production." alt="Principles" />
</div>

> I work best where **product UX, distributed systems, and AI infrastructure** meet —
> building tools that take people from an idea to working software, faster.

---

<!-- ═══════════════════════════════ CONNECT ═══════════════════════════════ -->
### 🤝 Connect

<div align="center">
  <a href="https://www.linkedin.com/in/raghuram-p"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://raghuram.vercel.app"><img src="https://img.shields.io/badge/Portfolio-1d5fd4?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://github.com/Raghu23-dev/Raghu23-dev/raw/main/Raghuram_P_Resume.pdf"><img src="https://img.shields.io/badge/R%C3%A9sum%C3%A9-b91c1c?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Résumé" /></a>
  <a href="mailto:raghu.builds&#64;gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/Raghu23-dev"><img src="https://img.shields.io/badge/Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</div>

<img width="100%" alt="footer" src="https://capsule-render.vercel.app/api?type=waving&color=0:6d28d9,55:4c1d95,100:0b1021&height=120&section=footer" />

<!-- profile readme -->
