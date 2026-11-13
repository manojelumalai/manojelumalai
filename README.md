# Hi, I'm Manoj Elumalai 👋
**AI Tech Lead & Platform Architect | Staff AI / Distributed Systems Engineer**  
📍 Kuala Lumpur, Malaysia ➔ Relocating to Singapore 🇸🇬 (MOM COMPASS EP Pre-Cleared: 70/40 pts)  
🌐 [LinkedIn](https://linkedin.com/in/manojelumalai) • 💻 [GitHub](https://github.com/manojelumalai) • ✉️ manoj.elumalai@outlook.com

---

### 🚀 About Me
I design and operate hyper-scale distributed backends, real-time voice streaming platforms, and durable multi-agent AI operating systems.
- **Current:** AI Tech Lead & Systems Architect at **tawk.to** (~1 Billion conversations/month, 50k+ live voice minutes/mo, sub-500ms voice turn-taking).
- **Previously:** Regional Technical Lead at **Maybank** (Led 4 cross-functional squads, 24 engineers across 5 ASEAN nations, processing **12M transactions in 30 minutes** with 99.99% availability — *Maybank Project Excellence Award*).
- **Core Engineering:** Temporal Durable Execution, LangGraph StateGraph, Model Context Protocol (MCP), WebRTC / LiveKit, Golang, Python 3.12, Kafka, Redis, Distributed Double-Entry Ledgers, and MAS TRM 2024 compliance.

---

### 🌟 Featured Open-Source AI Architecture

#### 1. [durable-agentic-os](https://github.com/manojelumalai/durable-agentic-os) `v1.0.0`
*The Durable Operating System for Agentic AI, Autonomous Financial Desks & Real-Time Voice Streaming.*
- **Temporal-Native Durable Workflows:** Persistent event history guaranteeing zero state loss across worker crashes, restarts, and container evictions.
- **The Autonomous Trading Desk that Never Fails:** Parallel sandboxed backtest fan-out (`asyncio.gather`) and multi-turn trade reasoning.
- **LiveKit WebRTC Voice Bridge:** Sub-500ms voice turn-taking latency profiling with instantaneous VAD barge-in interruptions.
- **Cryptographic Guardrails (HITL):** Halts trades $> \$10,000$ at **0% CPU** via `workflow.wait_condition` until an HMAC-SHA256 signed approval arrives.
- **Two-Tier Semantic Vector Cache & Circuit Breakers:** Exact hash + cosine similarity ($>0.92$) across OpenAI, Claude, and Gemini.
- *Test Coverage:* **28/28 tests passing (88% coverage)**, strict Ruff and Mypy clean.

#### 2. [enterprise-llm-gateway](https://github.com/manojelumalai/enterprise-llm-gateway) `v1.0.0`
*High-Throughput Multi-Provider LLM Gateway with Two-Tier Semantic Vector Caching & Circuit Breakers.*
- Multi-provider router with circuit breakers across OpenAI, Anthropic Claude, and Google Gemini with exponential backoff.
- Two-tier semantic vector cache reducing LLM API token consumption and redundant upstream calls.
- Per-tenant token-bucket rate limiter enforcing TPM / RPM quotas.
- RAG Triad evaluator scoring Context Relevance, Groundedness, and Answer Relevance.
- *Test Coverage:* **14/14 tests passing (89% coverage)**.

#### 3. [agentic-workflow-engine](https://github.com/manojelumalai/agentic-workflow-engine) `v1.0.0`
*Multi-Agent StateGraph Supervisor with Model Context Protocol (MCP) & Cryptographic Approvals.*
- Multi-agent supervisor pattern with dynamic StateGraph dispatch.
- MCP client integration connecting local and remote agent tools over STDIO / SSE.
- Cryptographic human-in-the-loop (HITL) approval gate using HMAC-SHA256 tokens for high-risk operations.
- *Test Coverage:* **11/11 tests passing (81% coverage)**.

---

### 🛠️ Technical Competencies
- **AI & Intelligent Systems:** Temporal Workflows, LangGraph StateGraph, FastMCP, Two-Tier Semantic Caching, vLLM / Continuous Batching, KV Cache Profiling, RAG Triad Evals.
- **Real-Time & Streaming:** WebRTC, LiveKit, Audio Codecs, Sub-500ms Voice Turn-Taking, VAD Barge-In, WebSockets.
- **Distributed Backends & Financial Infrastructure:** Golang, Python 3.12, Java, Apache Kafka (EOS), Redis (Cluster/Lua), Idempotent Gateways, Distributed Double-Entry Ledgers, Saga Pattern, Outbox CDC (Debezium).
- **Governance & Compliance:** Singapore MAS TRM (Notice 644/655), Bank Negara Malaysia (BNM RMiT), High Availability ($99.999\%$, RTO $< 4\text{h}$).
