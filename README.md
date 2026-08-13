# Asaif Ali

### AI/ML Engineer | Generative AI | Agentic AI | RAG | LLM Systems

I build **production-oriented AI systems** that combine LLMs, agentic workflows, retrieval, machine learning, backend engineering, evaluation, and cloud-native infrastructure to solve practical engineering and business problems.

My focus is on building AI applications that go beyond `prompt → response` by incorporating **structured outputs, deterministic validation, evidence, human-in-the-loop controls, testing, observability, and containerized deployment**.

---

## 🧠 What I Build

* Generative AI & LLM applications
* Agentic AI & workflow orchestration
* Retrieval-Augmented Generation (RAG)
* Document intelligence & structured extraction
* AI-assisted software engineering
* AI-powered QA & automation
* Machine learning & NLP systems
* Evidence-grounded AI systems
* Human-in-the-loop AI workflows
* Production-ready AI APIs and services
* Dockerized and cloud-deployable AI applications

---

# 🚀 Featured Projects

## 1. AI Code Modernization Platform

### Multi-Agent AI Platform for Legacy Application Modernization

An AI engineering platform that analyzes legacy repositories, builds a structured understanding of their architecture, creates migration plans, performs context-grounded code transformation, and evaluates the resulting migration.

Rather than sending an entire repository directly to an LLM, the system combines **deterministic program analysis with agentic LLM workflows**.

### Key capabilities

* Multi-language repository analysis
* AST / Tree-sitter analysis
* Universal CTags symbol extraction
* Dependency and technology detection
* Complexity and structural signals
* Metadata-aware knowledge base
* LanceDB-backed retrieval
* Migration planning
* Context-grounded conversion agents
* Source/target structural comparison
* Migration risk scoring
* Unsupported-pattern detection
* Post-migration QA
* Migration reports and review checklists
* Provider abstraction for cloud/self-hosted LLMs
* FastAPI + Streamlit
* Docker Compose deployment
* Automated evaluation and CI

### Engineering approach

```text
Legacy Repository
       ↓
Program Analysis
       ↓
Knowledge Base
       ↓
Migration Planning
       ↓
Agentic Conversion
       ↓
Post-Migration QA
       ↓
Risk / Gap Analysis
       ↓
Migration Report
```

**Focus:** Agentic AI · LLM Engineering · Code Intelligence · RAG · Software Modernization · FastAPI · Docker

---

## 2. AI Automation Command Center

### Production-Minded AI Automation Control Plane

A production-oriented AI automation platform demonstrating how LLM agents can become **reliable asynchronous business workflows rather than isolated chatbot demos**.

The platform supports content generation, competitor intelligence, partner outreach, and KPI/leadership reporting workflows.

### Key capabilities

* LangGraph workflow orchestration
* FastAPI control plane
* Pydantic contracts and validation
* Redis + RQ asynchronous workers
* PostgreSQL persistence and audit history
* Scheduled workflows
* Human-in-the-loop approval
* Evidence and validation
* External-impact action controls
* Deterministic demo mode
* Prometheus metrics
* Grafana dashboards
* OpenTelemetry tracing
* Jaeger distributed tracing
* CI evaluation suite
* Docker Compose deployment
* Worker scaling

### Architecture

```text
Streamlit
    ↓
FastAPI Control Plane
    ↓
Redis Queue
    ↓
RQ Workers
    ↓
LangGraph Workflows
    ↓
Validation + Evidence
    ↓
PostgreSQL Audit Store

Observability
    ├── Prometheus
    ├── Grafana
    ├── OpenTelemetry
    └── Jaeger
```

**Focus:** Agentic AI · LangGraph · Distributed Systems · Async Workflows · Human-in-the-Loop · Observability · Production AI

---

## 3. Evidence-Grounded Agentic RAG Platform

### Fail-Closed Retrieval-Augmented Generation System

A LangGraph-based research and document intelligence platform designed around a key principle:

> **An AI system should not claim evidence it cannot verify.**

The system combines agentic routing, hybrid retrieval, reranking, web research, persistent conversation state, and deterministic citation verification.

### Key capabilities

* LangGraph agentic routing
* Knowledge-base / web / hybrid routing
* Dense + sparse hybrid retrieval
* Reciprocal Rank Fusion
* Qdrant vector search
* BM25 sparse retrieval
* Cross-encoder reranking
* Persistent conversation state
* Whole-document summarization
* Cross-document comparison
* Evidence registry
* Citation verification
* Citation coverage analysis
* Numeric/date evidence checks
* Evidence conflict detection
* Fail-closed behavior when evidence is insufficient
* Token instrumentation
* Evaluation suite
* Dockerized deployment
* CI

### Architecture

```text
User Query
    ↓
LangGraph Router
    ├── Knowledge Base
    ├── Web Research
    ├── Both
    └── Direct Response
           ↓
    Hybrid Retrieval
           ↓
      RRF Fusion
           ↓
     Cross-Encoder
       Reranking
           ↓
      Evidence Set
           ↓
      LLM Synthesis
           ↓
    Citation Verification
           ↓
     Verified Answer
```

**Focus:** RAG · LangGraph · Hybrid Retrieval · Qdrant · Reranking · AI Reliability · Evidence Grounding

---

## 4. Quotation Intelligence Platform

### AI-Powered Procurement & Document Intelligence

A production-oriented document intelligence system that processes multiple supplier quotations and turns unstructured commercial documents into **structured, comparable and explainable procurement intelligence**.

The system deliberately separates probabilistic LLM reasoning from deterministic business logic.

### Key capabilities

* Multi-document quotation ingestion
* PDF / DOCX / TXT / XLSX processing
* LLM-based structured extraction
* Provider-independent LLM architecture
* Gemini / OpenAI / optional Ollama
* Pydantic schema validation
* Generic output normalization
* Deterministic multi-criteria scoring
* Completeness validation
* Risk detection
* Price anomaly detection
* Evidence traceability
* Prompt-injection-aware document handling
* FastAPI API
* Streamlit dashboard
* Docker Compose
* Optional local/GPU inference
* Automated testing and CI

### Architecture

```text
Supplier Documents
        ↓
Document Processing
        ↓
LLM Extraction
        ↓
Normalization
        ↓
Pydantic Validation
        ↓
Deterministic Scoring
        ↓
Risk / Anomaly Detection
        ↓
Evidence-Grounded Reasoning
        ↓
Recommendation
        ↓
Human Review
```

The core design principle is:

```text
LLM → Extract & Reason

Python → Validate & Score

Human → Make the Final Decision
```

**Focus:** GenAI · Document Intelligence · Structured Outputs · LLM Reliability · Procurement Analytics · FastAPI · Docker

---

## 5. Web Crawler Agent

### AI-Powered Web Application QA Intelligence Platform

A Playwright-based web analysis and QA intelligence system that crawls dynamic websites, extracts structured DOM information, identifies interaction candidates, assesses QA risks, generates evidence-grounded test plans, and detects regressions.

The crawler is intentionally **safe by default**: it discovers and plans interactions but does not arbitrarily submit forms or trigger potentially destructive business actions.

### Key capabilities

* Playwright-based browser crawling
* Same-domain crawling
* Authentication support
* Dynamic-page analysis
* DOM structure extraction
* Heading and section analysis
* Form and field discovery
* Interactive-element detection
* QA risk scoring
* Evidence-grounded test generation
* Browser console-error detection
* Failed network request detection
* Regression baselines
* Structural change detection
* Optional Ollama summaries
* Markdown / HTML / JSON / CSV / DOCX reports
* Docker Compose
* Automated testing
* CI

### Architecture

```text
URL
 ↓
Playwright Browser
 ↓
Same-Domain Crawl
 ↓
Structured DOM Analysis
 ↓
QA Risk Assessment
 ↓
Evidence-Grounded Test Generation
 ↓
Browser Health Signals
 ↓
Regression Comparison
 ↓
Reports
```

**Focus:** AI-Assisted QA · Playwright · LLM Applications · Test Intelligence · Browser Automation · Docker

---

# 🛠️ Technical Stack

### Languages

`Python` · `SQL`

### AI / ML

`Machine Learning` · `NLP` · `Generative AI` · `Agentic AI` · `LLM Engineering`

### LLM & Agent Frameworks

`LangGraph` · `LangChain` · `CrewAI` · `Agno` · `OpenAI` · `Gemini` · `Ollama`

### RAG & Retrieval

`Qdrant` · `LanceDB` · `Embeddings` · `Hybrid Search` · `BM25` · `RRF` · `Cross-Encoder Reranking`

### Backend

`FastAPI` · `REST APIs` · `Pydantic`

### AI Applications

`Streamlit` · `Document Intelligence` · `AI Automation` · `QA Intelligence`

### Browser Automation

`Playwright`

### Databases & Infrastructure

`PostgreSQL` · `Redis` · `RQ`

### Observability

`Prometheus` · `Grafana` · `OpenTelemetry` · `Jaeger`

### DevOps

`Docker` · `Docker Compose` · `GitHub Actions` · `CI/CD` · `AWS`

---

# 🏗️ How I Approach AI Engineering

I don't treat an LLM as the entire application.

I design AI systems as a combination of **probabilistic intelligence and deterministic engineering controls**.

```text
             Unstructured Data
                    ↓
          Processing / Retrieval
                    ↓
              LLM / Agents
                    ↓
          Structured Validation
                    ↓
       Deterministic Business Logic
                    ↓
        Evidence / Quality Gates
                    ↓
        Evaluation & Observability
                    ↓
             API / Application
                    ↓
           Dockerized Deployment
```

This allows AI systems to become:

**Reliable · Testable · Explainable · Observable · Deployable**

---

# 🧪 AI Engineering Practices

Across my projects, I focus on:

* Structured LLM outputs
* Pydantic schema validation
* Deterministic scoring and business rules
* Evidence-grounded generation
* Citation verification
* Fail-closed AI behavior
* Human-in-the-loop workflows
* Prompt-injection awareness
* Automated evaluation
* Regression testing
* API health and readiness checks
* Asynchronous job processing
* Persistent audit trails
* Metrics and distributed tracing
* Containerized deployment

---

# 💼 Professional Experience

### Software Engineer (AI/ML) — Bebo Technologies

Working on enterprise AI systems involving:

* Agentic RAG
* LLM-powered automation
* Multi-agent engineering workflows
* AI-assisted application modernization
* Retrieval and knowledge systems
* AI-assisted software engineering workflows

---

# 📈 Currently

Building and deploying practical AI systems with a focus on:

**Generative AI · Agentic AI · RAG · LLM Applications · AI Automation · Document Intelligence · AI Reliability · Production AI Engineering**

---

# 🤝 Connect

**LinkedIn:**
[Connect with me](https://www.linkedin.com/in/sk-asaif-ali-134873243/)

**Live Projects:**  
See the pinned repositories above for deployed applications and technical documentation.

**Portfolio:**  
Coming soon

**Resume:**
Coming soon

---

### ⭐ Interested in AI Engineering, GenAI, Agentic AI, RAG, or production LLM systems?

Feel free to connect.
