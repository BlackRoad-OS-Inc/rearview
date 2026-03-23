# rearview

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
