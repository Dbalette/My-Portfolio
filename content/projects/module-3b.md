---
title: "Conversational AI Chatbot with Memory"
date: 2025-04-16
draft: false
weight: 4
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

📘 **Description**

This project implements a dynamic, memory-enabled conversational agent that interacts over multiple turns, reasons through ReAct, and streams its thought process using LangGraph and GPT-4o-mini. Built within a Jupyter Notebook, the assistant simulates natural conversation with embedded search capabilities and message-based memory.

<!--more-->

The chatbot uses LangChain's tool-calling logic with Tavily for real-time web answers, scoped `thread_id` sessions for memory isolation, and a LangGraph agent executor to perform reasoning and retrieval steps transparently.

⸻

### 🔧 Features

- **Agent Executor (LangGraph):** Structured loop for reasoning, tool use, and memory recall.
- **Tavily Tool:** Live web results fetched automatically through natural language queries.
- **Threaded Memory:** Conversation history stored using `MemorySaver` for scoped sessions.
- **Token Streaming:** Displays LLM responses in real time for enhanced UX.
- **Tool Observation:** Logs intermediate thoughts and results for explainability.
- **Session ID Control:** Allows multiple chats without memory overlap using `thread_id`.

⸻

### 💡 Key Insight

> Chatbots become far more powerful when they reason step by step, track what’s been said, and know when to search. This project demonstrates that stateful, tool-augmented chat interfaces are the future of intelligent assistants.

🔗 [View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)
