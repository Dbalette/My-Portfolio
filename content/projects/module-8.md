---
title: "Hospital Operations AI Assistant"
date: 2025-06-08
draft: false
weight: 8
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

📘 **Description**

This module presents an AI-powered assistant designed to support hospital operations at Northwestern Memorial Hospital. Built with LangChain, LangGraph, and GPT-4o-mini, the agent handles multiple roles including triaging cases, analyzing operational metrics, and coordinating recommendations across specialist tools. It simulates a supervisory persona (“Claire”) that routes tasks to sub-agents and synthesizes responses in plain language.

<!--more-->

The project showcases how Retrieval-Augmented Generation (RAG), agent reasoning, and memory persistence can be combined to support complex workflows in regulated, high-stakes environments like healthcare — while preserving traceability and explainability in every step.

⸻

### 🔧 Features

- **Role-Based Agent Design:** Claire delegates tasks to specialist agents (e.g., Financial Planner, Utilization Review).
- **Tool Integration:** Connects to retrieval tools, structured memory, and analytical sub-systems for reporting and triage.
- **Workflow Orchestration:** Uses LangGraph to route and track multi-step interactions across conversation threads.
- **Traceable Decisions:** All recommendations are linked to specific inputs and model responses for transparency.
- **Human-Centric Output:** Final outputs are formatted for hospital leadership and frontline staff alike, emphasizing clarity and actionability.

⸻

### 💡 Key Insight

> AI systems are most valuable in high-stakes domains when they are modular, auditable, and human-facing. This project illustrates how LangGraph agents can be used not just to answer questions, but to assist with operational decisions, workload delegation, and contextual reasoning in complex organizational settings.

🔗 [View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)
