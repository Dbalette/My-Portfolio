---
title: "Virtual Buffett: AI Investment Advisor"
date: 2025-06-08
draft: false
weight: 10
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

📘 **Description**

This project introduces a custom-built AI agent inspired by Warren Buffett’s investing principles. Named “Virtual Buffett,” the assistant integrates LangChain, LangGraph, Milvus vector search, and OpenAI’s GPT-4o-mini. Developed for the MSDS 442 course at Northwestern University, the agent retrieves information from Buffett’s shareholder letters and offers context-aware investment insights using a Buffett-style persona.

<!--more-->

The assistant blends long-term memory (Milvus), real-time tools (like FRED and Tavily), and a custom persona to emulate Buffett’s plainspoken wisdom and investment philosophy — making it suitable for financial education, decision support, and investor engagement use cases.

⸻

### 🔧 Features

- **Buffett Persona:** Customized prompt engineering using 15 distilled Buffett principles.
- **Vector Search with Milvus:** Embeds and indexes all shareholder letters from 1977–2023.
- **Tool Use:** Includes FRED API for economic data, Tavily for web results, and FMCSA lookup for fundamentals.
- **Long-Term Memory:** Stores structured conversation history using SQLite + vector metadata.
- **Modular Architecture:** Built using LangGraph to control reasoning over tools, memory, and output.
- **Progress Visualization:** Includes dynamic progress bars and conversational threading with memory awareness.

⸻

### 💡 Key Insight

> Virtual Buffett demonstrates how an LLM-based agent can emulate human investment reasoning by retrieving real-world evidence, applying structured principles, and offering interpretable, long-term-focused responses. The project shows that AI personas built on domain-specific corpora can deliver personalized, expert-level guidance — without hallucination.

🔗 [View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)
