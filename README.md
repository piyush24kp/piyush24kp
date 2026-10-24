## 👋 Hi, I'm Piyush Patil — Tech Lead · Gen AI & AI Engineering

🏢 **Wipro** · HP Managed Print Services — leading AI Engineering & Gen AI delivery
🎓 **MSc Machine Learning & AI** — Liverpool John Moores University (LJMU) · Executive PG Diploma completed via IIIT Bangalore · Research phase in progress
📍 Pune, India · Open to **remote Gen AI Lead / AI Architect** roles · Open to relocation **Dubai / Abu Dhabi**

---

### 🔧 What I Build

| Area | Stack |
|---|---|
| LLMs & AI APIs | GPT-4o · Anthropic Claude (Haiku 4.5 / Sonnet 4.6) · AWS Bedrock · Gemini · Mistral · Llama 3 |
| RAG & Knowledge Systems | LangChain · LlamaIndex · ChromaDB · pgvector · FAISS · Pinecone · GraphRAG |
| Agentic AI | LangGraph · CrewAI · MCP · ReAct agents · n8n · AutoGen |
| LLMOps & Eval | LangSmith · RAGAS · DeepEval · Guardrails AI · AWS Bedrock Guardrails |
| Backend | Java 21 · Spring Boot 3.x · Python · FastAPI · Node.js · Kafka · AWS |
| Frontend | React.js · TypeScript · JavaScript (ES6+) · HTML5 · CSS3 · Angular.js |
| Cloud & Infra | AWS (Bedrock · SageMaker · EC2 · Lambda · S3 · RDS · DynamoDB) · Docker · Kubernetes |

---

### 🚀 Featured Projects

### 🤖 [Deep Research Agent Swarm](https://github.com/piyush24kp/Deep-Research-Agent-Swarm)
> Full-stack multi-agent research system — orchestrates up to 24 Claude agents in parallel to produce fact-checked, cited reports in real time.

**What it does**
- Streams a live agent graph (Planner → Orchestrator → Searchers → Critic → Fact-Checker → Synthesizer) via Server-Sent Events
- 5-dimension trust scoring on every claim (source authority, recency, cross-agreement, fact-checker verdict)
- Persistent research history panel — re-read any past report with full cost breakdown
- Per-model and per-agent-type cost tracking with progress-bar visualisations

**Stack:** Python · FastAPI · LangGraph · Anthropic Claude API (Sonnet 4.6 + Haiku 4.5) · Tavily · React · TypeScript · @xyflow/react

---

#### 🔐 [RAGGuardRails](https://github.com/piyush24kp/RAGGuardRails)
> RAG chatbot with RBAC + Guardrails + LangSmith monitoring

- Role-based document access (HR / Finance / Marketing / Engineering / CEO)
- Input guardrails (scope check + injection detection) + Output PII redaction
- Evaluated with **RAGAS** (faithfulness, answer relevancy, context precision)
- Stack: `LangChain` · `ChromaDB` · `Llama 3.3 70B (Groq)` · `Streamlit` · `FastAPI`

---

#### 🧠 [Intelligent Log Classifier](https://github.com/piyush24kp/intelligent-log-classifier)
> 3-tier hybrid classifier: Regex → ML → LLM with 100% test accuracy

- Cascading architecture: deterministic Regex → sentence-transformers → Groq LLM fallback
- 87.5% of logs handled by Regex; LLM only activates for novel/ambiguous cases
- Stack: `scikit-learn` · `sentence-transformers` · `Llama 3.3 70B (Groq)` · `FastAPI`

---

#### ☁️ [Foundation Model Eval on AWS Bedrock](https://github.com/piyush24kp)
> Automated benchmarking pipeline comparing Claude 3, GPT-4o, Titan, Mistral & Llama 3

- Dynamic model routing that selects optimal model per query complexity
- 18% API cost reduction · Private VPC deployment · RAGAS eval suite
- Stack: `AWS Bedrock` · `RAGAS` · `LangChain` · `Grafana`

---

#### 🗺️ [AI Interview Blueprint](https://github.com/piyush24kp/aiblueprint)
> SaaS product that turns an engineer's existing system into a ready-to-present AI/GenAI project blueprint — grounded in their real domain, no fabrication.

- Multi-agent pipeline: Discovery loop → 6 specialist agents (Scout, Architect, Ethics, Critic, Fact-Checker, Synthesizer) → assembled PDF/HTML/Markdown deliverable
- RBAC quota ledger with DynamoDB-backed concurrency guarantees (50-way race tested); Razorpay payment integration
- Deterministic ethics validator — ensures AI safety sections are never softened by model output
- 470 tests · Node.js + TypeScript backend · Plain HTML/CSS/ES modules frontend · AWS Bedrock (Claude Sonnet 4.6 + Haiku 4.5)
- Stack: `Node.js` · `TypeScript` · `AWS Bedrock` · `DynamoDB` · `Razorpay` · `Mermaid` · `FastAPI`

---

### 📈 Key Wins @ Wipro (HP MPS)
- 35% reduction in incident MTTR via AI triage (GPT-4o + RAG) — 10K+ incidents/month
- 22% LLM API cost reduction through LLMOps tooling (LangSmith + RAGAS + model routing)
- 70% reduction in manual reporting via n8n AI automation pipeline
- 40% API latency improvement (780ms → 468ms) on critical payment platform (ThoughtWorks)
- Led & mentored a team of 8 engineers across US / EU / India timezones into Gen AI delivery

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/piyush-patil-ba1829a9)
[![Portfolio](https://img.shields.io/badge/Portfolio-piyush24kp.github.io-1A1A2E?style=flat&logo=github)](https://piyush24kp.github.io)
[![GitHub](https://img.shields.io/badge/GitHub-piyush24kp-181717?style=flat&logo=github)](https://github.com/piyush24kp)
