## 👋 Hi, I'm Piyush Patil — AI Engineering Lead

🏢 **Wipro** · HP Managed Print Services — leading Gen AI engineering for a 5M-device global platform  
🎓 **MSc Machine Learning & AI** — Liverpool John Moores University (LJMU)  
📍 Indore, India · Open to **remote AI Lead / Gen AI Lead** roles globally  

---

### 🔧 What I Build

| Area | Stack |
|---|---|
| RAG & Knowledge Systems | LangChain · LlamaIndex · ChromaDB · pgvector · FAISS · Pinecone |
| Agentic AI | LangGraph · CrewAI · MCP · ReAct agents · n8n |
| LLMOps & Eval | LangSmith · RAGAS · DeepEval · Guardrails AI · LangSmith |
| LLMs | GPT-4o · Llama 3 (Groq) · Mistral · Anthropic Claude · Gemini |
| Backend | Java 21 · Spring Boot 3.x · FastAPI · Kafka · AWS |

---

### 🚀 Featured Projects

### 🤖 [Deep Research Agent Swarm](https://github.com/piyush24kp/Deep-Research-Agent-Swarm)
> Full-stack multi-agent research system — orchestrates up to 24 Claude agents in parallel to produce fact-checked, cited reports in real time.

**What it does**
- Streams a live agent graph (Planner → Orchestrator → Searchers → Critic → Fact-Checker → Synthesizer) via Server-Sent Events
- 5-dimension trust scoring on every claim (source authority, recency, cross-agreement, fact-checker verdict)
- Persistent research history panel (localStorage) — re-read any past report with full cost breakdown
- Per-model and per-agent-type cost tracking with progress-bar visualisations

**Stack:** Python · FastAPI · LangGraph · Anthropic Claude API (Sonnet 4.6 + Haiku 4.5) · Tavily · React · TypeScript · @xyflow/react
**Resume keywords:** multi-agent orchestration · prompt caching · SSE streaming · LangGraph StateGraph · async Python · React + TypeScript

#### 🔐 [RAGGuardRails](https://github.com/piyush24kp/RAGGuardRails)
> Production-grade internal chatbot with RAG + RBAC + Guardrails + LangSmith monitoring

- Role-based document access (HR / Finance / Marketing / Engineering / CEO)  
- Input guardrails (scope check + greeting detection) + Output PII redaction  
- Evaluated with **RAGAS** (faithfulness, answer relevancy, context precision)  
- Stack: `LangChain` · `ChromaDB` · `Llama 3.3 70B (Groq)` · `Streamlit` · `FastAPI`

#### 🧠 [Intelligent Log Classifier](https://github.com/piyush24kp/intelligent-log-classifier)
> 3-tier hybrid classifier: Regex → ML → LLM with 100% test accuracy

- Cascading architecture: deterministic Regex → sentence-transformers ML → Groq LLM fallback  
- 87.5% of logs handled by Regex, LLM only activates for novel/ambiguous cases  
- REST API (FastAPI) + Streamlit UI with batch classification support  
- Stack: `scikit-learn` · `sentence-transformers` · `Llama 3.3 70B (Groq)` · `FastAPI`

---

### 📈 Key Wins @ Wipro (HP MPS)
- 35% reduction in incident MTTR via AI triage (GPT-4o + RAG)
- 22% LLM API cost reduction through LLMOps tooling
- 70% reduction in manual reporting via n8n AI automation pipeline
- Led & mentored a team of 8 engineers into Gen AI delivery

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/piyush-patil-ba1829a9)
[![GitHub](https://img.shields.io/badge/GitHub-piyush24kp-181717?style=flat&logo=github)](https://github.com/piyush24kp)
