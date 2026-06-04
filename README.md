# Kuldeep Poonia

> Building production-grade infrastructure tools that solve real problems in distributed systems, observability, and runtime safety.

---

## 🎯 What I Build

I focus on **infrastructure automation, distributed systems, and runtime visibility**. My projects are designed for production use with clean APIs, minimal dependencies, and zero-config deployment.

---

## 🚀 Featured Projects

### 1. **LoadEquilibrium**
**Predictive auto-scaling for Docker & Kubernetes**

An autonomous control system that watches your services, predicts failures before they happen, and scales capacity automatically using control theory (MPC + RL).

- 🔍 No thresholds — uses aircraft-autopilot-grade math to predict problems 60 seconds ahead
- 📊 Live dashboard with failure risk scoring and reasoning feed
- 🏗️ Zero-config: just add one label to your Docker services
- 💾 Works in-memory or with PostgreSQL for persistent history
- 🐳 Kubernetes-ready manifests included

**Repository:** [loadequilibrium](https://github.com/kuldeep-poonia/loadequilibrium)  
**Tech Stack:** Go, React, Prometheus, Docker, Kubernetes  
**Key Feature:** Can run in single container or on K8s with one replica

---

### 2. **Real-Time Causal Inference Engine**
**Root cause analysis from system metrics**

Identifies true root causes from distributed system metrics with safety-aware decision-making. Uses causal inference to distinguish correlation from causation.

- 🎯 Finds actual root causes, not just correlated symptoms
- ⚡ Real-time inference with low latency
- 🛡️ Safety-aware recommendations that don't break things
- 📈 Works with any Prometheus-compatible metrics source

**Repository:** [Real-time-causal-inference-engine](https://github.com/kuldeep-poonia/Real-time-causal-inference-engine)  
**Tech Stack:** Go, Python, Prometheus  
**Use Case:** When you need to know *why* something failed, not just *that* it failed

---

### 3. **Terminal Log Highlighter** (Sentinel)
**Runtime danger detection in terminal logs**

A terminal-native system that preserves your original terminal behavior while detecting and highlighting dangerous runtime signals (crashes, exceptions, timeouts, memory exhaustion) with near-zero latency.

- 👻 Invisible when safe — only highlights actual problems
- ⚡ Near-zero latency — <1ms overhead even under load
- 🎨 Context-aware highlighting based on log severity
- 🔧 Works with any application without code changes

**Repository:** [terminal-log-highlighter](https://github.com/kuldeep-poonia/terminal-log-highlighter)  
**Tech Stack:** Rust, Shell  
**Perfect For:** Development, testing, and production log streams

---

### 4. **LogDrive**
**Real-time runtime visualizer for live terminal logs**

Converts live terminal logs into structured runtime events and traffic simulation. Bridges the gap between raw logs and actionable insights.

- 📺 PTY-based interactive shell with proper terminal handling
- 🔗 Multiline stack trace aggregation
- 💨 Zero-allocation byte-level classification
- 🎛️ Ring-buffer with async pipeline for backpressure

**Repository:** [logdrive](https://github.com/kuldeep-poonia/logdrive)  
**Tech Stack:** Go, TypeScript  
**Status:** Production-grade CLI ingestion foundation

---

## 💡 Common Thread

All these projects share a philosophy:

✅ **Zero-config when possible** — sensible defaults, minimal setup  
✅ **Production-grade** — built to run in real systems, not just demos  
✅ **Visible reasoning** — you can see why the system made a decision  
✅ **Efficient** — designed for production at scale (low overhead, minimal dependencies)  
✅ **Well-documented** — READMEs that actually explain how to use them  

---

## 🛠️ Tech Stack

**Languages:** Go, TypeScript, Rust, Python  
**Infrastructure:** Docker, Kubernetes, Prometheus, PostgreSQL  
**Specialties:** Distributed systems, control theory, causal inference, observability

---

## 📚 Learn More

Each project has comprehensive documentation in its README. Pick one and dive in:

- **Want auto-scaling?** → Start with [LoadEquilibrium](https://github.com/kuldeep-poonia/loadequilibrium)
- **Need root cause analysis?** → Check [Causal Inference Engine](https://github.com/kuldeep-poonia/Real-time-causal-inference-engine)
- **Observability focus?** → Try [Terminal Log Highlighter](https://github.com/kuldeep-poonia/terminal-log-highlighter) or [LogDrive](https://github.com/kuldeep-poonia/logdrive)

---

## 🤝 Get In Touch

Open to collaboration, feedback, and real-world use cases. If you're using these tools in production or have ideas for improvements, let's talk.

---

**Last updated:** 2026-06-04  
*Built for people who need infrastructure that actually works.*
