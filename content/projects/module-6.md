---
title: "Conversational RAG with LangGraph Agents"
date: 2025-06-08
draft: false
weight: 7
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

📘 **Description**

This project extends a Retrieval-Augmented Generation (RAG) pipeline into a stateful, conversational assistant using LangChain, LangGraph, and OpenAI’s GPT-4o-mini. Designed for the MSDS 442 course at Northwestern University, it builds on previous modules by introducing agent reasoning, memory persistence, and multi-step retrieval workflows.

<!--more-->

This reinforces the principle that AI systems are most powerful when embedded into structured, state-aware workflows — not standalone black boxes. LangGraph offers a clean architecture to reason over conversational history, perform multi-step tool calls, and allow LLMs to act as autonomous decision-makers.

⸻

### 🔧 Features

- **Memory Persistence:** Tracks multi-turn conversations using LangGraph’s `MemorySaver` checkpoints.
- **Chat State as Messages:** Uses LangChain’s message schema (`user`, `AI`, `tool`) for clean session tracking.
- **Agent Reasoning (ReAct):** Implements LangGraph’s ReAct-style executor to dynamically decide when and how to retrieve and respond.
- **Multi-Step Retrieval:** Empowers the agent to issue follow-up queries without requiring further user input.
- **Visualization:** Supports generation of Mermaid-compatible control flow graphs to inspect reasoning structure.

⸻

### 💡 Key Insight

> Agents are ideal for dynamic and ambiguous queries. This project illustrates how LLMs can be embedded in intelligent systems that retrieve, reason, and respond across evolving conversations — making them more like collaborative assistants than static tools.

🔗 [View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)
