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

| Product | Description | Company Size (Valuation/Revenue) | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[MongoDB Atlas](https://www.mongodb.com/products/platform/atlas-vector-search)** | Integrated vector search within the popular NoSQL document database. | **~$15 Billion** ($2.46B Revenue) | Cluster-based: Shared tiers or Dedicated (~$57/mo). | 512MB storage (M0 tier). Shared RAM/vCPU. |
| **[Supabase](https://supabase.com/docs/guides/ai)** | Managed PostgreSQL with pgvector, providing a full backend-as-a-service. | **$10.5 Billion** ($170M ARR) | Project-based: Pro plan from $25/mo (includes 8GB DB). | 500MB DB storage, 50K MAUs, 5GB egress. |
| **[Astra DB](https://www.datastax.com/products/astra)** | Cloud-native Cassandra-based database with integrated vector search. | **$1.6 Billion+** (Acquired by IBM) | Credit-based: $0.37/M reads; $0.62/M writes; $0.25/GB storage. | $25 monthly credit (25GB storage, 25M reads/writes). |
| **[Neon](https://neon.tech/)** | Serverless Postgres with pgvector and autoscaling compute. | **~$1 Billion** (Acquired by Databricks) | Compute-based: $0.106/CU-hour; $0.35/GB storage. $5/mo min. | 0.5GB storage, 100 CU-hours/mo. |
| **[Pinecone](https://www.pinecone.io/)** | Fully managed vector database for high-performance similarity search and RAG. | **$750M+** ($55M ARR) | Usage-based: $0.33/GB storage, $16/M reads, $4/M writes. | 2GB storage, 2M write units, 1M read units/mo. |
| **[Zilliz Cloud](https://zilliz.com/)** | Managed version of Milvus, optimized for massive embedding workloads. | **$600M - $1B** ($49M ARR) | vCU-based: $4 per million vCUs. Dedicated clusters from $99/mo. | 5GB storage (~1M vectors), 2.5M vCUs/mo. |
| **[Qdrant Cloud](https://qdrant.tech/)** | High-performance vector search engine with excellent filtering and Rust efficiency. | **$250M - $500M** ($14M ARR) | Resource-based: Hourly billing for RAM/vCPU (~$10/mo min). | 0.5 vCPU, 1GB RAM, 4GB disk. No CC required. |
| **[Weaviate Cloud](https://weaviate.io/)** | Open-source-first vector database with semantic search and modules. | **$200M** ($21M ARR) | Dimension-based: $0.016 per M dims; $0.25/GiB storage. $45/mo base. | 100K objects, 1GB RAM, 10GB disk. |
| **[Momento Vector](https://www.gomomento.com/services/vector-index)** | Low-latency vector index with throughput-based pricing and no storage fees. | **$150M - $250M** ($10M ARR) | Throughput-based: $0.50/GB for data transfer. | 5GB data transfer (inbound/outbound) per month. |
| **[Upstash Vector](https://upstash.com/products/vector)** | Serverless vector database with low latency and pay-as-you-go pricing. | **$100M - $200M** ($8M ARR) | Request-based: $0.40 per 100K requests; $0.25/GB storage. | 20K queries/mo, 200K max records. |

### Advanced & Specialized Platforms

**Other notable mentions**: SingleStore, Algolia NeuralSearch, and various managed vector services from major cloud providers (AWS, Google Cloud, Azure).

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