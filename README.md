# Asaif Ali

### AI/ML Engineer | Generative AI | Agentic AI | RAG | LLM Systems

I build **production-oriented AI systems** that combine LLMs, agentic workflows, retrieval, deterministic controls, evaluation, observability, and cloud deployment.

My engineering focus is moving beyond `prompt → response` toward systems that are **reliable, testable, evidence-grounded, observable, and deployable**.

## Featured projects

### 1. LegacyLens — Agentic Software Modernization

Multi-language legacy-code modernization platform combining program analysis, dependency intelligence, retrieval, migration planning, agentic transformation, and post-migration QA.

- AST / CTags analysis and dependency intelligence
- Qdrant-backed knowledge storage and retrieval
- Migration planning and context-grounded conversion
- Language-agnostic execution and validation adapters
- Post-migration quality gates and risk reporting
- FastAPI + Streamlit + Docker + Render Blueprint

**Repository:** https://github.com/AsaifAli/AI-Code-Modernization-Platform

### 2. FlowPilot — Agentic Automation Platform

Production-minded AI automation control plane built around asynchronous workflows, approval boundaries, evidence, persistence, scheduling, and observability.

- LangGraph orchestration
- FastAPI control plane
- Redis/RQ async execution
- PostgreSQL run and audit persistence
- Human-in-the-loop approval
- Prometheus, Grafana, OpenTelemetry, and Jaeger
- Render Blueprint deployment

**Repository:** https://github.com/AsaifAli/AI-Automation-Command-Center

### 3. EvidenceFlow — Verified Sparse-First RAG & Research

LangGraph research and document intelligence system built around sparse-first retrieval, adaptive query recovery, evidence provenance, citation verification, and fail-closed behavior.

- OpenSearch BM25, exact, phrase, fuzzy, and metadata-aware retrieval
- Optional neural-sparse retrieval without dense-vector k-NN
- Reciprocal Rank Fusion (RRF) across retrieval candidates
- Cross-encoder reranking with Jina AI
- Bounded agentic query expansion for weak first-pass retrieval
- Persistent multi-turn conversation state with LangGraph checkpointing
- Evidence registry with stable turn-scoped evidence IDs
- Citation verification, numeric/date support checks, and evidence-conflict detection
- Safe handling of retrieved documents and web content as untrusted data
- Fail-closed behavior when evidence is missing or cannot be verified

**Repository:** https://github.com/AsaifAli/LangGraph-RAG

### 4. QuoteSense — Procurement Intelligence

AI-powered quotation analysis system that combines LLM extraction with deterministic validation and scoring.

- PDF / DOCX / TXT / XLSX ingestion
- Structured extraction and schema validation
- Deterministic procurement scoring
- Completeness and risk checks
- Evidence traceability
- FastAPI + Streamlit + Docker

**Repository:** https://github.com/AsaifAli/quotation-analyzer

### 5. WebQA Intelligence — AI-Assisted Testing

Playwright-based web application QA intelligence platform for dynamic-site crawling, structured DOM analysis, QA risk assessment, test-plan generation, and regression detection.

- Same-domain browser crawling
- Authentication support
- Structured DOM and interaction analysis
- Evidence-grounded QA generation
- Browser health and regression signals
- Safe-by-default interaction model

**Repository:** https://github.com/AsaifAli/web-crawler-agent

## Shared Portfolio LLM Gateway

The five interactive projects use a shared OpenAI-compatible gateway for BYOK sessions.

```text
Portfolio
   ↓
Redis-backed session
   ↓
Short-lived JWT
   ↓
Project
   ↓
Portfolio LLM Gateway
   ↓
User's selected provider/model
```

Provider credentials remain server-side; projects receive a temporary session token rather than the provider API key.

**Repository:** https://github.com/AsaifAli/shared-Portfolio-LLM-Gateway

## Engineering principles

```text
Unstructured Data
      ↓
Processing / Retrieval
      ↓
LLM / Agents
      ↓
Structured Validation
      ↓
Deterministic Logic
      ↓
Evidence / Quality Gates
      ↓
Evaluation / Observability
      ↓
API / Application
      ↓
Containerized Deployment
```

Across projects I emphasize:

- Structured LLM outputs and schema validation
- Evidence-grounded generation and citation verification
- Retrieval designed for recall, precision, and transparent failure modes
- Deterministic business rules and quality gates
- Human-in-the-loop controls for external-impact actions
- Automated evaluation and regression testing
- Health/readiness checks and observability
- Dockerized, cloud-deployable services

## Connect

**LinkedIn:** https://www.linkedin.com/in/sk-asaif-ali-134873243/

**Portfolio:** https://asaifali-portfolio.vercel.app

**GitHub:** https://github.com/AsaifAli

## Current focus

**Generative AI · Agentic AI · RAG · LLM Systems · AI Reliability · AI Automation · Document Intelligence · Software Modernization · AI-Assisted QA**
