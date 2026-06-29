# Advanced IT Domains — Go Project Series

A collection of hands-on projects exploring five advanced IT domains, each implemented in **Go** and maintained in its own repository. The goal is to build production-grade, idiomatic Go systems that demonstrate depth across modern infrastructure, data, and security engineering.

> **Status:** Actively in development. Only the AI/ML Engineering & LLMOps repository is live today — the remaining four are planned future work.

---

## Repositories

| # | Domain | Repository | Status |
|---|--------|------------|--------|
| 1 | AI/ML Engineering & LLMOps | [llmops-go](https://github.com/sanjog-shrestha/llmops-go) | ✅ Active |
| 2 | Cloud-Native Architecture & Platform Engineering | _coming soon_ | 🔜 Planned |
| 3 | Offensive & Cloud Security | _coming soon_ | 🔜 Planned |
| 4 | Distributed Systems & Data Engineering | _coming soon_ | 🔜 Planned |
| 5 | Site Reliability Engineering (SRE) | _coming soon_ | 🔜 Planned |

> Replace the `#` link in the table and the section below with your actual GitHub URL once the repo is published (e.g. `https://github.com/<username>/llmops-go`).

---

## 1. AI/ML Engineering & LLMOps — `llmops-go` ✅

**Repository:** [llmops-go]((https://github.com/sanjog-shrestha/llmops-go)) _(active)_

Tooling and services for operating large language models in production, written in Go.

**Focus areas:**
- Model serving and inference gateways
- RAG (Retrieval-Augmented Generation) pipelines
- Vector database integration
- Prompt orchestration and routing
- Inference cost, latency, and observability

---

## 2. Cloud-Native Architecture & Platform Engineering 🔜

**Status:** Future work.

Designing distributed, cloud-native systems and internal developer platforms.

**Planned focus areas:**
- Kubernetes operators and controllers (`controller-runtime`)
- Service mesh integration (Istio / Linkerd)
- Serverless workloads
- Internal Developer Platform (IDP) building blocks
- Multi-cloud and observability tooling

---

## 3. Offensive & Cloud Security 🔜

**Status:** Future work.

Security tooling with an emphasis on offensive techniques and cloud workload protection.

**Planned focus areas:**
- Penetration-testing utilities and scanners
- Zero-trust architecture components
- Cloud Security Posture Management (CSPM) checks
- Container and workload security
- Red-team automation helpers

---

## 4. Distributed Systems & Data Engineering 🔜

**Status:** Future work.

High-throughput data systems and distributed-systems primitives.

**Planned focus areas:**
- Stream processing (Kafka / Flink-style pipelines)
- Consensus algorithms (Raft)
- Eventual consistency patterns
- Large-scale storage and data pipelines
- Backpressure and fault tolerance

---

## 5. Site Reliability Engineering (SRE) 🔜

**Status:** Future work.

Tooling for reliability, observability, and resilience at scale.

**Planned focus areas:**
- SLO / SLI definition and tracking
- Chaos engineering experiments
- Observability with OpenTelemetry
- Incident management automation
- Self-healing and resilience automation

---

## Tech Stack

- **Language:** Go (Golang)
- **Tooling:** Go modules, standard library first, minimal external dependencies where practical
- **Testing:** `go test`, table-driven tests
- **CI/CD:** _to be added per repository_

---

## License

Specify a license per repository (e.g. MIT, Apache 2.0).

---

_This is a living document. Links and statuses will be updated as each repository goes live._
