---
title: "LangGraph Orchestrated RAG Over Nike 10-K"
date: 2025-06-08
draft: false
weight: 7
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

This project demonstrates a LangGraph-orchestrated Retrieval-Augmented Generation (RAG) system for intelligent querying of Nike’s 2023 10-K filing. It extends prior modules by introducing a **graph-based control flow**, allowing the app to analyze questions, retrieve relevant vector data using metadata filters, and generate structured responses, all as composable LangGraph nodes.

<!--more-->

This approach reflects a production-ready design for enterprise AI, combining semantic search, structured reasoning, and orchestration to deliver scalable, transparent question-answering pipelines.

⸻

### Features

- **LangGraph Orchestration:** Constructs a structured execution flow using LangGraph, where each step (query analysis retrieval generation) is defined as a node.
- **Mermaid Diagram Compatibility:** Outputs the graph as a Mermaid diagram for inspection and transparency.
- **Checkpointed Memory:** Supports state management between nodes with LangGraph’s `MemorySaver` for persistence and reproducibility.
- **Metadata-Filtered Search:** Performs section-specific retrievals (e.g., only from “middle” of the document).
- **Modular Design:** Each RAG component, from question parsing to chunk filtering to response generation, is encapsulated as a separate function node.
- **Prompt Customization:** Uses minimal, safety-conscious RAG prompts for controlled output.

⸻

### Key Insight

> Orchestration is the secret to reliable AI systems. LangGraph makes it possible to coordinate retrieval, reasoning, and memory across steps, turning one-off queries into robust workflows and enabling LLMs to act as structured agents in dynamic environments.

[View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)
