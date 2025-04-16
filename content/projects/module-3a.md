
---
title: "MSDS_Module-3A_ChatGPT_Chatbot"
date: 2025-04-16
draft: false
weight: 1
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

Date: April 16, 2025  
Course: MSDS 442 – Large Language Models  
Tooling: LangChain, LangGraph, OpenAI (GPT-4o-mini), Tavily Search

⸻

📘 **Description**

This project showcases the creation of a stateful, memory-enabled AI agent using the LangGraph framework from LangChain. Built as part of MSDS 442 at Northwestern, this tutorial walks through how to wire up a language model, connect external tools (like search), stream responses, and persist memory across conversation threads — all in one cohesive agent pipeline.

⸻

### 🔧 Features

- **LLM Integration:** GPT-4o-mini via LangChain’s OpenAI wrapper  
- **Tool Calling:** Integrated with Tavily’s search API for live web results  
- **ReAct Agent Framework:** Uses LangGraph’s `create_react_agent()` to reason + act in steps  
- **Memory Management:** Threaded memory via `MemorySaver` for multi-turn conversation flow  
- **Streaming UX:** Live stream of responses and tokens for enhanced interactivity  
- **Conversation Control:** Scoped sessions using `thread_id` to simulate new or continued chats  

⸻

### 💡 Key Insight

> Even simple chatbots gain serious capability when you give them memory and tools. LangGraph’s modular structure makes it easy to go from stateless Q&A to dynamic agents that reason, act, recall, and respond — all while maintaining a clear UX.
