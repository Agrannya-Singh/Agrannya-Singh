<div align="center">

# Agrannya Singh

**Building the infrastructure layer that makes everything else possible**

<p>
  <a href="https://www.linkedin.com/in/agrannya/">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/Agrannya-Singh">
    <img src="https://img.shields.io/badge/GitHub-100000?logo=github&logoColor=white" alt="GitHub">
  </a>
</p>

**Final Year CSE @ VIT Vellore** | Infrastructure Specialist | LLM Orchestration | Full-Stack Engineer

</div>

---

## What I Do

I build systems that operate at the intersection of **infrastructure, AI orchestration, and scale**. 

- **Backend Infrastructure** — JWT auth, cloud pipelines, containerized systems that actually run in production
- **Agentic AI Systems** — LLM orchestration doing real operational work (not demos), multi-model chaining, intelligent automation
- **Rapid Execution** — Full backends in under two weeks. Multiple internships shipping production systems on founding-team pace
- **Systems Thinking** — Auth layers, cloud architecture, DevOps pipelines. The critical infrastructure other people defer

**Philosophy:** Ship fast. Sleep after. The only opinion that matters is whether it works at scale.

## Current Work

### **Samsung Prism** — *R&D Intern (Ongoing)*

**Problem:** Most music retrieval systems assume static user intent. But intent shifts mid-session—what someone wants at track 3 differs at track 12. Retrieval systems have no way to model that drift.

**Solution:** Building an LLM-driven sequential music retrieval pipeline that:
- Tracks user intent state transitions in real time
- Adapts recommendations based on behavioral signals within the session
- Moves beyond static collaborative filtering to dynamic preference modeling

**Impact:** Real-time, contextually-aware music experiences that feel personalized to the moment.

---

## Experience & Impact

### **Novustrana** — *Full Stack Intern*

**Problem:** Manual employability assessment is slow, subjective, and doesn't leverage modern data. Need an intelligent system to score candidates across multiple dimensions.

**Solution:** Solo backend and cloud infrastructure for an agentic scoring system:
- Orchestrated Gemini 2.5-Flash and Grok 4 chaining for parallel evaluations
- Built OSINT intelligence engine using Google Search grounding to verify resume claims
- Implemented JWT auth, Express.js routes, Firestore security rules, Cloud Run deployment
- Firebase Cloud Functions as orchestration backbone

**Impact:** From manual spreadsheets to automated multi-model scoring. All infrastructure handled solo.

---

### **SambalPay Fintech Solutions** — *Software Engineering Intern*

**Problem:** Legacy core banking backend wasn't containerized—couldn't scale, difficult to deploy.

**Solution:** Containerized Apache Fineract backend infrastructure:
- Docker Compose orchestration for local development
- Deployed to GCP for production environments
- Contributed to Technical PM and Android interview process
- Conducted competitive analysis across 10+ NBFC loan partners

**Impact:** Fintech system ready for cloud-native operations at scale.

---

### **Mokshapay** — *Full Stack Engineer (Founding Team)*

**Problem:** Building a fintech platform from zero. Needed complete stack—frontend, infrastructure, backend, compliance, and AI support.

**Solution:** End-to-end platform built on founding-team pace (everyone owns everything):
- **Frontend:** Next.js 15 for speed and developer experience
- **Infrastructure:** Terraform-provisioned GCP with compliant VPC
- **Backend:** Dual-database architecture (PostgreSQL for loans, Firestore for profiles)
- **AI:** GenAI helpdesk powered by Vertex AI Agent Builder
- **Deployment:** Production-ready from day one

**Impact:** Shipped a complete fintech platform on startup velocity.

---

### **Labmentex** — *Python Intern*

**Problem:** NASA DONKI space weather datasets are massive and raw—hard to extract signal.

**Solution:** Custom EDA (Exploratory Data Analysis) engine:
- Python + Flask data pipeline for space weather datasets
- Feature selection via Pearson Correlation analysis
- Built tools to make complex climate data interpretable

**Impact:** Researchers can now quickly identify significant patterns in space weather data.

## Notable Projects

Projects that demanded everything—novel problems, cutting-edge techniques, and shipping something that actually works.

### **[TuneTrace](https://github.com/Agrannya-Singh)** — Hybrid Music Recommendation Engine

**Problem:** Recommending from 3,000+ songs requires both behavioral understanding (what you listened to) AND semantic meaning (contextual similarity). Single-approach systems fail.

**Solution:** Two-layer recommendation architecture:
- **Collaborative Filtering** for behavioral signal (people like you also listened to...)
- **Semantic Vector Search** for contextual meaning (songs with similar vibes)
- **Exponential Recency Decay** so 2021 listening history stops poisoning recommendations
- Both layers communicate to each other—the ensemble beats either alone

**Tech:** Vector embeddings, collaborative filtering, decay functions, real recommendation logic.

---

### **[ScreenScout](https://github.com/Agrannya-Singh)** — Semantic Movie Search

**Problem:** Finding movies across 30,000+ records using keyword search fails. Users think in vibes/themes, not exact titles. But vector search alone has latency/cost issues.

**Solution:** Hybrid retrieval system:
- **High-dimensional embeddings** for semantic understanding
- **Pinecone vector DB** for fast approximate nearest neighbor (ANN) lookup
- **SQLite local deterministic lookups** for fallback and verification
- **Boundary analysis:** Figured out where one approach breaks down and the other picks up—that's where all the real design lives

**Tech:** High-dimensional embeddings, approximate nearest neighbor search, hybrid retrieval.

---

### **[Othello Dojo](https://github.com/Agrannya-Singh)** — Autonomous Reversi Agent

**Problem:** Build an autonomous game-playing agent for Reversi (Othello). Underestimated game, incredible complexity at scale.

**Solution:** AlphaZero-style approach for a board game:
- **Classical Minimax** for game tree search
- **ResNet-based Policy Network** for intelligent move evaluation
- **Custom MCTS Pipeline** synthesizing 10,000+ training states
- **Team:** Led a 5-person team to execution

**Impact:** Autonomous agent that plays at near-optimal level, demonstrating MCTS + neural synthesis at scale.

---

### **[Space Weather Intelligence Dashboard](https://github.com/Agrannya-Singh)** — Real-Time NASA Analytics

**Problem:** Raw datasets tell nothing. 50,000+ NASA space weather records exist, but humans can't read them fast.

**Solution:** Full-stack dashboard with AI-powered interpretation:
- **Real-time visualization** of 50,000+ records
- **Genkit + Gemini AI** that generates EDA-aware summaries (actually explaining what the data is doing, not just summarizing)
- **Interactive exploration** so users can drill into signals themselves

**Impact:** Researchers can now understand complex space weather patterns in minutes instead of days.

## Technical Arsenal

### Languages
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![R](https://img.shields.io/badge/R-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

### Backend & LLM Orchestration
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express-404d59.svg?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Flask](https://img.shields.io/badge/Flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Django REST](https://img.shields.io/badge/Django_REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709)

### Frontend & UI
![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)

### Authentication & Security
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

### AI & ML
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

### Cloud & DevOps Infrastructure
![Google Cloud](https://img.shields.io/badge/Google_Cloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

### Databases & Persistence
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-%23039BE5.svg?style=for-the-badge&logo=firebase&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

### Deployment & Platform
![Vercel](https://img.shields.io/badge/Vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)

## Recognitions

**Certifications**

Generative AI using IBM WatsonX | Machine Learning for Data Science Projects | Atlas Vector Search for RAG Applications | Cloud Computing Fundamentals | Cybersecurity Fundamentals | DevOps and Site Reliability Engineering

---

## GitHub Analytics

<div align="center">

![](https://github-readme-stats.vercel.app/api?username=Agrannya-Singh&theme=github_dark&hide_border=false&include_all_commits=true&count_private=false)

![](https://nirzak-streak-stats.vercel.app/?user=Agrannya-Singh&theme=github_dark&hide_border=false)

![](https://github-profile-trophy.vercel.app/?username=Agrannya-Singh&theme=radical&no-frame=false&no-bg=true&margin-w=4)

![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

![](https://github-contributor-stats.vercel.app/api?username=Agrannya-Singh&limit=5&theme=dark&combine_all_yearly_contributions=true)

![My GitHub Game](game.gif)

</div>
