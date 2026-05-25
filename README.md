<h1 align="center">Hi, I'm Elle Li (이미령) 👋</h1>

<div align="center">
Full-stack & mobile developer who ships products end-to-end — Spring/Oracle backends, React/Vue web, Flutter apps — with a research background in AI/LLM evaluation.
</div>

<div align="center">
<sub>🇨🇳 中文 · 🇰🇷 한국어 · 🇬🇧 English</sub>
</div>

<hr>

## 👋 소개 (Korean)

안녕하세요, **풀스택·모바일 개발자 이메이링(Elle Li)** 입니다.

웹과 모바일 제품을 기획부터 배포까지 직접 구현합니다. KDT 부트캠프에서 **Java / Spring Boot / Oracle** 기반 팀 프로젝트를 완수했고, **React·Node** 풀스택 서비스와 **Flutter** 앱을 만들었습니다. 석사 연구에서는 Python·LLM API로 데이터 수집·분류·검증 파이프라인을 설계·구현했습니다.

복잡한 요구사항을 안정적인 시스템으로 옮기는 일과, 데이터·검증 로직을 꼼꼼하게 다루는 일을 좋아합니다. **중국어·한국어·영어** 3개 국어로 협업할 수 있습니다.

<hr>

## About Me (English)

<table>
<tr><td>

💻 I build **full-stack web and mobile products end-to-end** — from DB design and backend logic to UI. My team project shipped a real e-commerce platform on **Spring Boot / Oracle / Vue 3**; my solo project is a **React + Node** community service with real-time chat.

🔬 My master's research turns messy, real-world data into reliable pipelines: I designed and implemented a **Python + LLM-API** workflow to screen, classify, and validate 2,000+ posts, with human–LLM agreement verification.

📊 I care about **correctness and reliability** — settlement/commission logic, CRUD integrity, batch jobs with retry/checkpoint recovery, and statistical validation. Research methods training gives me a habit of testing assumptions before trusting output.

🌏 **Trilingual (Chinese · Korean · English)** with permanent residency in South Korea. Comfortable collaborating in Korean and English.

</td></tr>
</table>

<hr>

## 🛠 Tech & Skills

**Backend**
<div>
  <img src="https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/MyBatis-000000?logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?logo=express&logoColor=white" />
</div>

**Frontend**
<div>
  <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?logo=vuedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white" />
</div>

**Database & Infra**
<div>
  <img src="https://img.shields.io/badge/Oracle-F80000?logo=oracle&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" />
</div>

**Data & AI**
<div>
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Anthropic_API-191919?logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white" />
</div>

<br>

**Methods**: Real-time features (WebSocket / Socket.io) · Payment & auth API integration (PortOne, CoolSMS, Kakao) · Batch processing with retry & checkpointing · Inter-rater reliability (Cohen's κ, Gwet's AC1) · Classification framework design

<hr>

## 💻 Development Projects

### 🍰 디저트 연구소 (Dessert Lab) — Handmade dessert marketplace
A full e-commerce / brokerage platform connecting dessert sellers and buyers. **5-person team project (KDT).**
- **Stack**: Spring Boot · MyBatis · Oracle DB · JSP · Vue.js 3 · AJAX · WebSocket
- **My role** — Admin & Buyer pages, data & settlement logic:
  - Full **CRUD** for users and posts across admin/buyer dashboards
  - **Commission settlement logic** tied to the platform's revenue structure
  - Membership management; purchase history with per-order option retrieval
  - Payment-state-aware review system; **ApexCharts** sales/usage dashboards
- Integrated APIs across the project: Kakao Map, PortOne (payment), CoolSMS (SMS auth)
- [GitHub Repository](https://github.com/chchjjj/teamProject)

<br>

### 🌧️ Sweatin'SkyBlue — Relay jogging community platform
Full-stack **solo** project for mutual-support running groups.
- **Stack**: React · Node.js · Express · MySQL · Socket.io
- Designed relay jogging group logic with completion-rate-based participation rules
- Implemented **real-time chat and notifications** via Socket.io
- Built an anonymous feed and a 3-zone community structure
- [GitHub Repository](https://github.com/li33893/react-sns-project)

<br>

### 📱 Flutter Team Project — AI-assisted recipe & community app
Mobile app; contributed community, notification, and navigation features.
- **Stack**: Flutter · Dart · Firebase
- Built post detail, comment/reply interactions, bookmark flow, and notification-linked navigation
- Connected community interaction to real-time user feedback; integrated Firebase data handling
- [GitHub Repository](https://github.com/harford-stack/flutter_team_project)

<hr>

## 🔬 Research & Data Projects

### AI-Mediated Mental Health Content — Screening, Coding & Validation Pipeline
A reproducible **Python + LLM-API** workflow for classifying and validating Reddit data at scale.
- Built a **7-stage pipeline** to screen, classify, and validate 2,000+ posts
- Designed a multi-dimensional classification framework with iterative decision rules
- Established **human–LLM agreement verification** (Cohen's κ ≥ 0.80) using dual reliability metrics
- Implemented batch LLM coding with **exponential backoff, checkpoint recovery, and structured error handling**
- Key finding: AI disclaimers function as authorization mechanisms rather than warnings
- **Python · Anthropic API · Pandas · Statistical validation**
- [GitHub Repository](https://github.com/li33893/reddit-content-classificaiton-pipeline)

<br>

### Meta-Analysis Pipeline (R)
A fully reproducible meta-analysis codebase, organized for clarity and re-runnability.
- Modular, **numbered R scripts** (setup → data → analysis → outputs) for end-to-end reproducibility
- Automated effect-size computation, heterogeneity assessment, and publication-bias diagnostics
- Git-tracked model objects and table outputs for a clean, auditable workflow
- **R · meta / metafor · reproducible research**
- [GitHub Repository](https://github.com/li33893/meta-analysis)

<hr>

## 🎓 Education

**Hanyang University** — M.A. in Child Psychotherapy (Research Methods focus), Expected 2026
- Thesis: AI-mediated mental health support — classification framework design, LLM-assisted validation, and discourse analysis

**KDT Bootcamp (Java / Spring / Oracle)** — Full-stack development, 2026

**China University of Mining and Technology, Beijing** — B.A. in English Language and Literature, 2020

<hr>

## 📫 Contact

- **Email**: lmeiling322830@gmail.com
- **GitHub**: [github.com/li33893](https://github.com/li33893)
- **Location**: Incheon, South Korea
