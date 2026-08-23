---
title: "Allstate Claim Supervisor Agent (Module 7)"
date: 2025-06-08
draft: false
weight: 10
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

This project simulates an intelligent claim supervisor named *Anna* who manages a team of agents to process auto insurance claims for Allstate. Built with LangChain, LangGraph, OpenAI GPT-4o-mini, and persistent memory, the system evaluates policy status, classifies damage severity, and determines payment outcomes. It features a modular, node-based structure that mirrors real insurance workflows.

<!--more-->

Developed for the MSDS 442 course at Northwestern University, this project highlights how AI agents can be orchestrated into production-grade systems that reason over structured data and delegate tasks across teams, moving beyond chatbots to decision-making frameworks.

⸻

### Features

- **Supervisor Agent:** A human-like assistant named *Anna* delegates tasks to policy, claim, and damage agents.
- **Memory Persistence:** Each agent stores outputs to local files and vector memory for long-term tracking.
- **Damage Classification:** Uses structured prompts to label severity as Minor, Moderate, or Major.
- **Vector Search Retrieval:** Enables retrieval of past decisions and document references.
- **Multi-Agent Workflow:** Implements LangGraph with clear stages: input verification classification decision.
- **BPMN Compatibility:** Designed to align with Business Process Modeling workflows and test cases.

⸻

### Key Insight

> Intelligent agents can be designed not just to chat, but to supervise. This project illustrates how modular LLM agents can handle real business logic, enabling automated workflows for high-volume, rules-based decision environments like insurance.

[View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)
