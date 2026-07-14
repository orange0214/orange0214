### Hi, I'm Junchen He

**About Me**

I focus on building scalable backend systems and practical LLM/RAG applications.  
My work emphasizes system design, data processing, vector search, and reliable infrastructure for AI-driven applications.

**Selected Projects**

**VectorKV** `C++` `Vector Database` `HNSW` `WAL` `CMake`

- Built an in-memory vector database in C++ with insert, delete, metadata storage, and top-k similarity search.
- Implemented exact brute-force search and multi-layer HNSW approximate nearest neighbor search with configurable search parameters.
- Added WAL-based crash recovery, snapshot persistence, checkpointing, and recovery tests.
- Developed benchmark tooling to measure QPS, P50/P95/P99 latency, and Recall@K against brute-force ground truth.

**HackerNews Chinese** `FastAPI` `RAG` `LangChain` `Supabase`

- Built an automated content ingestion pipeline for Hacker News articles.
- Implemented LLM-based summarization and Chinese translation workflows.
- Integrated Supabase vector retrieval to support semantic search across indexed content.
