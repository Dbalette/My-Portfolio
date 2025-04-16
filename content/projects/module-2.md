---
title: "MSDS_Module-2_LLM_Integration_and_Workflows.ipynb"
date: 2025-04-08
draft: false
weight: 2
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

📘 **Description**
   
This project builds upon the concepts introduced in Module 1 by demonstrating a modular agent-based approach to leveraging large language models (LLMs) for multi-step problem-solving tasks. Designed for the MSDS 442 course at Northwestern University, the script showcases the integration of OpenAI’s GPT-4o-mini model within an agent framework that follows a structured reasoning process: Thought, Action, PAUSE, Observation. The agent handles complex tasks by invoking different actions, such as retrieving data or performing calculations, while maintaining clarity through explicit reasoning workflows.  

This project emphasizes the importance of creating well-structured workflows that allow AI agents to reason and act beyond simple queries, such as calculating the combined weight of multiple dogs. It highlights how tools like LangChain can be used to connect agent logic to backend LLMs, enabling the efficient execution of multi-step tasks.  


<!--more-->
---

### 🔧 Features

- **LLM Integration:** Uses OpenAI’s GPT-4o-mini model, integrated into a custom agent framework for conversational interactions and problem-solving.
- **Agent Workflow:** Implements a four-step reasoning loop (Thought, Action, PAUSE, Observation), where the agent reflects, performs actions, and then outputs results based on observation.
- **Tool Use:** Dynamically retrieves or calculates information based on user input.
- **Transparent Output:** Shows the agent’s logic and steps at each stage.
- **Complex Task Handling:** Solves multi-step problems through sequential reasoning.

### 💡 Key Insight

> LLMs become significantly more powerful when paired with structured agent workflows, enabling clear, multi-step problem solving—not just single-response answers.
   
🔗 [View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)


