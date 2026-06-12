# Awesome-Vector-Databases
## Top Vector Databases Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on High-Performance Vector Search & Embeddings Storage*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** building **Vector Databases**. These specialized databases are optimized for storing, indexing, and querying high-dimensional vector embeddings — essential for semantic search, RAG, recommendation systems, multimodal AI, and agent memory.

**Examples** include Pinecone, Weaviate, Milvus, Qdrant, Chroma, and pgvector (the category leaders). Tools listed here emphasize **scalability**, similarity search performance (ANN), filtering, hybrid search, and integration with LLMs.

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local deployment, full customization, and production use without vendor lock-in — ideal for AI engineers and teams who want data sovereignty and cost control.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS Products](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS Products

### Core Vector Database Platforms

- **[Pinecone](https://www.pinecone.io/)**  
  Fully managed vector database known for simplicity, scale, and production-grade performance with hybrid search.

- **[Weaviate Cloud](https://weaviate.io/)**  
  Open-source-first vector database with strong semantic search, modules, and cloud hosting.

- **[Milvus Cloud](https://milvus.io/)**  
  Cloud version of the popular open-source vector database with high scalability.

### Advanced & Specialized Platforms

**Other notable mentions**: SingleStore, Zilliz Cloud, and various managed vector services.

## Open-Source GitHub Projects

### Dedicated Vector Database Projects

- **[Weaviate](https://github.com/weaviate/weaviate)**  
  Leading open-source vector database with native multimodal support, GraphQL + REST API, modules for LLMs, and excellent hybrid search capabilities.

- **[Milvus](https://github.com/milvus-io/milvus)**  
  Highly scalable open-source vector database designed for massive embedding workloads and similarity search. Widely used in production.

- **[Qdrant](https://github.com/qdrant/qdrant)**  
  High-performance vector search engine with excellent filtering, payload support, and Rust-based efficiency. Great for production RAG.

- **[Chroma](https://github.com/chroma-core/chroma)**  
  Popular open-source embedding database optimized for developer experience and local-to-production RAG applications.

- **[pgvector](https://github.com/pgvector/pgvector)**  
  Open-source PostgreSQL extension that adds vector similarity search to the world's most popular relational database.

- **[LanceDB](https://github.com/lancedb/lancedb)**  
  Modern open-source vector database built on Lance format with strong versioning and zero-copy capabilities.

- **[Faiss](https://github.com/facebookresearch/faiss)**  
  Facebook's industry-standard library for efficient similarity search and clustering of dense vectors.

- **[HNSWlib](https://github.com/nmslib/hnswlib)**  
  Fast approximate nearest neighbor search library implementing Hierarchical Navigable Small World graphs.

- **[Vespa](https://github.com/vespa-engine/vespa)**  
  Open-source big data serving engine with powerful vector search and hybrid ranking capabilities.

- **[Redis Stack (with RediSearch & Vector)](https://github.com/redis/redis)**  
  Redis with official vector search module for real-time vector operations.

### Additional Strong Open-Source Options

- **[Annoy](https://github.com/spotify/annoy)** — Spotify’s approximate nearest neighbors library optimized for memory usage.
- **[ScaNN](https://github.com/google-research/google-research/tree/master/scann)** — Google’s high-performance vector search library.
- **[USearch](https://github.com/unum-cloud/usearch)** — Extremely fast SIMD-accelerated vector search library.
- **[Turbopuffer](https://github.com/turbopuffer/turbopuffer)** — Serverless-scale open-source vector database.
- **[Typesense](https://github.com/typesense/typesense)** — Fast open-source search engine with vector capabilities.
- Many community **Docker + pgvector**, **Chroma**, and **Qdrant** deployment templates.

**Frameworks for building custom solutions**: Combine **pgvector**, **Qdrant**, or **Chroma** with **LlamaIndex**, **LangChain**, and **LangGraph** for complete RAG and agent memory systems.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Performance characteristics (latency, recall, scale) vary significantly by use case and hardware.
- Always evaluate vector databases based on your specific workload (dimensionality, update frequency, query patterns).

---

**Made for AI engineers, RAG developers, data scientists, and LLM application builders.**  
Let's make vector search more accessible, scalable, and open.