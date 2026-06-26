<div align="center">
  <img src="assets/banner.svg" alt="Awesome Vector Databases Banner" width="100%">

  # Awesome Vector Databases 🚀
  
  **A curated list of high-performance Vector Databases, SaaS products, and Open-Source projects.**
  
  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/ishandutta2007/awesome-awesome-awesome)
  [![Stars](https://img.shields.io/github/stars/ishandutta2007/Awesome-Vector-Databases?style=for-the-badge&color=ffd700)](https://github.com/ishandutta2007/Awesome-Vector-Databases/stargazers)
  [![Forks](https://img.shields.io/github/forks/ishandutta2007/Awesome-Vector-Databases?style=for-the-badge&color=38BDF8)](https://github.com/ishandutta2007/Awesome-Vector-Databases/network/members)
  [![License](https://img.shields.io/github/license/ishandutta2007/Awesome-Vector-Databases?style=for-the-badge&color=818CF8)](LICENSE)
  [![Last Updated](https://img.shields.io/badge/Last%20Updated-June%202026-brightgreen?style=for-the-badge)](https://github.com/ishandutta2007/Awesome-Vector-Databases/commits/main)
<a href="https://github.com/ishandutta2007">
  <img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow&style=for-the-badge&logo=github&logoColor=white" alt="Github"/>
</a>

  ---
  
  <p align="center">
    <a href="#saas-products">SaaS Products</a> •
    <a href="#open-source-github-projects">Open-Source</a> •
    <a href="#why-vector-databases">Why Vector DBs?</a> •
    <a href="#contributing">Contributing</a>
  </p>

  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%">
</div>

## 🌟 Overview

Welcome to the **Awesome Vector Databases** repository! 📚 This is the ultimate collection of specialized databases optimized for **storing, indexing, and querying high-dimensional vector embeddings**. 

Whether you are building a **Retrieval-Augmented Generation (RAG)** system, a recommendation engine, or multimodal AI agents, choosing the right vector store is critical for performance and scalability. ⚡

> **SEO Keywords:** Vector Database, RAG, Embeddings, Semantic Search, Similarity Search, LLM Memory, AI Infrastructure, Vector Search Engine, Milvus, Pinecone, Weaviate, Qdrant, Chroma, pgvector.

---

## 🏗️ Why Vector Databases?

Vector databases are the "memory" of modern AI. Unlike traditional relational databases, they are designed to:
- 🔍 **Perform Similarity Search:** Find the "nearest neighbors" in high-dimensional space.
- 🚀 **Scale to Billions of Vectors:** Efficiently handle massive embedding datasets.
- 🧠 **Power AI Agents:** Provide long-term memory for LLMs.
- 📂 **Support Hybrid Search:** Combine keyword search with semantic search.

---

## 📊 SaaS Products (Managed Services)

### 💎 Core Vector Database Platforms

| Product | Description | Company Size | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[MongoDB Atlas](https://www.mongodb.com/products/platform/atlas-vector-search)** | Integrated vector search in NoSQL. | **~$15B** | Cluster-based | 512MB storage (M0) |
| **[Supabase](https://supabase.com/docs/guides/ai)** | Managed PostgreSQL with pgvector. | **$10.5B** | $25/mo Pro | 500MB DB storage |
| **[Astra DB](https://www.datastax.com/products/astra)** | Cloud-native Cassandra-based. | **$1.6B+** | Credit-based | $25/mo credit |
| **[Neon](https://neon.tech/)** | Serverless Postgres with autoscaling. | **~$1B** | $5/mo min | 0.5GB storage |
| **[Pinecone](https://www.pinecone.io/)** | High-performance managed vector DB. | **$750M+** | Usage-based | 2GB storage |
| **[Zilliz Cloud](https://zilliz.com/)** | Managed version of Milvus. | **$600M+** | vCU-based | 5GB storage |
| **[Milvus](https://milvus.io/)** | Highly scalable vector database designed for massive embedding workloads and similarity search. | **$600M+** | vCU-based | 5GB storage |
| **[Qdrant Cloud](https://qdrant.tech/)** | Rust-based efficiency. | **$250M+** | Hourly billing | 1GB RAM Free |
| **[Weaviate Cloud](https://weaviate.io/)** | Semantic search first. | **$200M** | Dimension-based | 1GB RAM Free |
| **[Momento Vector](https://www.gomomento.com/services/vector-index)** | Low-latency serverless index. | **$150M+** | Throughput-based | 5GB transfer/mo |
| **[Upstash Vector](https://upstash.com/products/vector)** | Serverless pay-as-you-go. | **$100M+** | Request-based | 20K queries/mo |
| **[ChromaDB](https://www.trychroma.com/)** | Developer-friendly embedding database optimized for RAG and local-to-production AI applications. | **$75M** | Usage-based | Free $5 credit |

  
---

## 📂 Open-Source GitHub Projects

### 🛠️ Dedicated Vector Databases

- **[Weaviate](https://github.com/weaviate/weaviate)** 🏆  
  Native multimodal support, GraphQL + REST, and excellent hybrid search.
  
- **[Milvus](https://github.com/milvus-io/milvus)** ☁️  
  Highly scalable, designed for massive embedding workloads.
  
- **[Qdrant](https://github.com/qdrant/qdrant)** 🦀  
  Rust-based, high performance with rich filtering and payload support.
  
- **[Chroma](https://github.com/chroma-core/chroma)** 🎨  
  Developer-first, perfect for local-to-production RAG apps.
  
- **[pgvector](https://github.com/pgvector/pgvector)** 🐘  
  The industry standard for vector search in PostgreSQL.
  
- **[LanceDB](https://github.com/lancedb/lancedb)** ⚡  
  Modern, built on Lance format with zero-copy capabilities.

- **[Faiss](https://github.com/facebookresearch/faiss)**  🦀  
  Facebook’s industry-standard library for efficient similarity search and clustering of dense vectors.

- **[HNSWlib](https://github.com/nmslib/hnswlib)**  🎨  
  Fast approximate nearest neighbor search library implementing Hierarchical Navigable Small World graphs.

- **[Vespa](https://github.com/vespa-engine/vespa)**  ☁️  
  Big data serving engine with powerful vector search and hybrid ranking capabilities.

- **[Redis Stack (RediSearch + Vector)](https://github.com/redis/redis)**  🐘  
  Redis with official vector search module for real-time vector operations and caching.

### 🐘  Additional Strong Open-Source Options

- **[Annoy](https://github.com/spotify/annoy)** — Spotify’s approximate nearest neighbors library optimized for memory usage.
- **[ScaNN](https://github.com/google-research/google-research/tree/master/scann)** — Google’s high-performance vector search library.
- **[USearch](https://github.com/unum-cloud/usearch)** — Extremely fast SIMD-accelerated vector search library.
- **[Turbopuffer](https://github.com/turbopuffer/turbopuffer)** — Serverless-scale open-source vector database.
- **[Typesense](https://github.com/typesense/typesense)** — Fast open-source search engine with vector capabilities.
- **[ClickHouse](https://github.com/ClickHouse/ClickHouse)** with vector search extensions.
- Many community **Docker + pgvector**, **Chroma**, and **Qdrant** deployment templates.
  

### 📚 Specialized Libraries

- **[Faiss](https://github.com/facebookresearch/faiss)** — Facebook's library for dense vector similarity search.
- **[HNSWlib](https://github.com/nmslib/hnswlib)** — Fast HNSW graph implementation.
- **[Vespa](https://github.com/vespa-engine/vespa)** — Big data serving engine with powerful ranking.
- **[Redis Stack](https://github.com/redis/redis)** — Real-time vector search in Redis.

---

##  Star History
<div align="center">
<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Vector-Databases&type=date&legend=bottom-right">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Vector-Databases&type=date&theme=dark&legend=bottom-right" />
<source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Vector-Databases&type=date&legend=bottom-right" />
<img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Vector-Databases&type=date&legend=bottom-right" />
</picture>
</a>
</div>

---

## 🤝 Contributing

Contributions are what make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**. 💖

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## ⚖️ Disclaimer

- This list is **community-curated** and not exhaustive.
- Performance varies by use case. Always benchmark with your own data! 📊

<div align="center">
  <img src="assets/logo.svg" alt="Awesome Vector Databases Logo" width="100">
  <p>Made with ❤️ for the AI community</p>
</div>
