<h1 align="center">Pranav Upadhyay</h1>

<p align="center">
  <b>B.Tech CSE @ Manipal University Jaipur</b> &nbsp;·&nbsp; Kanpur, India
</p>

<p align="center">
  I build ML systems and then try to break them.<br>
  Three projects where auditing my own work changed the headline number.
</p>

<p align="center">
  <a href="https://linkedin.com/in/pranavupadhyay1201"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:pranavupadhyay402@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://doi.org/10.5281/zenodo.21970156"><img src="https://img.shields.io/badge/DOI-10.5281%2Fzenodo.21970156-1682D4?logo=doi&amp;logoColor=white" alt="DOI"></a>
  <a href="https://visitcount.itsvg.in"><img src="https://komarev.com/ghpvc/?username=Pranav-1201&color=blueviolet&style=flat" alt="Profile views"></a>
</p>

---

## 💫 About Me

🔭 &nbsp;I'm currently working on **three research papers** — an SSL meta-analysis across NLP and CV, a cost-sensitive churn framework, and a surrogate-assisted GA for feature selection

👯 &nbsp;I'm looking to collaborate on **ML/AI research** and **AI-integrated full-stack systems**

🤝 &nbsp;I'm looking for help with getting the SSL meta-analysis and the GA feature-selection paper to **publication standard**

🌱 &nbsp;I'm currently learning **Reinforcement Learning**, **Recommender Systems**, and surrogate-assisted evolutionary algorithms

💬 &nbsp;Ask me about **cost-sensitive ML**, **model calibration**, **explainability**, or **React + FastAPI + Supabase** stacks

⚡ &nbsp;Fun fact: I ran my university's cybersecurity club as **Managing Director** — 100+ events over three years, including a statewide hackathon with IIIT Bhubaneswar (~600 participants)

---

## 🚀 Featured Work

| Project | What it does | Headline result |
|---|---|---|
| **[AI Code Review Agent](https://github.com/Pranav-1201/AI-Code-Review-Agent)** <br> `Python` `FastAPI` `React` `FAISS` | AST engine over Python/JS — cyclomatic complexity, call-graph, dead code, taint rules — with deterministic findings gating an optional LLM explanation layer | Every finding is deterministic; the LLM only paraphrases. Each explanation labeled `llm` or `deterministic` |
| **[ChurnLens](https://github.com/Pranav-1201/churnlens-dashboard)** <br> `Python` `CatBoost` `XGBoost` `SHAP` | Cost-sensitive churn pipeline — 7 calibrated models, deployed model chosen by out-of-fold **business cost**, not accuracy | **59% held-out cost cut** (₹10.3L → ₹4.2L), n = 7,043. Found test-set leakage in my own pipeline and retracted a better-looking ₹3.8L for the honest ₹4.2L |
| **[EHCV](https://github.com/Pranav-1201/Explanable-Hybrid-Computer-Vision-System-for-Robust-Scene-Understanding)** <br> `PyTorch` `ResNet-50` `OpenCV` `Flask` | Explainable indoor scene classification — Places365 fine-tune with Grad-CAM, temperature calibration, and a calibrated out-of-scope reject | **83.9% top-1** on MIT Indoor-67 (n = 1,340); ECE **33.4% → 5.6%**. CNN+HOG fusion lost on test (−1.2 pts) and is kept as a documented negative result |
| **[AcePlan](https://github.com/Pranav-1201/Aceplan)** <br> `React 18` `TypeScript` `Supabase` `Deno` | Serverless study platform — subject management, session tracking, AI note synthesis, vision-based timetable parsing | **14 Postgres tables** behind **19 row-level-security policies**, 7 Deno edge functions, Groq / Llama-3.3 |

> **TriageRL** — an RL agent that learns which security alert an analyst should investigate next, trained first on a hand-written reward then re-trained on a reward model learned from human preferences (RLHF). Coursework project with [@diya-garg18](https://github.com/diya-garg18); the repository lives on her account.

---

## 💼 Experience

**Software Engineer Intern — BPCL R&D Centre** · *Jun 2026 – Present*
Sole developer of a full-stack console (React/TS + FastAPI) replacing a single-user Excel + MATLAB HiGee rotating-packed-bed deaerator design workflow. Deterministic Python engine — 9 modular blocks, Pydantic-typed contracts, YAML-versioned constants — behind 6 REST endpoints. Verified by **281 backend + 34 frontend tests** and a **119-case / 7,507-check harness with zero divergence** against the original MATLAB/Excel.

**Software Development Intern — Li & Fung India** · *Jun 2026 – Jul 2026*
Shipped **6 of 8 automation tools to production** (FastAPI + React 19/TS) for a merchandising desk — PO parsing, tech-pack extraction, costing comparison, milestone tracking — behind **499 tests**. The flagship PO-bifurcation tool cut a measured 2-hour task to seconds, reconciled cell-by-cell to **79,049 pieces exactly**.

---

## 📄 Research

**Self-Supervised Learning in NLP vs. Computer Vision — A Quantitative Meta-Analysis**
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.21970156-1682D4?logo=doi&logoColor=white)](https://doi.org/10.5281/zenodo.21970156)
Cross-domain meta-analysis over **108 papers / 112 method–benchmark rows**, covering benchmark performance, evaluation-protocol sensitivity, and NLP↔CV convergence. Every statistic in the 16-page manuscript is regenerated by a single script — **40/40 data assertions pass**, and no number enters the paper by hand. Data and code archived on Zenodo (CC-BY-4.0 / MIT).

**Adaptive Surrogate-Assisted Multi-View GA for Feature Selection (ASMV-GA)** — *in preparation*
Survey and method work on genetic algorithms for feature selection in image recognition.

**Cost-Sensitive Ensemble ML for Telecom Churn Prediction** — *in preparation*
The framework behind ChurnLens, written up for publication.

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)

**ML / AI**

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)

**Web & Backend**

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)

**Databases**

![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.shion.dev/api?username=Pranav-1201&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&hide=stars,issues,prs&show_icons=true" alt="GitHub Stats">
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Pranav-1201&theme=tokyonight&hide_border=true" alt="Contribution Streak">
</p>

<p align="center">
  <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=Pranav-1201&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&layout=compact&langs_count=8" alt="Top Languages">
</p>

<!-- Built on GPRM ( https://gprm.itsvg.in ), then extended by hand -->
