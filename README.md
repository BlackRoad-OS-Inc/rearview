<!-- BlackRoad SEO Enhanced -->

# rearview

> Part of **[BlackRoad OS](https://blackroad.io)** — Sovereign Computing for Everyone

[![BlackRoad OS](https://img.shields.io/badge/BlackRoad-OS-ff1d6c?style=for-the-badge)](https://blackroad.io)
[![BlackRoad OS Inc](https://img.shields.io/badge/Org-BlackRoad-OS-Inc-2979ff?style=for-the-badge)](https://github.com/BlackRoad-OS-Inc)
[![License](https://img.shields.io/badge/License-Proprietary-f5a623?style=for-the-badge)](LICENSE)

**rearview** is part of the **BlackRoad OS** ecosystem — a sovereign, distributed operating system built on edge computing, local AI, and mesh networking by **BlackRoad OS, Inc.**

## About BlackRoad OS

BlackRoad OS is a sovereign computing platform that runs AI locally on your own hardware. No cloud dependencies. No API keys. No surveillance. Built by [BlackRoad OS, Inc.](https://github.com/BlackRoad-OS-Inc), a Delaware C-Corp founded in 2025.

### Key Features
- **Local AI** — Run LLMs on Raspberry Pi, Hailo-8, and commodity hardware
- **Mesh Networking** — WireGuard VPN, NATS pub/sub, peer-to-peer communication
- **Edge Computing** — 52 TOPS of AI acceleration across a Pi fleet
- **Self-Hosted Everything** — Git, DNS, storage, CI/CD, chat — all sovereign
- **Zero Cloud Dependencies** — Your data stays on your hardware

### The BlackRoad Ecosystem
| Organization | Focus |
|---|---|
| [BlackRoad OS](https://github.com/BlackRoad-OS) | Core platform and applications |
| [BlackRoad OS, Inc.](https://github.com/BlackRoad-OS-Inc) | Corporate and enterprise |
| [BlackRoad AI](https://github.com/BlackRoad-AI) | Artificial intelligence and ML |
| [BlackRoad Hardware](https://github.com/BlackRoad-Hardware) | Edge hardware and IoT |
| [BlackRoad Security](https://github.com/BlackRoad-Security) | Cybersecurity and auditing |
| [BlackRoad Quantum](https://github.com/BlackRoad-Quantum) | Quantum computing research |
| [BlackRoad Agents](https://github.com/BlackRoad-Agents) | Autonomous AI agents |
| [BlackRoad Network](https://github.com/BlackRoad-Network) | Mesh and distributed networking |
| [BlackRoad Education](https://github.com/BlackRoad-Education) | Learning and tutoring platforms |
| [BlackRoad Labs](https://github.com/BlackRoad-Labs) | Research and experiments |
| [BlackRoad Cloud](https://github.com/BlackRoad-Cloud) | Self-hosted cloud infrastructure |
| [BlackRoad Forge](https://github.com/BlackRoad-Forge) | Developer tools and utilities |

### Links
- **Website**: [blackroad.io](https://blackroad.io)
- **Documentation**: [docs.blackroad.io](https://docs.blackroad.io)
- **Chat**: [chat.blackroad.io](https://chat.blackroad.io)
- **Search**: [search.blackroad.io](https://search.blackroad.io)

---


> RearView — Sovereign vector database. BlackRoad fork of Qdrant. RAG, semantic search, AI memory.

Part of the [BlackRoad OS](https://blackroad.io) ecosystem — [BlackRoad-OS-Inc](https://github.com/BlackRoad-OS-Inc)

---

# RearView — BlackRoad Road Fleet

> **Sovereign vector database.** Fork of [Qdrant](https://github.com/qdrant/qdrant).

---

**RearView** is BlackRoad's sovereign fork of Qdrant — vector similarity search powering RAG, semantic search, and AI memory across the fleet.

## What's Different

- **RAG pipeline** — nomic-embed-text embeddings, academic citations, moral context
- **Memory system** — 36MB ledger indexed for semantic retrieval
- **BlackRoad search** — powers search.blackroad.io semantic queries
- **Fleet-local** — runs on Alice, no cloud vector DB dependency

## Deployment

```bash
# On Alice
# Qdrant runs on ports 6333 (HTTP) and 6334 (gRPC)
curl http://localhost:6333/collections
```

## Collections

| Collection | Vectors | Use |
|-----------|---------|-----|
| blackroad-docs | ~10K | Documentation search |
| blackroad-memory | ~50K | Memory/journal semantic search |
| blackroad-code | ~20K | Code search across 574 repos |

## Upstream

Forked from [qdrant/qdrant](https://github.com/qdrant/qdrant) (Apache 2.0 upstream).
All BlackRoad modifications are proprietary.

---

**BlackRoad OS, Inc.** — Pave Tomorrow.

*Proprietary. All rights reserved.*
