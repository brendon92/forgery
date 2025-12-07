# FORGERY: Scalable, Self-Improving Executive AI Agent

**Codename:** FORGERY

## Project Goal
To build a highly scalable, autonomous agent system capable of handling complex, executive-level tasks. The system prioritizes **determinism, deep contextual memory, and cost control** over purely exploratory models.

## Core Architecture
- **Orchestration:** **LangGraph** for deterministic flow control, resilience, and human-in-the-loop checkpointing.
- **Memory:** **GraphRAG** (Neo4j + Vector DB) for complex, multi-hop reasoning and persistent contextual awareness.
- **Scalability:** **RAG-on-Tools** (LlamaIndex) for efficient tool selection and context optimization.
- **Observability:** **Langfuse/LangSmith** for distributed tracing and FinOps monitoring.

## Tech Stack
- **Backend:** Python, FastAPI, MCP Server
- **Frontend:** Next.js, React, TailwindCSS
- **Infrastructure:** Docker, Docker Compose

## Current Status
- [x] Core LangGraph Node Architecture
- [x] MCP Server Integration
- [x] Basic Frontend (Next.js)
- [ ] GraphRAG Implementation
- [ ] Self-Improvement Loops (Reflection & TT-SI)
