# Asaif Ali

### AI Engineer | Generative AI | Agentic Systems | RAG | AI Engineering

I design and build AI applications that move beyond simple prompt-and-response experiences: systems with retrieval, orchestration, structured outputs, deterministic validation, human approval boundaries, and practical deployment paths.

My focus is on making AI useful in real workflows while keeping its behavior inspectable, testable, and appropriately governed.

## Featured AI applications

### 1. EvidenceFlow — Verified Research & Document Intelligence

A LangGraph-based research and RAG application built around sparse-first retrieval, evidence provenance, citation verification, and fail-closed answers.

- OpenSearch lexical retrieval with BM25; optional neural-sparse retrieval
- Reciprocal Rank Fusion and cross-encoder reranking
- Bounded query expansion when initial evidence is weak
- Document ingestion, persistent conversations, and source traceability
- Citation and grounding checks, conflict detection, and evidence-sufficiency states

**Repository:** [LangGraph-RAG](https://github.com/AsaifAli/LangGraph-RAG)

### 2. QuoteSense — Procurement Intelligence

An AI-assisted quotation analysis application that turns supplier documents into structured, comparable, explainable procurement decisions.

- PDF, DOCX, TXT, and XLSX ingestion
- LLM-assisted extraction with schema validation
- Deterministic multi-criteria scoring and supplier comparison
- Completeness checks, commercial risk detection, and price anomaly signals
- Evidence traceability and human-reviewed recommendations

**Repository:** [quotation-analyzer](https://github.com/AsaifAli/quotation-analyzer)

### 3. FlowPilot — AI Workflow Automation

An AI automation workspace for launching and managing workflow runs with asynchronous execution, role-scoped access, and approval boundaries.

- Content drafting and channel adaptation
- Competitor intelligence and evidence-oriented briefs
- Opportunity qualification and approval-ready outreach drafts
- KPI normalization, blocker detection, and leadership briefings
- FastAPI workflow API, Streamlit workspace, execution tracking, and Gateway-based BYOK handoff

**Repository:** [AI-Automation-Command-Center](https://github.com/AsaifAli/AI-Automation-Command-Center)

### 4. LegacyLens — Software Modernization Workbench

An agentic software modernization application combining repository analysis, migration planning, context-grounded conversion, syntax-aware validation, bounded repair, and release gates.

- Multi-language program and dependency analysis
- Retrieval over repository structure and migration context
- Planned code transformation with deterministic validation
- Post-migration checks, review states, and downloadable reports

**Repository:** [AI-Code-Modernization-Platform](https://github.com/AsaifAli/AI-Code-Modernization-Platform)

### 5. WebQA Intelligence — Browser QA Workbench

A Playwright-based application for analyzing web applications, generating evidence-backed QA plans, executing explicitly authorized safe tests, and reviewing regressions.

- Same-domain browser crawling and optional authentication
- Structured DOM, form, and interaction discovery
- Evidence-grounded test planning and risk assessment
- Explicit safe test execution and regression baselines
- Reports and exports for QA review

**Repository:** [web-crawler-agent](https://github.com/AsaifAli/web-crawler-agent)

## Shared infrastructure

### Portfolio LLM Gateway

A shared OpenAI-compatible inference gateway used by interactive portfolio applications. It supports provider-specific adapters, encrypted provider credentials, short-lived project-scoped sessions, and one-time handoff codes. The website owns provider selection and BYOK credential entry; applications receive temporary session access rather than the user's raw provider key.

**Repository:** [shared-Portfolio-LLM-Gateway](https://github.com/AsaifAli/shared-Portfolio-LLM-Gateway)

### Engineering Assurance

A deliberately small internal service for replay-quality evidence and content-free application telemetry. Its retained evaluation packs cover **EvidenceFlow** and **QuoteSense** only. The read-only dashboard distinguishes synthetic replay fixture scores from actual application activity; those fixture scores are not live model-accuracy claims.

**Repository:** [ai-engineering-evaluation-harness](https://github.com/AsaifAli/ai-engineering-evaluation-harness)

### AI-Native Agency OS

A separate private, founder-controlled operating environment for the AI engineering studio. It contains the agency's native workforce, revenue and delivery foundations, governed execution, and founder-approval boundaries. It is not a public SaaS product, and its workforce catalogue should not be mistaken for a claim that every agent is already an autonomous live runtime.

**Repository:** private — not publicly linked.

## Engineering approach

I work across:

- Generative AI, LLM integration, and agentic workflow design
- RAG, retrieval quality, source provenance, and citation verification
- Document intelligence, extraction, validation, and deterministic scoring
- Workflow orchestration, asynchronous execution, and human approval
- FastAPI, Python, Streamlit, Next.js, Docker, and cloud deployment
- BYOK session architecture, provider abstraction, and application security
- Testing, evaluation, observability, and failure-aware system design

I aim to separate probabilistic model behavior from deterministic controls, make failure states visible, and keep consequential actions reviewable.

## Connect

- **LinkedIn:** https://www.linkedin.com/in/sk-asaif-ali-134873243/
- **Portfolio:** https://asaifali-portfolio.vercel.app
- **GitHub:** https://github.com/AsaifAli

---

*The repositories represent independent engineering demonstrations and supporting infrastructure. Descriptions do not imply customer deployments, customer outcomes, production certification, or that every optional hosted integration is currently configured.*
