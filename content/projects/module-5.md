---
title: "Structured RAG with LangGraph"
date: 2025-06-08
draft: false
weight: 6
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

📘 **Description**

This project demonstrates how to build a structured, metadata-aware Retrieval-Augmented Generation (RAG) application using LangChain, LangGraph, and OpenAI’s GPT-4o-mini. Based on the “LLM-Powered Autonomous Agents” blog post by Lilian Weng, the app performs context-aware question answering by combining semantic search, structured query rewriting, and large language models.

Developed as part of the MSDS 442 course at Northwestern University, this project emphasizes structured reasoning, modular control flow, and interpretable document retrieval. LangGraph orchestrates each application step — from query analysis to final response — allowing for step-level transparency, persistence, and real-time streaming.

⸻

### 🔧 Features

- **Web Ingestion:** Loads a public blog post using `WebBaseLoader` and selectively parses HTML using BeautifulSoup filters.
- **Document Chunking:** Splits content into semantically meaningful sections using `RecursiveCharacterTextSplitter` with metadata tags like `"beginning"`, `"middle"`, and `"end"`.
- **Structured Query Analysis:** Uses an LLM to convert raw questions into structured queries with metadata filters via LangChain’s `with_structured_output`.
- **Metadata Filtering:** Retrieves only the most relevant chunks from a vector store using the embedded query and section-specific filters.
- **LangGraph Orchestration:** Manages the entire pipeline through a composable graph structure (`analyze_query → retrieve → generate`) with real-time streaming and Mermaid diagram visualization.
- **Prompt Customization:** Demonstrates prompt control by replacing the default RAG template with a concise, polite, and safety-aware version.

⸻

### 💡 Key Insight

> Building RAG systems isn’t just about plugging in a model — it’s about designing workflows that enable clear reasoning and traceable decisions. This project highlights how LangGraph helps formalize control flow, introduces modular AI steps, and turns LLMs into reliable tools for real-world, query-sensitive applications.

🔗 [View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)
