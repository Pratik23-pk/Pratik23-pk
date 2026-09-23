# Hi, I'm Pratik Kanjilal

### Agentic AI Engineer | Multi-Agent Systems | RAG | MLOps

I build AI systems that do more than generate text: they **plan, use tools, preserve state,
coordinate specialized agents, validate their work, repair failures, and deliver usable software**.

My current focus is production-oriented Agentic AI with LangGraph, LangChain, MCP, reliable
evaluation and repair loops, human-in-the-loop control, retrieval engineering, and cost-aware model
orchestration.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" alt="LangGraph" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/MCP-5A45FF?style=flat-square" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
</p>

## Agentic AI Engineering

- **LangGraph orchestration:** durable parent workflows, repair subgraphs, conditional routing,
  checkpointing, long-term memory, resumable execution, and human approval gates.
- **Multi-agent architecture:** planner, design, database, backend, frontend, evaluator, artifact,
  and repair responsibilities with explicit contracts and file ownership.
- **MCP and tool use:** policy-controlled tools, browser automation, web search, provider actions,
  output redaction, auditability, and bounded execution.
- **Reliability engineering:** canonical file manifests, deterministic validation, failure
  fingerprinting, targeted repair, runnable fallbacks, security guardrails, and sandboxed previews.
- **Cost-aware AI:** role-based model routing, token accounting, per-run cost ledgers, hard budget
  ceilings, context optimization, and bounded retries.
- **RAG systems:** hybrid retrieval, embeddings, reranking, diversity filtering, context compression,
  source isolation, and grounded generation.

## How I Build Agentic Products

```mermaid
flowchart LR
    Intent["Product Intent"] --> Plan["Planning + Specifications"]
    Plan --> Agents["Specialized Agents"]
    Agents --> Tools["MCP Tools + External Services"]
    Agents --> Memory["State + Checkpoints + Memory"]
    Tools --> Validate["Deterministic Validation"]
    Memory --> Validate
    Validate --> Evaluate["Semantic Evaluation"]
    Evaluate -->|"repair"| Repair["Evidence-Driven Repair"]
    Repair --> Validate
    Evaluate -->|"approved"| Release["Previewable / Deployable Product"]
    Human["Human Approval"] -.-> Plan
    Human -.-> Release
```

## Featured Projects

### [Agentic Forge](https://github.com/Pratik23-pk/agentic-forge)

A guarded, budget-aware multi-agent software development studio that converts natural-language
requirements into generated, validated, repairable, previewable, and downloadable applications.

`LangGraph` `MCP` `OpenAI` `FastAPI` `React` `TypeScript` `PostgreSQL` `Supabase` `Redis`
`Playwright` `Docker` `LangSmith`

- Durable LangGraph workflow with checkpointing, memory, conditional routing, and human approvals
- Specialized planner, design, database, backend, frontend, evaluator, and repair responsibilities
- Universal Repair Kernel with structured evidence, full-project context, and bounded escalation
- Deterministic capability adapters, dependency audits, browser tests, guardrails, and isolated previews
- Per-node model routing and a global cost ledger for controlled production economics

### [Mermaid Research Copilot](https://github.com/Pratik23-pk/mermaid_researchCopilot)

A user-isolated RAG system for PDFs and web content with Django authentication, FastAPI ingestion,
ChromaDB storage, hybrid lexical/vector retrieval, reranking, diversity filtering, and context
compression.

### [Workforce Intelligence MLOps](https://github.com/Pratik23-pk/workforce-mlops)

An end-to-end workforce forecasting platform with a PyTorch multi-head model, FastAPI inference,
DVC pipelines, MLflow tracking, Docker, GitHub Actions, Kubernetes, and GitOps-ready deployment.

### [Bowel Sound Detection AI](https://github.com/Pratik23-pk/bowel_sound_app_COMPLETE)

A biomedical audio-classification system using CRNN models, MFCC features, signal processing, and
deep-learning workflows for applied health AI research.

## Technical Toolkit

| Area | Technologies and Practices |
| --- | --- |
| Agentic AI | LangGraph, LangChain, MCP, multi-agent workflows, tool calling, memory, HITL, evaluation and repair |
| LLM and RAG | OpenAI APIs, embeddings, ChromaDB, hybrid search, reranking, prompt and context optimization |
| Backend and Data | Python, FastAPI, Django, Pydantic, PostgreSQL, Supabase, Redis, REST APIs |
| Frontend and Testing | React, TypeScript, Vite, Playwright, responsive product interfaces |
| ML and Audio AI | PyTorch, scikit-learn, CRNNs, MFCCs, recommendation and ranking systems |
| MLOps and Platform | Docker, GitHub Actions, DVC, MLflow, Kubernetes, Argo CD, AWS |
| Reliability and Security | Guardrails, DLP, secret detection, dependency auditing, sandboxing, observability |

## Engineering Principles

- Use deterministic checks before asking an LLM to judge correctness.
- Preserve complete state so retries repair software instead of recreating it blindly.
- Give agents narrow responsibilities, explicit contracts, and only the tools they require.
- Treat cost, security, observability, and human control as architecture—not afterthoughts.
- Optimize AI systems for working outputs, reproducibility, and evidence-backed decisions.

## GitHub Snapshot

![GitHub followers](https://img.shields.io/github/followers/Pratik23-pk?style=for-the-badge&logo=github&label=Followers)
![GitHub stars](https://img.shields.io/github/stars/Pratik23-pk?style=for-the-badge&logo=github&label=Stars)
![Profile views](https://komarev.com/ghpvc/?username=Pratik23-pk&style=for-the-badge&color=412991)

## Current Direction

I am focused on building reliable Agentic AI products that combine orchestration, retrieval,
software engineering, secure tool use, and deployment-aware workflows. I am open to Agentic AI,
Applied AI, AI Platform, ML Engineering, and backend-for-AI opportunities and collaborations.
