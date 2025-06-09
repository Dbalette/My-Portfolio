---
title: "Conversational RAG with LangGraph Agents"
date: 2025-06-08
draft: false
weight: 7
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

📘 **Description**

This project extends a Retrieval-Augmented Generation (RAG) pipeline into a stateful, conversational Q&A assistant using LangChain, LangGraph, and OpenAI’s GPT-4o-mini. Developed as part of the MSDS 442 course at Northwestern University, it builds upon the Part 1 implementation by introducing chat history and agentic reasoning capabilities.

This reinforces the principle that AI systems are most powerful when embedded into structured, state-aware workflows — not standalone black boxes. LangGraph offers a clean architecture to reason over conversational history, perform multi-step tool calls, and allow LLMs to act as autonomous decision-makers.

⸻

### 🔧 Features

- **Memory Persistence:** Tracks multi-turn conversations using LangGraph’s `MemorySaver` checkpointing.
- **Chat State as Messages:** Adopts LangChain’s native message format (`user`, `AI`, `tool`) for interoperability.
- **Agent Reasoning (ReAct):** Uses LangGraph’s ReAct-style agent executor to autonomously decide retrieval and reasoning paths.
- **Multi-Step Retrieval:** Agent can issue follow-up queries without user intervention.
- **Visualization:** Includes control flow graphs to inspect execution structure.

⸻

### 💡 Key Insight

> Agents are ideal for dynamic and ambiguous queries. This project illustrates how LLMs can be embedded in intelligent systems that retrieve, reason, and respond across evolving conversations — making them more like collaborative assistants than static tools.

🔗 [View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)
