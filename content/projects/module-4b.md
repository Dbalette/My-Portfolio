---
title: "Semantic Search Over Nike 10-K (Part 2)"
date: 2025-06-08
draft: false
weight: 6
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

This project enhances the Nike 10-K semantic search pipeline by introducing structured metadata filters and query rewriting capabilities. It moves beyond simple similarity search by allowing users to ask targeted questions tied to specific sections of the document (e.g., "beginning", "middle", "end").

<!--more-->

Built with LangChain, GPT-4o-mini, and Chroma, this implementation applies Pydantic schemas to capture structured queries and leverages LangChain’s structured output features for cleaner, more precise retrieval.

⸻

### Features

- **Metadata Tagging:** Adds semantic tags (e.g., `section = beginning`) during document chunking for more controlled retrieval.
- **Structured Query Rewriting:** Converts free-form questions into structured metadata queries using `with_structured_output()` and a custom Pydantic schema.
- **Filtered Retrieval:** Narrows down search results to specific vector subsets based on structured metadata.
- **Chroma Integration:** Demonstrates how to apply metadata filters directly in a vector database.
- **Improved RAG Precision:** Reduces noise and boosts relevance for complex enterprise documents.

⸻

### Key Insight

> Structured retrieval is the missing link between raw vector search and truly useful AI. By adding metadata and rewriting queries to align with document structure, you increase both precision and interpretability, two key traits of trustworthy AI systems.

[View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)
