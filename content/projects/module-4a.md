---
title: "Semantic Search Over Nike 10-K (Part 1)"
date: 2025-06-08
draft: false
weight: 5
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

📘 **Description**

This project demonstrates how to build a basic semantic search engine over a real-world 10-K corporate filing. It serves as the foundation for more advanced retrieval-augmented generation (RAG) systems, showcasing how to move from unstructured PDF text to meaningful, queryable insights.

<!--more-->

Developed for the MSDS 442 course at Northwestern, this first iteration emphasizes core skills in document ingestion, embedding, and vector similarity querying using LangChain and GPT-4o-mini.

⸻

### 🔧 Features

- **PDF Ingestion:** Uses `PyPDFLoader` to extract and structure raw text from Nike’s 10-K filing.
- **Chunking:** Splits content into manageable pieces using `RecursiveCharacterTextSplitter`.
- **Embedding & Storage:** Transforms text into embeddings with OpenAI and stores them in a Chroma vectorstore.
- **Semantic Search:** Supports question-based search with ranked similarity scores.
- **Retriever Construction:** Compares default and custom retriever approaches for document relevance.
- **Batch Querying:** Demonstrates LangChain’s `Runnable` pipelines for efficient multi-query handling.

⸻

### 💡 Key Insight

> AI applications that rely on information retrieval should treat LLMs not as oracles, but as reasoning layers on top of curated memory. This project shows how to build that memory effectively.

🔗 [View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)
