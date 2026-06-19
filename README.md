<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:0D1117&height=120&section=header&text=&animation=fadeIn)

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&duration=3500&pause=1200&color=E6EDF3&center=true&vCenter=true&width=750&height=70&lines=Aaditya+Agarwal;Software+Engineer+%2F%2F+AI+Researcher;Local+LLM+Infrastructure" alt="Typing SVG" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=400&size=13&duration=4500&pause=2500&color=8B949E&center=true&vCenter=true&width=680&height=28&lines=B.Tech+CSE+(AI%2FML)+%E2%80%94+VIT+Bhopal+%2F%2F+Co-Lead%2C+Gen+AI+Community+%2F%2F+Open+to+Internships" alt="Subtitle" />

<br/>

[![Email](https://img.shields.io/badge/EMAIL-aadityaagarwal947%40gmail.com-8B949E?style=flat-square&logo=gmail&logoColor=8B949E&labelColor=161B22)](mailto:aadityaagarwal947@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-aaditya--agarwal-8B949E?style=flat-square&logo=linkedin&logoColor=8B949E&labelColor=161B22)](https://www.linkedin.com/in/aaditya-agarwal-457922379)
&nbsp;
[![X](https://img.shields.io/badge/X-aaditya8979__-8B949E?style=flat-square&logo=x&logoColor=8B949E&labelColor=161B22)](https://x.com/aaditya8979_)
&nbsp;
[![CodeForces](https://img.shields.io/badge/CODEFORCES-aaditya8979-8B949E?style=flat-square&logo=codeforces&logoColor=8B949E&labelColor=161B22)](https://codeforces.com/profile/aaditya8979)
&nbsp;
![Visitors](https://komarev.com/ghpvc/?username=aaditya8979&style=flat-square&color=8B949E&label=PROFILE+VIEWS)

</div>

<br/>

---

<!-- ─────────────────────────────────────────────────── -->
<!--  OPERATOR PROFILE                                   -->
<!-- ─────────────────────────────────────────────────── -->

<br/>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=11&duration=99999&pause=99999&color=58A6FF&center=true&vCenter=true&width=200&height=20&lines=%2F%2F+OPERATOR+PROFILE" alt="section" />
</div>

<br/>

```yaml
operator    : Aaditya Agarwal
designation : B.Tech CSE (AI & ML) — VIT Bhopal, Expected 2029
location    : Firozabad, Uttar Pradesh, India
status      : Open to internships and research collaborations

thesis:
  Small local models don't need to be smarter — they need
  better context and deterministic verification wrapped
  around them. That premise drives everything below.

focus:
  - Local LLM inference (Qwen-7B, quantised, zero-cloud)
  - Code Property Graphs & AST-based context compression
  - Deterministic verification of probabilistic systems
  - LLM-as-a-Judge evaluation infrastructure
  - Multi-agent orchestration

currently:
  - Co-Lead, AI/ML & Innovation Team — Gen AI Community, VIT Bhopal
  - Extending VECTOR to multi-file repository modification
  - Writing a second research preprint on local agent orchestration
```

<br/>

---

<!-- ─────────────────────────────────────────────────── -->
<!--  FLAGSHIP WORK                                      -->
<!-- ─────────────────────────────────────────────────── -->

<br/>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=11&duration=99999&pause=99999&color=58A6FF&center=true&vCenter=true&width=200&height=20&lines=%2F%2F+FLAGSHIP+WORK" alt="section" />
</div>

<br/>

<div align="center">

### 🔬 VECTOR

**A local 7B model performing repository-level code modification — zero cloud, zero fine-tuning.**

[![Open VSX](https://img.shields.io/badge/OPEN_VSX-210%2B_installs-238636?style=for-the-badge&labelColor=161B22)](https://open-vsx.org/extension/aaditya8979/vector-coder)
[![Preprint](https://img.shields.io/badge/RESEARCH-Preprint-6E40C9?style=for-the-badge&labelColor=161B22)](https://zenodo.org/records/20708135?preview=1&token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6IjdkYTBmNzMwLTU3ZGUtNGY3My1iYWRhLWY3ZTU3NTZjMDY2YSIsImRhdGEiOnt9LCJyYW5kb20iOiIxZDQ1ZWZiOTBkZmFjY2Y0NjNjNWRkY2FlNmVkYzBlZSJ9.qm45K-tCBvYffi9Bth0DD3rZ88tzsRzTh4jF0MAFS4H1H2p2TXE2Q1nO_HCjfstjiSjyxLS4qna_wT6rClf2bg)
[![GitHub](https://img.shields.io/badge/GITHUB-VECTOR-1F6FEB?style=for-the-badge&logo=github&labelColor=161B22)](https://github.com/aaditya8979/VECTOR)

Compresses 50,000+ token repositories to ≤2,500 tokens via Code Property Graph
traversal (**TSDC**), then wraps a local Qwen-7B model in a **5-layer deterministic
verification pipeline** — AST symbol checking, strict `mypy`, `pytest` guards, structural
diff validation, and runtime sandboxing — so hallucinated code never reaches the
file system.

`84.8% pass@1 on HumanEval` · `Python AST` · `Tree-sitter` · `Qwen-7B` · `VS Code Extension`

<br/>

### ⚙️ AgentCI

**An enterprise-grade AI evaluation CI/CD platform — a GitHub-native quality gate.**

[![PyPI](https://img.shields.io/badge/PyPI-agentci--aadi-238636?style=for-the-badge&logo=pypi&labelColor=161B22)](https://pypi.org/project/agentci-aadi)
[![GitHub App](https://img.shields.io/badge/GITHUB_APP-Install-1F6FEB?style=for-the-badge&logo=github&labelColor=161B22)](https://github.com/apps/agent-ci-aaditya)

`pip install agentci-aadi` installs an **LLM-as-a-Judge consensus panel** that uses
**Welch's t-test** for statistically verified AI behaviour analysis across a 50-scenario
testing suite, orchestrated on **Temporal** for durable execution with zero-data-loss
retries on partial API failures.

`Python` · `FastAPI` · `Temporal` · `Docker` · `PostgreSQL`

<br/>

### 🧭 NeuralOps

**Intelligent LLM routing across 7 providers — cost-free inference at scale.**

[![Live](https://img.shields.io/badge/LIVE-neuralops-238636?style=for-the-badge&labelColor=161B22)](https://neuralops-three.vercel.app)

Routes queries across **Google, Groq, Anthropic, and OpenAI** by semantic complexity
to maximise free-tier utilisation. Ships a Redis-backed circuit breaker with automatic
failover (**99.9% uptime**), an OpenAI-compatible API gateway secured by HMAC key
validation, and semantic caching via SHA-256 hashing to cut redundant calls and TTFT.

`Next.js` · `FastAPI` · `PostgreSQL` · `Redis` · `pgvector`

</div>

<br/>

---

<!-- ─────────────────────────────────────────────────── -->
<!--  TECH STACK                                         -->
<!-- ─────────────────────────────────────────────────── -->

<br/>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=11&duration=99999&pause=99999&color=58A6FF&center=true&vCenter=true&width=200&height=20&lines=%2F%2F+TECH+STACK" alt="section" />
</div>

<br/>

<div align="center">

**CORE LANGUAGES**

![Python](https://img.shields.io/badge/Python-161B22?style=for-the-badge&logo=python&logoColor=E6EDF3)
![C++](https://img.shields.io/badge/C++-161B22?style=for-the-badge&logo=cplusplus&logoColor=E6EDF3)
![TypeScript](https://img.shields.io/badge/TypeScript-161B22?style=for-the-badge&logo=typescript&logoColor=E6EDF3)
![JavaScript](https://img.shields.io/badge/JavaScript-161B22?style=for-the-badge&logo=javascript&logoColor=E6EDF3)
![Java](https://img.shields.io/badge/Java-161B22?style=for-the-badge&logo=openjdk&logoColor=E6EDF3)

<br/>

**AI / ML & LLM INFRASTRUCTURE**

![Local LLMs](https://img.shields.io/badge/Local_LLMs-161B22?style=for-the-badge&logo=ollama&logoColor=E6EDF3)
![Tree-sitter](https://img.shields.io/badge/Tree--sitter-161B22?style=for-the-badge&logo=treesitter&logoColor=E6EDF3)
![Qwen](https://img.shields.io/badge/Qwen_2.5_Coder-161B22?style=for-the-badge&logo=huggingface&logoColor=E6EDF3)
![RAG](https://img.shields.io/badge/RAG-161B22?style=for-the-badge)
![pgvector](https://img.shields.io/badge/pgvector-161B22?style=for-the-badge&logo=postgresql&logoColor=E6EDF3)

<br/>

**BACKEND & INFRASTRUCTURE**

![FastAPI](https://img.shields.io/badge/FastAPI-161B22?style=for-the-badge&logo=fastapi&logoColor=E6EDF3)
![Temporal](https://img.shields.io/badge/Temporal-161B22?style=for-the-badge&logo=temporal&logoColor=E6EDF3)
![Next.js](https://img.shields.io/badge/Next.js-161B22?style=for-the-badge&logo=nextdotjs&logoColor=E6EDF3)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-161B22?style=for-the-badge&logo=postgresql&logoColor=E6EDF3)
![Redis](https://img.shields.io/badge/Redis-161B22?style=for-the-badge&logo=redis&logoColor=E6EDF3)

<br/>

**DEVOPS & TOOLING**

![Docker](https://img.shields.io/badge/Docker-161B22?style=for-the-badge&logo=docker&logoColor=E6EDF3)
![Linux](https://img.shields.io/badge/Linux-161B22?style=for-the-badge&logo=linux&logoColor=E6EDF3)
![Git](https://img.shields.io/badge/Git-161B22?style=for-the-badge&logo=git&logoColor=E6EDF3)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-161B22?style=for-the-badge&logo=githubactions&logoColor=E6EDF3)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-161B22?style=for-the-badge&logo=opentelemetry&logoColor=E6EDF3)

</div>

<br/>

---

<!-- ─────────────────────────────────────────────────── -->
<!--  OTHER PROJECTS                                     -->
<!-- ─────────────────────────────────────────────────── -->

<br/>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=11&duration=99999&pause=99999&color=58A6FF&center=true&vCenter=true&width=200&height=20&lines=%2F%2F+OTHER+PROJECTS" alt="section" />
</div>

<br/>

<div align="center">

| Project | Description | Stack |
|:---:|:---|:---:|
| **[Split-Fast](https://github.com/aaditya8979/Split-Fast)** | Group expense management app with serverless APIs and real-time WebSocket sync. | ![TypeScript](https://img.shields.io/badge/TypeScript-161B22?style=flat-square&logo=typescript&logoColor=E6EDF3) ![Svelte](https://img.shields.io/badge/Svelte-161B22?style=flat-square&logo=svelte&logoColor=E6EDF3) |
| **[Syncy](https://github.com/aaditya8979/Syncy)** | Full-stack streaming app with optimised provider mapping for native Hindi audio support. | ![TypeScript](https://img.shields.io/badge/TypeScript-161B22?style=flat-square&logo=typescript&logoColor=E6EDF3) ![WebSockets](https://img.shields.io/badge/WebSockets-161B22?style=flat-square) |

</div>

<br/>

---

<!-- ─────────────────────────────────────────────────── -->
<!--  CERTIFICATIONS & AWARDS                            -->
<!-- ─────────────────────────────────────────────────── -->

<br/>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=11&duration=99999&pause=99999&color=58A6FF&center=true&vCenter=true&width=280&height=20&lines=%2F%2F+CERTIFICATIONS+%26+AWARDS" alt="section" />
</div>

<br/>

<div align="center">

🏆 **5th Place Overall** — ACWOC'26 · Open-source contribution program, 45+ contributions
&nbsp;|&nbsp;
**Software Architecture & System Design Foundations** — ScholarHat
&nbsp;|&nbsp;
**Alpha (DSA/Java) + Delta (Full Stack)** — Apna College

</div>

<br/>

---

<!-- ─────────────────────────────────────────────────── -->
<!--  SYSTEM TELEMETRY                                   -->
<!-- ─────────────────────────────────────────────────── -->

<br/>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=11&duration=99999&pause=99999&color=58A6FF&center=true&vCenter=true&width=220&height=20&lines=%2F%2F+SYSTEM+TELEMETRY" alt="section" />
</div>

<br/>

<div align="center">

| &nbsp; | &nbsp; |
|:---:|:---:|
| [![Stats](https://github-readme-stats.vercel.app/api?username=aaditya8979&show_icons=true&hide_border=true&bg_color=0D1117&title_color=E6EDF3&icon_color=58A6FF&text_color=8B949E&ring_color=58A6FF&count_private=true&include_all_commits=true)](https://github.com/aaditya8979) | [![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=aaditya8979&layout=compact&hide_border=true&bg_color=0D1117&title_color=E6EDF3&text_color=8B949E&langs_count=8)](https://github.com/aaditya8979) |

<br/>

[![Streak](https://streak-stats.demolab.com?user=aaditya8979&hide_border=true&background=0D1117&ring=58A6FF&fire=8B949E&currStreakLabel=E6EDF3&sideLabels=8B949E&dates=8B949E&currStreakNum=E6EDF3&sideNums=E6EDF3&stroke=161B22)](https://github.com/aaditya8979)

<br/>

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=aaditya8979&bg_color=0D1117&color=8B949E&line=58A6FF&point=E6EDF3&area=true&area_color=161B22&hide_border=true&custom_title=CONTRIBUTION+GRAPH)](https://github.com/aaditya8979)

</div>

<br/>

---

<!-- ─────────────────────────────────────────────────── -->
<!--  OPEN CHANNEL                                       -->
<!-- ─────────────────────────────────────────────────── -->

<br/>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=11&duration=99999&pause=99999&color=58A6FF&center=true&vCenter=true&width=200&height=20&lines=%2F%2F+OPEN+CHANNEL" alt="section" />
</div>

<br/>

<div align="center">

Working on local LLM infrastructure, agentic systems, or developer tooling?<br/>
Reach out — collaboration, critique, or cold outreach, all signals welcome.

<br/>

[![Email](https://img.shields.io/badge/aadityaagarwal947%40gmail.com-161B22?style=for-the-badge&logo=gmail&logoColor=8B949E)](mailto:aadityaagarwal947@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-161B22?style=for-the-badge&logo=linkedin&logoColor=8B949E)](https://www.linkedin.com/in/aaditya-agarwal-457922379)
&nbsp;
[![Portfolio](https://img.shields.io/badge/Read_my_essays-161B22?style=for-the-badge&logo=readme&logoColor=8B949E)](https://aadityaagarwal.vercel.app)

</div>

<br/>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:0D1117&height=80&section=footer&text=&animation=fadeIn)
