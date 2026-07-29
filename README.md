# Vansh Patel

**AI/ML Engineer** — Production GenAI Agents · RAG Retrieval Systems · Reinforcement Learning
M.S. Computer Science (AI & Machine Learning), Stevens Institute of Technology

[LinkedIn](https://linkedin.com/in/vanshpatel1702) · [vanshpatel6996@gmail.com](mailto:vanshpatel6996@gmail.com) · Hoboken, NJ

---

## About

I build production AI systems, not demos. My recent work spans multi-agent orchestration (LangGraph, RAG, Neo4j), production retrieval (LlamaIndex, MongoDB), and applied machine learning (PyTorch, TensorFlow) — each shipped with automated testing, CI/CD, and observability (structured logging, Prometheus, OpenTelemetry), and each with a real, documented bug diagnosis rather than an assumed-reliable system.

Previously a Software Developer at Scale-tech Solutions, building and operating fault-tolerant ML inference APIs in production. Open to full-time **AI/ML Engineer**, **Applied AI Engineer**, **LLM Engineer**, and **Forward Deployed Engineer** roles.

---

## Featured Projects

### [TriageAI](https://github.com/vanshpatel9669/TriageAI) — Multi-Agent LangGraph Triage System
`Python` `LangGraph` `LangChain` `RAG` `Neo4j` `FastAPI` `Docker`

A 5-stage agent pipeline (ingestion → classification → retrieval → drafting → routing) for IT support triage, with tool use, cross-session memory, and context management. Built an evaluation framework across 12,000 tickets/month measuring accuracy and hallucination rate, driving a confidence-based escalation layer projected to cut triage time 75%. Containerized and versioned for reproducible deployment and rollback.

### [Insight-OS](https://github.com/vanshpatel9669/Insight-OS-AI-Decision-Platform) — Production RAG Decision Intelligence Platform
`Python` `FastAPI` `LlamaIndex` `MongoDB` `Docker`

A genuine two-stage retrieval pipeline — embedding search (LlamaIndex + sentence-transformers) narrowing a candidate set, then cross-encoder reranking — over a MongoDB-backed corpus of 50,000 case records. Instrumented with structured logging, Prometheus, and OpenTelemetry; profiled request latency stage-by-stage and root-caused the dominant cost to the vector store's query path. 21 automated tests against real embedding/reranking models, CI running against a live MongoDB service container, optional local-LLM RAG generation.

### [AI Financial Decision System](https://github.com/vanshpatel9669/AI-Financial-decision-System) — Reinforcement Learning Portfolio Engine
`Python` `PyTorch` `stable-baselines3` `Gymnasium` `FastAPI` `Docker`

Designed a Gymnasium environment simulating a regime-switching market and trained PPO/DQN agents for allocation decisions. Diagnosed a real policy-collapse failure mode via action-distribution logging, root-caused it to unnormalized observations, and fixed it — verified by re-running the full benchmark. Benchmarked PPO against DQN across two reward formulations on held-out evaluation seeds; served the trained policy via FastAPI with Pydantic validation and full observability. 30 automated tests, CI/CD.

### [Sentinel](https://github.com/vanshpatel9669/Sentinel-Forecasting-and-Anomaly-Detection-) — TensorFlow Forecasting & Drift-Aware Anomaly Detection
`Python` `TensorFlow` `FastAPI` `Docker`

Built a TensorFlow forecasting model and benchmarked it head-to-head against two statistical baselines on held-out data — it won, measurably. Implemented drift-triggered recalibration: detects a volatility-regime shift in incoming data and automatically refits anomaly-detection thresholds using a standard statistical-process-control tuning rule. Audited the service's own monitoring endpoint, found hardcoded metrics with no measurement behind them, and replaced them with real Prometheus counters plus a permanent regression test. 34 automated tests, CI/CD, matplotlib evaluation visualizations.

---

## Tech Stack

**Languages:** Python, SQL, JavaScript, TypeScript
**AI/ML:** PyTorch, TensorFlow, LangGraph, LangChain, RAG, Reinforcement Learning, Prompt Engineering
**Backend & Infra:** FastAPI, REST APIs, MongoDB, Neo4j, Docker, CI/CD
**Practices:** Evaluation Frameworks, Structured Logging, Observability (Prometheus/OpenTelemetry), Automated Testing

---

## Connect

[LinkedIn](https://linkedin.com/in/vanshpatel1702) · [vanshpatel6996@gmail.com](mailto:vanshpatel6996@gmail.com)
