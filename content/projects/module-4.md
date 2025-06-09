---
title: "Semantic Search Over Nike 10-K"
date: 2025-06-08
draft: false
weight: 5
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

📘 **Description**

This project demonstrates how to build a semantic search engine over a real-world corporate financial document (Nike’s 2023 10-K filing) using LangChain, OpenAI’s GPT-4o-mini embeddings, and Chroma as an in-memory vector store. Developed as part of the MSDS 442 course at Northwestern University, it highlights modular design principles for Retrieval-Augmented Generation (RAG) workflows.

More importantly, it reinforces the idea that effective AI systems require structured reasoning and integration layers — not just a chatbot UI. LangChain acts as a framework to formalize interactions between user queries, document retrieval, and language model responses, enabling intelligent, context-aware applications.

⸻

### 🔧 Features

- **PDF Ingestion:** Loads a full-length corporate 10-K filing using `PyPDFLoader`, splitting the document into manageable semantic chunks.
- **Embedding & Storage:** Uses OpenAI’s GPT-4o-mini model to embed chunks and stores them in a Chroma vector store.
- **Semantic Search:** Implements similarity-based querying over the embedded document, returning the most relevant textual evidence.
- **Retriever Construction:** Demonstrates both custom and built-in retrievers for querying across stored vectors.
- **Score Filtering:** Includes optional similarity scoring to assess result quality and confidence.
- **Batch Querying:** Uses LangChain’s `Runnable` interface to support parallel processing of multiple questions.

⸻

### 💡 Key Insight

> AI applications that rely on information retrieval should treat LLMs not as oracles, but as components in a reasoning system. This project shows how to embed, index, and query document content with full transparency, demonstrating how to build interpretable, modular AI tools for enterprise-grade question answering.
🔗 [View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)
