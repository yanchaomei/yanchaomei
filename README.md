# Chaomei Yan

**Systems infrastructure × AI inference × Agent infrastructure.**

I work at the intersection of low-level systems and large-scale AI. My background is in distributed databases, storage engines, and disaggregated memory systems. Currently, I'm focused on making LLM inference faster and building the infrastructure layer for AI agents.

CS grad student at USTC. Open-source contributor. Builder.

---

### Now

- Optimizing **KV Cache scheduling** for large model inference (contributing to [Mooncake](https://github.com/kvcache-ai/Mooncake))
- Exploring **video generation / multimodal inference** acceleration
- Building infrastructure for **AI agents** — memory, retrieval, orchestration
- Researching **disaggregated memory** architectures (CXL, PMEM, RDMA)

### Technical Themes

```
Systems Layer              AI Infrastructure           Frontier
─────────────────          ─────────────────           ─────────────────
Storage engines            LLM inference optimization  Agent memory systems
KV stores (LSM / B-Tree)  KV Cache scheduling         Retrieval acceleration
Transaction processing     Distributed training        Multimodal agents
Disaggregated memory       Video generation systems    Research agents
RDMA / CXL / PMEM         Serving infrastructure      Agentic workflows
```

### Open Source

Contributions to production infrastructure used at scale:

| Project | What I Worked On |
|---------|-----------------|
| [**RocksDB**](https://github.com/facebook/rocksdb) | Storage engine performance optimization |
| [**Mooncake**](https://github.com/kvcache-ai/Mooncake) | Transfer engine, KVCache scheduling for LLM serving |
| [**Apache Kvrocks**](https://github.com/apache/kvrocks) | Storage engine internals |
| [**OpenMLDB**](https://github.com/4paradigm/OpenMLDB) | Database kernel for ML feature platform |
| [**ColossalAI**](https://github.com/hpcaitech/ColossalAI) | Distributed training framework |
| [**Kmesh**](https://github.com/kmesh-net/kmesh) | eBPF-based kernel-native service mesh |
| [**LightGBM**](https://github.com/microsoft/LightGBM) | ML framework contributions |

### Selected Projects

- **[Mooncake KVCache](https://github.com/kvcache-ai/Mooncake)** — Working on the serving platform behind Kimi. Focused on transfer engine and KV Cache disaggregation for efficient LLM inference.
- **[LevelDB-BF-Index](https://github.com/yanchaomei/LevelDB-BF-Index)** — Bloom filter index optimization for LSM-tree based storage.
- **[3R-Memory-Manager](https://github.com/yanchaomei/3R-Memory-Manager)** — Custom OS memory management with a novel 3R allocation strategy. National OS competition project.

### What I Care About

- **Leverage over labor.** I prefer building systems that multiply output — automation, good abstractions, AI-augmented workflows. Not a fan of scaling through headcount.
- **Research that ships.** Theory matters when it changes how systems work in practice. I want to close the gap between papers and production.
- **Infrastructure taste.** The best infra is invisible. I care about clean interfaces, minimal abstractions, and systems that degrade gracefully.

### Reach Me

- Email: [782294150@qq.com](mailto:782294150@qq.com)
- Site: [yanchaomei.github.io](https://yanchaomei.github.io)

---

<sub>Building systems that think — from storage engines to intelligent agents.</sub>
