<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=30&duration=3000&pause=1200&color=4CBB17&center=true&vCenter=true&width=900&lines=Building+ISTINA;Conflict+Intelligence+Engine;Truth+Through+Data;Computer+Science+%40+University+of+Toronto" />
</p>

---

# Fahad S. Khan

**Computer Science & Finance @ UofT | Building ISTINA 👁**

I am a Computer Science student at the University of Toronto with hands-on experience building production-grade software systems across startups, enterprise environments, and public-sector operations. My interests sit at the intersection of backend engineering, AI-driven systems, and security-focused software design.

I have worked as a Software Developer and Software Engineer in startup and business environments, where I built scalable backend services in Go and Python, implemented secure authentication workflows, integrated relational databases, and improved operational efficiency through automation. I enjoy working close to real systems where reliability, performance, and correctness matter.

Beyond formal roles, I am the founder of Istina, a news bias analysis platform focused on applying APIs, natural language processing, and data visualization to improve clarity in global conflict reporting. This project reflects my entrepreneurial mindset and my interest in building technology that helps people make better-informed decisions.

I am currently seeking opportunities where I can continue developing as a software engineer, contribute meaningfully to real-world systems, and grow alongside teams that value strong technical fundamentals, ownership, and impact.

<p align="left">
  <a href="https://www.linkedin.com/in/fahad-sadiq-khan" target="_blank">
    <img alt="LinkedIn" title="Follow my LinkedIn!" 
         src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:khan.fsadiq05@gmail.com" title="Business email">
    <img alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="mailto:fsadiq.khan@mail.utoronto.ca" title="University email">
    <img alt="Outlook" src="https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white"/>
  </a>
</p>

---

# 🐱‍👤 Languages & Tools

<p align="left">
  <img alt="Python" height="40px"
       src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/>
  <img alt="C#" height="40px"
       src="https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white"/>
  <img alt="Go" height="40px"
       src="https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white"/>
  <img alt="Java" height="40px"
       src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white"/>
</p>

---

# 👁 ISTINA — Conflict Intelligence Engine (WAITLIST FOR v1 LAUNCHING SOON!)

*A conflict-tracking and bias-aware news analysis system.*

**Istina** is a CLI-first platform designed to analyze global news narratives and surface **measurable bias across sources**.  
It ingests articles from live RSS feeds, evaluates them using external AI models, and identifies **conflicting claims, rhetorical bias, and narrative framing** within coverage of the same event.

The project serves as the **core prototype for a larger system** that will eventually expand into a full **web and mobile platform for narrative transparency**.

🔗 **Repository:**  
https://github.com/mufferio/istina

---

## 🚀 Core Capabilities

**Article Ingestion**

- Collects articles directly from live RSS feeds  
- Normalizes articles into structured internal models  
- Stores metadata including title, source, publication time, and summaries  

**AI-Powered Bias Detection**

- Integrates external AI providers (currently Google Gemini)  
- Detects rhetorical bias and narrative framing  
- Produces structured bias reports with confidence scores  

**Conflict Tracking**

- Compares narratives across multiple sources  
- Identifies contradictions and competing claims  
- Surfaces supporting evidence and references  

**Bias Reporting**

- Generates CLI summaries of narrative bias  
- Supports detailed per-article reports with claim verification results  

---

## 🧠 System Architecture

Istina is built with **clean architecture and extensibility in mind**.

Key design patterns:

**Model-View-Controller (MVC)**  
Separates domain models, command interfaces, and presentation logic.

**Command Pattern**  
Implements CLI commands such as `ingest`, `analyze`, and `summarize`.

**Factory Pattern**  
Abstracts AI providers so new services can be integrated easily.

**Visitor Pattern**  
Traverses article collections to apply scoring and reporting logic.

**Repository Pattern**  
Supports pluggable persistence layers:

- In-memory repositories  
- JSONL file persistence  
- Future database implementations  

---

# 📈 Activity Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=mufferio&theme=tokyo-night"/>
</p>
