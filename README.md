<h1 align="center">Hi, I'm Meiling Li (이미령) 👋</h1>

<div align="center">
Full-stack & mobile developer who ships products end-to-end — Spring/Oracle backends, React/Vue web, Flutter apps — with a research background in AI/LLM evaluation.
</div>

<div align="center">
<sub>🇨🇳 中文 · 🇰🇷 한국어 · 🇬🇧 English</sub>
</div>

<hr>

## 👋 소개 (Korean)

안녕하세요, **이미령 (Meiling Li)** 입니다.

복잡한 요구사항을 안정적인 시스템으로 옮기는 일과, 데이터·검증 로직을 꼼꼼하게 다루는 일을 좋아합니다. **중국어·한국어·영어** 3개 국어로 협업할 수 있습니다.

<hr>

## About Me (English)

<table>
<tr><td>

💻 I build **full-stack web and mobile products end-to-end** — from DB schema design and backend logic to UI. My team project shipped an e-commerce / brokerage platform on **Spring Boot / Oracle / Vue 3**; my solo project is a **React + Node** community service with real-time chat built on a self-designed multi-table MySQL schema.

🔬 My master's research turns messy real-world data into reliable pipelines: I designed and implemented a **Python + Anthropic API** workflow to screen, classify, and validate 2,000+ Reddit posts, with human–LLM agreement verification.

📊 I care about **correctness and reliability** — settlement/commission logic, CRUD integrity, batch jobs with retry/checkpoint recovery, and fail-fast data validation. Research-methods training gives me the habit of testing assumptions before trusting output.

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
  <img src="https://img.shields.io/badge/Google_Gemini-4285F4?logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?logo=mysql&logoColor=white" />
</div>

<br>

**Methods**: Real-time features (WebSocket / Socket.io) · Payment & auth API integration (PortOne, CoolSMS, Kakao, JWT, bcrypt) · Batch LLM processing with retry & checkpointing · Inter-rater reliability (Cohen's κ, Gwet's AC1) · Content classification framework design

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
- Project-wide API integration: Kakao Map, PortOne (payment), CoolSMS (SMS auth)
- [GitHub Repository](https://github.com/chchjjj/teamProject)

<br>

### 🌧️ Sweatin'SkyBlue — Relay-jogging mutual-support platform
**Solo full-stack** project (8 days) helping people build exercise habits to ease depressive symptoms.
- **Stack**: React 18 · Material-UI · Socket.io · Node.js · Express · MySQL · JWT · bcrypt
- **Relay jogging system**: previous runner finishes → next starts; completion-rate gating (90%+ to qualify as leader) with a leader-skip fallback so a late/incomplete runner doesn't block the team
- **3-zone community feed** (exercise / daily life / anonymous venting): likes, comments, bookmarks, region & zone filters, search
- Real-time chat and notifications via **Socket.io**; follow/follower system; JWT + bcrypt auth; Daum Postcode API
- Designed a **~19-table MySQL schema**, refactoring the data model around relay scenarios after the initial flat structure proved insufficient
- [GitHub Repository](https://github.com/li33893/react-sns-project)

<br>

### 🍳 ShakeCook — AI recipe recommendation app
Shake your phone to get AI-generated recipes from the ingredients you have. **4-person Flutter team project.**
- **Stack**: Flutter · Dart · Firebase (Auth / Firestore / Storage) · Google Gemini API
- **My role** — Community & Notification features:
  - Post creation with image upload (Firebase Storage), comments & replies, bookmarks
  - Category filtering, title/content search, latest/popular sorting
  - Notification list with real-time updates
- [GitHub Repository](https://github.com/harford-stack/flutter_team_project)

<hr>

## 🔬 Research & Data Projects

### AI-Mediated Mental Health Content — Screening, Coding & Validation Pipeline
A Python research workflow for classifying AI-in-mental-health Reddit posts at scale.
- Multi-stage pipeline: collection (ArcticShift) → **LLM relevance screening** → human–LLM agreement → cleaning & stratified sampling → multi-dimensional coding → validation → batch coding → descriptive stats → held-out validation
- **Human–LLM agreement** with dual metrics (Cohen's κ + Gwet's AC1, handling the prevalence paradox): screening κ ≈ 0.86; coding dimensions κ ≈ 0.68–0.81
- Batch coding with **exponential backoff, checkpoint recovery, and cost estimation**; `temperature = 0` for reproducibility; Wilson-score CIs for proportions
- Key finding: AI disclaimers function as authorization mechanisms rather than warnings
- **Python · Anthropic API (Claude) · Pandas**
- [GitHub Repository](https://github.com/li33893/reddit-content-classificaiton-pipeline)

<br>

### Meta-Analysis: Unguided Self-Help CBT for Adolescent Depression (R)
A systematic review & meta-analysis (master's thesis) built as a fully reproducible R codebase.
- **Numbered script workflow** (00–10 + PRISMA): setup → data import → effect sizes → main/follow-up models → risk of bias → subgroup → meta-regression → sensitivity → publication bias → acceptability
- Random-effects models (Hedges' *g*, REML + Hartung–Knapp) across 14 RCTs; PRISMA 2020 flow; Cochrane RoB 2.0 (`robvis`)
- Publication-bias diagnostics: contour-enhanced funnel, Egger's test, Pustejovsky–Rodgers SMD-corrected test, trim-and-fill
- **Defensive data handling**: fail-fast join assertions (`stopifnot`) to catch silent empty-join bugs; Git-tracked model objects (`.rds`) and CSV outputs for an auditable pipeline
- **R · metafor · meta · robvis · tidyverse**
- [GitHub Repository](https://github.com/li33893/meta-analysis)

<hr>

## 🎓 Education

**Hanyang University** — M.A. in Child Psychotherapy (Research Methods focus), Expected 2027
- Thesis: meta-analysis of unguided self-help CBT for adolescent depression; plus a discourse-analysis study of AI use in online mental health communities

**Deojoeun Computer Academy (더조은컴퓨터아카데미), Incheon** — Full-stack Web/App Development Bootcamp, 2025.07–2026.01
- MSA-based curriculum: Java full-stack (frontend & backend) + Flutter (Dart) for mobile/web app development

**China University of Mining and Technology, Beijing** — B.A. in English Language and Literature, 2020

<hr>

## 📫 Contact

- **Email**: lmeiling322830@gmail.com
- **GitHub**: [github.com/li33893](https://github.com/li33893)
- **Location**: Incheon, South Korea
