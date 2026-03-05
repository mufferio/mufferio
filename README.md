<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=30&duration=3000&pause=1200&color=4CBB17&center=true&vCenter=true&width=900&lines=Building+ISTINA;Conflict+Intelligence+Engine;Truth+Through+Data;Computer+Science+%40+University+of+Toronto" />
</p>

---

# Fahad S. Khan

**Computer Science & Finance @ UofT | Building ISTINA 👁**

Passionate builder and leader in software development, AI engineering, and cybersecurity, driven to turn ideas into tools that make a real difference. From developing **Istina**, a platform designed to bring clarity to global conflicts, to leading innovative tech projects that empower teams to excel, I thrive at the intersection of **technology, analysis, and impact**.

With a strong technical foundation and an entrepreneurial mindset, I’m committed to building systems that help people navigate complex information landscapes.

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

# 👁 ISTINA — Conflict Intelligence Engine

*A conflict-tracking and bias-aware news analysis system.*

**Istina** is a CLI-first platform designed to analyze global news narratives and surface **measurable bias across sources**.  
It ingests articles from live RSS feeds, evaluates them using external AI models, and identifies **conflicting claims, rhetorical bias, and narrative framing** within coverage of the same event.

The project serves as the **core prototype for a larger system** that will eventually expand into a full **web and mobile platform for narrative transparency**.

🔗 **Repository:**  
https://github.com/mufferio/istina

<p align="center">
  <a href="https://github.com/mufferio/istina_v0">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=mufferio&repo=istina_v0&theme=tokyonight"/>
  </a>
</p>

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
