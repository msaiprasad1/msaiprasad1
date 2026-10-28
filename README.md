# 👋 Hey, I'm Sai Prasad Muppala

**Founder & Technical Architect | Founding AI Engineer | Multi-Agent Architect | GenAI & Inference Engineer | AI Product Builder**

I take **AI-native products from 0 → 1 and into production**: product scope, system architecture, models, AI agents, RAG, backend, frontend, mobile, cloud deployment and the users who rely on it.

I have founded, co-founded or architected **six AI products**: an AI staffing engine, a career intelligence platform, an AI dubbing studio, an AI grading platform, a nutrition app live on both app stores, and a medical figure generator. Before that I built data and AI systems for the **State of Florida Department of Health, the U.S. Army Corps of Engineers, the South Florida Water Management District and Deloitte**.

📍 Boca Raton, FL · 📧 saiprasadmuppala2602@gmail.com · 🔗 [LinkedIn](https://www.linkedin.com/in/sai-prasad-muppala/)

---

## 🌐 Live Products

| Product | What it does | Role | Link |
|---|---|---|---|
| **Ace HR AI Staffing** | API-first recruiting and onboarding engine for staffing agencies | Founding AI Architect | 🔨 Building now |
| **Knuckler AI** | Tailored, ATS-ready resumes and submissions for staffing teams | Founder / Founding AI Engineer | [knuckler.app](https://knuckler.app/) |
| **ClonA AI** | AI dubbing studio: voice cloning across 30+ languages | Founding AI Engineer | [dev.clona.io](https://dev.clona.io/) |
| **GradeUS AI** | Rubric-based AI grading for handwritten and typed coursework | Co-Founder / Technical Architect | [gradeus.ai](https://gradeus.ai/home) |
| **Olvi** | AI nutrition, exercise and lifestyle app | Technical Architect (via Bluetomic LLC) | [olvi.io](https://olvi.io/) · [App Store](https://apps.apple.com/us/app/olvi/id6793376875) · [Google Play](https://play.google.com/store/apps/details?id=io.olvi.app) |
| **MediFigure** | Prompt-to-figure scientific and medical illustrations | Founder / Technical Architect | [Live on Cloud Run](https://medifigure-web-7g63t6e75a-uc.a.run.app/) |

---

## 🚀 What I Build

- **LLM applications** with RAG, context engineering, embeddings, semantic search and tool-calling agents
- **Multi-agent systems** with graph-based workflows (LangGraph), CrewAI, agent loops and MCP servers
- **Model training and inference**: fine-tuning open-weight models (LoRA/QLoRA) on Hugging Face and serving them with vLLM on NVIDIA GPUs
- **Full-stack AI SaaS** with Next.js, React, FastAPI, PostgreSQL/Neon/Supabase and Vercel AI SDK
- **Mobile AI apps** with React Native and Expo, shipped to the App Store and Google Play
- **Cloud-native data pipelines** with PySpark, Airflow, Kafka, BigQuery, Dataflow and Cloud Composer
- **Evaluations and reliability**: type-safe structured outputs, eval harnesses, feedback loops and observability

---

## 🧠 Core Expertise

| Area | Tools & Technologies |
|---|---|
| **Languages** | Python, SQL, TypeScript, JavaScript, R, C |
| **AI Coding & Agent Engineering** | Claude Code, Codex, Agent Loops, Graph Engineering, Context Engineering, Type-Safe Structured Outputs, Evals |
| **GenAI / LLMs** | Claude, OpenAI GPT, Gemini, DeepSeek, LLaMA, Mistral, Qwen |
| **Agentic AI** | LangGraph, LangChain, CrewAI, Autogen, MCP Servers, Tool/Function Calling |
| **Training & Inference** | Hugging Face, LoRA/QLoRA, PyTorch, vLLM, NVIDIA CUDA, A100/H100 GPUs |
| **RAG / Vector Search** | Pinecone, FAISS, ChromaDB, Weaviate, pgvector, Embeddings, Hybrid Search |
| **Multimodal** | Voice Cloning, TTS, Lip-Sync (LatentSync), OCR, Vision Models, Image Generation |
| **ML / DL** | scikit-learn, TensorFlow, PyTorch, XGBoost, MLflow, Feature Engineering |
| **Frontend & Mobile** | Next.js, React, Tailwind CSS, Vercel AI SDK, React Native, Expo, Streamlit |
| **Backend** | FastAPI, REST APIs, Webhooks, Microservices, JWT, RBAC, Async Processing |
| **Data Engineering** | PySpark, Databricks, Airflow, Kafka, BigQuery, SQL Server, Oracle |
| **Cloud** | GCP (Cloud Run, Vertex AI, Cloud Functions, BigQuery), AWS (ECS, S3, Lambda), Azure |
| **DevOps / Infra** | Docker, Kubernetes, Terraform, GitHub Actions, CI/CD, Prometheus, Grafana |
| **Databases** | PostgreSQL, Neon, Supabase, MongoDB, BigQuery, SQL Server, Oracle |

---

# 🧩 AI Product Portfolio

## 1. Ace HR AI Staffing — API-First Recruiting & Onboarding Engine 🔨

**Role:** Founding AI Architect · **Status:** In active development

Agencies send candidates through a parse → interview → onboard engine by API and get structured scorecards and onboarding status back by webhook, while keeping their own ATS and branding.

- Resume parsing with **bias-stripped scoring and ranking**, backed by an immutable audit log
- **Agentic workflows** from candidate intake to Day-1 onboarding; AI voice interviews in build
- Post-offer onboarding: document collection, AI verification and compliance routing
- Security-first delivery: protected source code, delivery pipeline and data environments

`Python` · `FastAPI` · `LangGraph` · `Claude` · `OpenAI` · `PostgreSQL` · `Webhooks` · `Audit Logging`

---

## 2. Knuckler AI — Career Intelligence & Resume Platform · [knuckler.app](https://knuckler.app/)

**Role:** Founder / Founding AI Engineer

An AI resume and submission platform for staffing, bench sales and IT consulting teams. Enter a candidate once, paste a job description, and get a tailored resume, cover letter and recruiter email built only from the candidate's real experience.

- Multi-agent pipelines for **resume parsing, skill extraction and role matching** using RAG, OCR, embeddings and LLM scoring
- Grounding guardrails so generated resumes never invent experience, plus an **ATS check** before every download
- Duplicate-submission warnings, pipeline and bench tracking, and a candidate portal
- Salesforce- and Apollo-style CRM and enrichment workflows for candidate and job intelligence

`Next.js` · `React` · `FastAPI` · `Neon Postgres` · `Vercel AI SDK` · `LangGraph` · `CrewAI` · `RAG` · `OpenAI` · `Claude` · `Gemini`

---

## 3. ClonA AI — AI Dubbing & Voice Studio · [dev.clona.io](https://dev.clona.io/)

**Role:** Founding AI Engineer

An AI dubbing studio for film studios and creators that clones a speaker's voice and re-voices content in **30+ languages**, keeping the emotion of the original performance.

- Dubbing and lip-sync pipelines combining **video processing, voice cloning, speech-to-speech synthesis and model orchestration**
- **GPU-backed inference** and batch processing on NVIDIA A100/H100 with CUDA
- Lip-sync research with **LatentSync** for Indian-language cinema (Visra)
- Production APIs for model execution, quality checks and output delivery

`Python` · `FastAPI` · `CUDA` · `A100/H100` · `LatentSync` · `ElevenLabs` · `Deepgram` · `LiveKit` · `Replicate`

---

## 4. GradeUS AI — AI Grading & Assessment Platform · [gradeus.ai](https://gradeus.ai/home)

**Role:** Co-Founder / Technical Architect

An AI assessment platform that grades handwritten and typed coursework against each instructor's rubric and returns personalized feedback to every student. Piloted with institutions.

- **Multi-agent LangGraph grading**: OCR (Chandra model) → rubric evaluation agents → structured scorecards
- Multimodal recognition of handwritten logic, hand-drawn diagrams and technical reports
- **Hallucination-aware evaluation** aligned with each professor's rubric and penalty rules
- Automated feedback reports, exportable grade tables and class-level analytics

`Python` · `FastAPI` · `LangGraph` · `CrewAI` · `OCR` · `Vision Models` · `RAG` · `Next.js` · `PostgreSQL`

---

## 5. Olvi — AI Nutrition & Lifestyle App · [olvi.io](https://olvi.io/)

**Role:** Technical Architect (built through Bluetomic LLC, which I co-founded) · **Live on** [App Store](https://apps.apple.com/us/app/olvi/id6793376875) and [Google Play](https://play.google.com/store/apps/details?id=io.olvi.app)

Photograph a meal and Olvi identifies each item, estimates portions and logs macros and micronutrients in about a minute.

- Multi-step **AI vision pipeline** from photo to food items, portions and nutrients, with async job tracking
- **"Ask Olvi" chat** grounded in each user's own meal log, plus personalized calorie and macro targets
- Meal, exercise and pantry-based meal-prep plans with Apple Health, Health Connect and Fitbit sync
- Clinic portal and shareable reports for doctors and dietitians

`React Native` · `Expo` · `AI Vision Models` · `LLM Chat` · `Wearable Health APIs`

---

## 6. MediFigure — AI Scientific & Medical Figure Generator · [Live](https://medifigure-web-7g63t6e75a-uc.a.run.app/)

**Role:** Founder / Technical Architect

Students, clinicians and researchers describe a topic and get exam-ready scientific figures and medical images: anatomy, pathways, flowcharts, cross-sections and timelines.

- An AI **"illustration architect"** that turns each prompt into a structured, labeled visual brief before generation
- **Multi-model routing** across Recraft V3, Flux, Nano Banana and GPT Image with automatic fallback
- Animated step-by-step walkthroughs for every figure
- Credit-based plans, deployed on **Google Cloud Run**

`Google Cloud Run` · `LLM Prompt Planning` · `Recraft V3` · `Flux` · `Nano Banana` · `GPT Image`

---

## More Products

- **BoxOps AI** (AI Engineer): film distribution operations automation: theater collection submissions, weekly reporting and invoice generation. `FastAPI` · `React` · `React Native / Expo` · `PostgreSQL`
- **Sakura AI** (Founder): AI workflow automation SaaS with multi-tenant architecture, developer APIs and Stripe usage-based billing. `Next.js` · `Supabase` · `FastAPI` · `Stripe` · `Webhooks`
- **Visra** (Product Builder): AI video and multilingual dubbing experiences across 12+ languages on A100/H100 GPU pipelines. `Python` · `GPU Inference` · `TTS` · `Video Processing`

---

# 🔬 In the Lab Now

- **Open-source model training & client deployment:** fine-tuning open-weight models and deploying them into each client's own environment with **Hugging Face, NVIDIA GPUs and vLLM**.
- **Knuckler Labs:** a platform that turns a product spec into a working **React Native / Expo** mobile app and ships it to the App Store and Google Play automatically.
- **Construction drawing intelligence:** an AI product for civil construction companies that reads construction drawings and analyzes them.

---

# 🛠️ Featured Technical Projects

## [Healthcare Intelligence Pipeline](https://github.com/msaiprasad1/Hybrid-ETL-ML-Orchestration-Platform-GitHub-1)

Predictive healthcare analytics with **Python, FastAPI, Streamlit, ML models and CrewAI agents**.

- ETL for healthcare data preprocessing, validation and feature generation
- Readmission risk prediction with **Random Forest and Gradient Boosting**, reaching about **85% accuracy**
- **CrewAI multi-agent** analysis and explanation, plus a Streamlit dashboard for patient risk

`Python` · `FastAPI` · `Streamlit` · `CrewAI` · `Random Forest` · `Gradient Boosting`

## [AI-ML Analytics Assistant](https://github.com/msaiprasad1/AI-ML-Analytics-Assistant)

Upload a dataset, ask questions in plain language, and get insights and ML workflows.

- Natural-language query processing with **LangChain and OpenAI GPT**
- scikit-learn pipelines for classification, regression and model evaluation
- Automated EDA, summaries and model recommendations for non-technical users

`LangChain` · `OpenAI GPT` · `scikit-learn` · `FastAPI` · `Streamlit` · `Pandas`

## [AI-Enhanced Big Data Pipeline Framework](https://github.com/msaiprasad1/ai-enhanced-bigdata-pipeline)

Intelligent ETL automation with **PySpark, Airflow, Kafka and MLflow**.

- Streaming ingestion, modular transformations and validation checkpoints
- Adaptive data-quality monitoring with **Isolation Forest, LOF and statistical methods**
- **MLflow** tracking for model versioning, experiments and retraining

`PySpark` · `Airflow` · `Kafka` · `MLflow` · `Isolation Forest` · `LOF`

## Revolutionizing Maternal Health in 3D with AI Medical Imaging

🏆 **Winner, NIH All of Us AI Hackathon**

AI maternal health monitoring with **OpenCV, Open3D and Intel RealSense 3D cameras** for gait analysis, posture tracking and fall detection.

`OpenCV` · `Open3D` · `Intel RealSense` · `Computer Vision` · `Healthcare AI`

---

# 🏢 Professional Experience

## Founding AI Architect — Stealth AI Startup (Ace HR AI Staffing)
**Jun 2026 – Present** · Miami, FL (Remote)

- Architecting agentic AI systems with **LangGraph and CrewAI** on Claude, OpenAI GPT and open-weight LLMs, with tool calling and **MCP** integrations
- Building production **RAG**, evaluation harnesses and feedback loops that catch quality regressions before release
- Fine-tuning open-weight LLMs with **LoRA/QLoRA** and optimizing GPU inference
- Shipping Python/FastAPI services with **Docker, Terraform and CI/CD** on GCP and AWS, using **Claude Code and Codex** daily

## AI Engineer — State of Florida, Department of Health
**Dec 2025 – May 2026** · West Palm Beach, FL

- AI-assisted document intake with **OCR, NLP, structured parsing and validation**
- Python and Oracle ETL pipelines with data-quality checks and regression testing
- **Power Apps** data collection apps, Power Automate workflows and **Power BI** dashboards for KPIs, anomaly detection and executive reporting

## Founding AI Engineer — Stealth Startup / Knuckler AI
**Sept 2025 – Nov 2025** · Harrison, NJ (Remote)

- AI backend services and REST APIs with **Python, FastAPI, Next.js and Neon Postgres**
- Multi-agent workflows with **LangChain, LangGraph, CrewAI and MCP Server**; RAG on Pinecone, FAISS and ChromaDB
- Ingestion, enrichment, deduplication, scoring and semantic matching workflows, with RAG traceability and prompt evaluation

## GenAI Engineer / AI Full Stack — Smart Structures (Client: U.S. Army Corps of Engineers)
**May 2025 – Aug 2025** · Riviera Beach, FL

- RAG and multi-agent workflows for technical document analysis, cutting manual QA/QC review time by **40%**
- Cloud data pipelines with **BigQuery, Pub/Sub, Cloud Composer, Python and SQL**
- Secure APIs with JWT and role-based access; services on Docker and AWS ECS, **25%** faster responses

## Research ML / Data Engineer — South Florida Water Management District / FAU
**Jan 2024 – Apr 2025** · West Palm Beach, FL

- Anomaly detection (**Isolation Forest, One-Class SVM, LOF**) on hydrologic time-series, improving predictive accuracy by **35%**
- PySpark ETL across Oracle, SQL Server and BigQuery with Prometheus/Grafana monitoring
- A generative AI hydrology assistant with **LangChain, RAG and vector search**

## Data Analyst (AI & Data Engineering) — Deloitte USI (Gilead Sciences / GovConnect)
**Jan 2022 – Dec 2023** · India

- ETL/ELT pipelines with **Python, PySpark, SQL, Dataflow, Cloud Composer and BigQuery**
- Salesforce integrations through REST APIs, Salesforce APIs and SOQL; **OmniStudio (Vlocity)** public-sector workflows for California child care licensing
- Data quality, reconciliation and validation, plus Einstein Analytics predictive scoring

---

# 🎓 Education

- **M.S., Data Science and Analytics**: Florida Atlantic University · GPA 3.89/4.0 · Graduate Research Assistant (AI & Water Data)
- **B.Tech, Mechanical Engineering**: K L University · CGPA 9.2/10

---

# 🏅 Certifications

- Google Cloud Certified Professional Data Engineer
- Oracle Cloud Infrastructure 2025 AI Foundations Certified
- Deloitte AI Academy Certified
- Microsoft Certified Power BI Data Analyst Associate
- Salesforce Certified Agentforce Specialist (in progress)
- Big Data Engineer Certified
- CITI Responsible Conduct of Research (RCR)

---

# 📊 About My Repositories

Most of my product work lives in **private repositories**: production SaaS codebases, client-specific deployments and confidential builds. The live links above show those products running. Public repos here cover featured projects, experiments and reference implementations.

---

# 🤝 Let's Connect

I enjoy building **AI-native products, multi-agent systems, RAG and evaluation pipelines, and GPU inference** with teams that ship.

📧 **Email:** saiprasadmuppala2602@gmail.com  
📞 **Phone:** +1 415-470-7299  
🔗 **LinkedIn:** https://www.linkedin.com/in/sai-prasad-muppala/  
💻 **GitHub:** https://github.com/msaiprasad1

---

> **AI products are not just about models. They are about workflows, trust, usability, speed and execution.**
