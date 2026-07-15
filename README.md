<div align="center">

<!-- ══════════════════════════ HERO: LIVE BIAS-SCANNER ══════════════════════════ -->
<img src="assets/hero-scanner.svg" width="100%" alt="Fahad S. Khan — animated bias-scanner banner"/>

<br/><br/>

<a href="https://readme-typing-svg.demolab.com">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=900&color=00C566&center=true&vCenter=true&width=720&lines=Head+of+Development+%40+Hadio+Friperie+Vintage;Founder+%26+CEO+%40+ISTINA+AI;CS+%26+Finance+%40+University+of+Toronto;Backend+%C2%B7+AI+pipelines+%C2%B7+Systems+%C2%B7+Firmware" alt="Typing SVG" />
</a>

<br/><br/>

<a href="https://www.linkedin.com/in/fahad-sadiq-khan"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
&nbsp;
<a href="mailto:khan.fsadiq05@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
&nbsp;
<a href="https://tryistina.net"><img src="https://img.shields.io/badge/ISTINA-00C566?style=for-the-badge&logo=eye&logoColor=white" alt="ISTINA"/></a>

</div>

<br/>

<table>
<tr>
<td width="62%" valign="top">

### 🧭 About

I build production-grade systems across the stack — REST APIs, AI/NLP pipelines, computer-vision tooling, and a PID control loop running on bare-metal firmware.

By day I run the **development department at Hadio Friperie Vintage**, shipping everything from internal dashboards to a YOLO/DINOv2 patch-detection pipeline. By night I'm building **ISTINA**, an AI platform that measures bias and framing in news coverage — sentence by sentence.

> 🟢 **Open to collaboration & interesting problems.**

</td>
<td width="38%" valign="top">

### ⚡ At a glance

```text
💼  Head of Dev @ Hadio
👁️  Founder @ ISTINA AI
🎓  CS & Finance @ UofT
🛠️  Go · Python · C · TS
🤖  AI / NLP / CV pipelines
🔌  ESP32 firmware (r/arduino)
📍  Montréal, QC
```

</td>
</tr>
</table>

<br/>

<div align="center">

### 🧰 Arsenal

<img src="https://skillicons.dev/icons?i=python,go,c,cpp,java,cs,ts,js,react,vite,tailwind,html,css,fastapi,postgres,supabase,docker,vercel,git,postman,linux,unity,unreal,blender&perline=12" alt="Tech stack"/>

<br/>

![Gin](https://img.shields.io/badge/Gin-008ECF?style=flat-square&logo=gin&logoColor=white)
![RISC-V ASM](https://img.shields.io/badge/RISC--V_ASM-283272?style=flat-square&logo=riscv&logoColor=white)
![JWT](https://img.shields.io/badge/JWT_Auth-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Fly.io](https://img.shields.io/badge/Fly.io-8B5CF6?style=flat-square&logo=flydotio&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![LLM Orchestration](https://img.shields.io/badge/LLM_Orchestration-FF6F61?style=flat-square&logo=openai&logoColor=white)
![Tavily](https://img.shields.io/badge/Tavily_Search-6C5CE7?style=flat-square&logo=duckduckgo&logoColor=white)

</div>

<br/>

## <img src="https://img.shields.io/badge/👁-ISTINA-00C566?style=flat-square" height="22"/> &nbsp;Featured — *Signal in the noise.*

> An AI platform that ingests RSS feeds and analyzes **geopolitical news at the sentence level** — surfacing rhetorical bias, narrative framing, and conflicting claims across coverage of the same event, then turning that analysis into shareable content.

🔗 **[tryistina.net](https://tryistina.net)** &nbsp;·&nbsp; 🔒 *Source private (security)* &nbsp;·&nbsp; 🎯 *B2B: journalism schools, fact-checkers, newsrooms*

| Layer | Stack |
|---|---|
| 🖥️ &nbsp;Backend | `FastAPI` · `Python` · `JWT auth` · Dockerized |
| 🎨 &nbsp;Frontend | `React` · `TypeScript` · `Vite` · `TailwindCSS` |
| 🗄️ &nbsp;Data & Auth | `Supabase` · `PostgreSQL` |
| ▲ &nbsp;Deploy | Backend on `Fly.io` · frontend on `Vercel` |
| 🤖 &nbsp;Engine | LLM-driven sentence-level bias scoring · framing detection · multi-stage claim verification |
| 🔁 &nbsp;Pipeline | `n8n`: RSS → scorer → analyzer → claim verifier → generator, with `Tavily` live search |

<details>
<summary><b>🦀 The origin story → ISTINA v1 (Rust CLI)</b></summary>

<br/>

The prototype the platform grew out of: a **Rust** command-line engine that ingests live RSS feeds, normalizes articles into structured models, and runs AI-powered bias detection to compare narratives across sources.

| | |
|---|---|
| **Language** | Rust |
| **Design** | Clean architecture — MVC + Command, Factory, Visitor, Repository patterns |
| **Persistence** | Pluggable: in-memory · JSONL · database-ready |
| **Does** | RSS ingestion · narrative conflict tracking · bias reports with confidence scores |

*Source private; shown here as the foundation of the current platform.*

</details>

<br/>

## 📂 Public Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🔧 [concave-tech](https://github.com/mufferio/concave-tech)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)

Layered REST API serving user data from PostgreSQL via Gin. Clean controller / service / repository / DTO separation, Docker Compose for local Postgres + pgAdmin.

</td>
<td width="50%" valign="top">

#### 👾 [SOTD Engine](https://github.com/mufferio/SOTD-riscv-assembly-engine)
![Assembly](https://img.shields.io/badge/-RISC--V_ASM-283272?style=flat-square&logo=riscv&logoColor=white)

Survival-horror game written **entirely in RISC-V assembly**. Infinite undo (512-snapshot ring buffer), Chebyshev-distance monster AI, and a multiplayer leaderboard.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🗜️ [file-compression-engine](https://github.com/mufferio/file-compression-engine)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

Quadtree-based lossy image compressor. Recursively partitions images by regional variance into a custom `.qdt` format — ~5× size reduction at moderate loss.

</td>
<td width="50%" valign="top">

#### ✈️ [frequent-flyer-data-parser](https://github.com/mufferio/frequent-flyer-data-parser)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

Airline sim ingesting tens of thousands of CSV rows into a typed domain model with frequent-flyer tier logic, plus an interactive map with real-time filtering.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### ♟️ [othello-java-engine](https://github.com/mufferio/othello-java-engine)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

Full Othello/Reversi engine with 8-direction move validation, random + greedy AI strategies, and automated simulation modes. JUnit-tested, Maven-built.

</td>
<td width="50%" valign="top">

#### 🎨 [paint3d-mario-edition](https://github.com/mufferio/paint3d-mario-edition)
![Java](https://img.shields.io/badge/-JavaFX-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

Themed JavaFX paint app showcasing MVC + Observer, Strategy-per-tool routing, and a shape Factory. 7 tools, undo/redo, clipboard ops, PNG import/export.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📝 [paint3d-visitor-fsm-parser](https://github.com/mufferio/paint3d-visitor-fsm-parser)
![Java](https://img.shields.io/badge/-JavaFX-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

Companion project focused on persistence: a custom save-file format with an FSM-style, regex-driven parser, backed by a JUnit suite defining the parser contract.

</td>
<td width="50%" valign="top">

#### ☕ [esp32-espresso-mod](https://github.com/mufferio/esp32-espresso-mod)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**"Frank"** — a PID temperature-controller mod holding ±0.5 °C at target. ESP32 + thermocouple + SSR, self-hosted web UI at `frank.local`. *Featured on r/arduino.*

</td>
</tr>
</table>

<br/>

## 💼 Experience

**Head of Development · Software Developer (Full-time)** · *Hadio Friperie Vintage* &nbsp;|&nbsp; `Present`
Lead the development department for a vintage retail business — internal admin dashboards (React/Fastify/Supabase), an employee portal, a YOLO/DINOv2 computer-vision patch-detection pipeline, and automation across operations.

**Software Developer** · *Concave Tech* &nbsp;|&nbsp; `05/2025 – 08/2025`
Built a production-grade user-service backend in **Go** with RESTful APIs for secure user-data ingestion and validation. Implemented hashing + salting for credential storage, integrated **PostgreSQL** with indexed schemas for scalable concurrent queries, and containerized with **Docker** — cutting auth-related failures by **~40%**.

**Software Engineer** · *Elections Ontario* &nbsp;|&nbsp; `01/2025 – 02/2025`
Led on-site technical operations during the Ontario Provincial Election, keeping voting infrastructure fully operational under strict time pressure. Verified large volumes of voter records and resolved **95%+ of technical issues on first response**, preventing downtime in a compliance-driven environment.

**Software Engineer** · *Hawks Management & Solutions* &nbsp;|&nbsp; `06/2023 – 08/2023`
Built a **Python**-based task delegation and tracking system with a cross-functional team. Automated assignment logic and real-time progress tracking that boosted weekly task throughput **10×**, refined through iterative testing and structured user feedback.

<br/>

<div align="center">

## 📊 GitHub

<img height="165" src="https://github-readme-stats.vercel.app/api?username=mufferio&show_icons=true&hide_border=true&title_color=00C566&icon_color=00C566&text_color=ffffff&bg_color=0d1117&rank_icon=github" alt="stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mufferio&layout=compact&hide_border=true&title_color=00C566&text_color=ffffff&bg_color=0d1117" alt="top langs"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=mufferio&hide_border=true&background=0d1117&ring=00C566&fire=00C566&currStreakLabel=00C566&sideLabels=8b949e&currStreakNum=ffffff&sideNums=ffffff&dates=8b949e" alt="streak"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=mufferio&bg_color=0d1117&color=8b949e&line=00C566&point=ffffff&area=true&area_color=00C566&hide_border=true&custom_title=Contribution%20Signal" width="95%" alt="activity graph"/>

<br/><br/>

<!-- ══════════════════════════ SNAKE ══════════════════════════ -->
<img src="https://raw.githubusercontent.com/mufferio/mufferio/output/github-snake-dark.svg" width="95%" alt="contribution snake"/>

<br/><br/>

🎓 **Honors BSc & BCom, Computer Science and Finance @ University of Toronto** &nbsp;·&nbsp; 2024–present

<sub><code>$ exit 0</code> — thanks for scrolling.</sub>

</div>
