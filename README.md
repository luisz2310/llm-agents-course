# 🧠 LLMs, Agents & AI Systems — Complete Learning Path

A structured, engineering-focused course to understand **LLMs, Agents, RAG, MCP, and production AI systems** from fundamentals to advanced architectures.

This course is designed for developers who already know programming (Java / TypeScript / Python) and want to build **real-world AI agents and systems**, not just use APIs.

---

# 🎯 Goal of the Course

By the end of this course, you will be able to:

- Understand how LLMs actually work (internally, not just API usage)
- Build local LLM systems using Ollama
- Design and implement AI Agents from scratch
- Work with MCP (Model Context Protocol)
- Build RAG systems (simple → advanced → graph-based)
- Use frameworks like LangChain, LangGraph, and LlamaIndex
- Design multi-agent systems and workflows
- Deploy production-ready AI systems (cloud + local hybrid)
- Understand model selection, quantization, and performance tradeoffs

---

# 🧱 Course Structure

## 🧠 PHASE 0 — CORE THEORY (FOUNDATION)

### 0.1 LLM Fundamentals
- Next-token prediction
- Probability distributions over tokens
- Sampling (deterministic vs stochastic)
- Pattern completion behavior (not reasoning)

### 0.2 Tokens & Language Structure
- Tokenization (BPE / SentencePiece)
- Subword units (not words)
- Frequency-based learning
- No grammar understanding (emergent structure)
- Context window limitations

### 0.3 Sampling
- Temperature
- Top-K sampling
- Top-P (nucleus sampling)
- Deterministic vs creative outputs
- Stability vs randomness tradeoffs

### 0.4 Training Lifecycle
- Pre-training
- Instruction tuning
- Fine-tuning
- Alignment vs capability separation

---

## 🧱 PHASE 1 — LOCAL LLM SETUP (OLLAMA FIRST)

### 1.1 Setup
- Install Ollama
- Run local models

### 1.2 Local Inference API
- REST API usage
- Streaming responses
- Latency considerations

### 1.3 Model Types
- Base models
- Instruction-tuned models
- Code models
- Agent-optimized models (e.g. Hermes-style)

### 1.4 Model Scaling
- 3B / 7B / 13B / 70B models
- Tradeoffs: speed vs intelligence vs memory

### 1.5 Quantization
- FP16 / INT8 / INT4
- GGUF format
- Compression vs quality tradeoff

### 1.6 Model Selection Strategy
- Task-based model selection
- Local vs cloud decision logic

---

## 🧪 PHASE 2 — FIRST EXPERIMENTS

- Temperature experiments
- Output randomness analysis
- JSON stability testing
- Prompt sensitivity tests

---

## 🧠 PHASE 3 — MODEL BEHAVIOR

- Attention and relevance intuition
- Why models “focus” on certain tokens
- Hallucination mechanisms
- Context dilution
- Failure modes

---

## 🧠 PHASE 4 — EMBEDDINGS & SEMANTIC SPACE

- Vector representations of text
- Feature matrix representation
- Cosine similarity
- Euclidean distance
- Semantic similarity vs lexical similarity
- Text clustering and search

---

## 🧠 PHASE 5 — TRANSFORMER ARCHITECTURE

- Self-attention mechanism
- Contextual token relationships
- Attention = relevance scoring system

---

## 🤖 PHASE 6 — AGENT FUNDAMENTALS

- Agent loop (Observe → Think → Act → Repeat)
- Tool usage design
- Input/output contracts
- State management

---

## 🧪 PHASE 7 — AGENT EXPERIMENTS

- Simple calculator agent
- Multi-step reasoning
- Tool chaining systems

---

## 🧱 PHASE 8 — STRUCTURED OUTPUTS

- JSON schema enforcement
- Output validation
- Retry mechanisms
- Tool hallucination prevention

---

## 🔁 PHASE 9 — REACT AGENTS

- Reason → Act → Observe loop
- Iterative reasoning systems
- Tool orchestration logic

---

## 🧠 PHASE 10 — MEMORY SYSTEMS

- Short-term memory
- Long-term memory
- Vector databases (Redis / Postgres / Vector DBs)

---

## 📚 PHASE 11 — RAG SYSTEMS

- Embedding-based retrieval
- Naive RAG
- Hybrid RAG
- Agentic RAG
- Graph RAG
- Chunking strategies
- Reranking

---

## 🔌 PHASE 12 — MCP (MODEL CONTEXT PROTOCOL)

- Tool abstraction layer
- Tool registry
- Execution pipeline
- Security and sandboxing

---

## 🤖 PHASE 13 — MULTI-AGENT SYSTEMS

- Hierarchical agents
- Peer-to-peer agents
- Supervisor architectures
- Message passing systems
- Shared memory systems

---

## 🧰 PHASE 14 — FRAMEWORKS

- LangChain
- LangGraph
- LlamaIndex

---

## ⚙️ PHASE 15 — AUTOMATION (n8n)

- Workflow automation
- Triggers and actions
- API integrations
- Webhooks

---

## 🚀 PHASE 16 — ADVANCED AGENTS

- Agent OS concepts
- Coding agents (Claude Code / Codex-style systems)
- Self-improving agents

---

## ☁️ PHASE 17 — PRODUCTION SYSTEMS

- AWS Bedrock
- Cloud LLMs
- Hybrid architectures (local + cloud)
- Scaling strategies
- Observability (logs, traces, metrics)

---

## 🧠 PHASE 18 — FINAL SYSTEM DESIGN

- Full AI system architecture:
  - LLM + Tools + Memory + RAG + MCP
- AI Operating System concept
- Multi-agent orchestration systems

---

# 🚀 OUTCOME

You will be able to:

- Build production-ready AI agents
- Design RAG systems
- Create multi-agent architectures
- Deploy hybrid AI systems (local + cloud)
- Understand and control LLM behavior at a deep level
