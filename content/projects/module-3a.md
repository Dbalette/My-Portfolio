---
title: "ChatGPT_Chatbot"
date: 2025-04-16
draft: false
weight: 3
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

📘 **Description**

This project implements a functional memory-enabled chatbot using LangChain, OpenAI’s GPT-4o-mini, and LangGraph's agent orchestration. It demonstrates how agents can reason and act in multiple steps, maintain session-based memory, and integrate with external tools for live information retrieval.

<!--more-->

The chatbot runs entirely in a Jupyter Notebook and supports both single-turn and multi-turn conversations with tool use, showcasing how LangGraph can structure conversational logic around external API access and memory state.

⸻

### 🔧 Features

- **LangGraph Agent Executor:** Manages control flow and decision-making using a ReAct-style loop.
- **Tavily Search Tool:** Allows the agent to fetch live web results during conversation.
- **Threaded Memory:** Uses `MemorySaver` to persist user interactions across chat turns.
- **Tool Use History:** Supports step-by-step breakdowns of tool calls and thought processes.
- **Live Streaming UX:** Streams LLM output in real time for responsiveness.
- **Session Control:** Each chat is scoped to a `thread_id` to preserve or isolate context.

⸻

### 💡 Key Insight

> The true power of conversational AI comes from embedding reasoning, retrieval, and memory into structured workflows. This chatbot is more than a UI — it’s a stateful autonomous agent, built with tools and traceability from the ground up.

🔗 [View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)
