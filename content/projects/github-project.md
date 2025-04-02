---
title: "MSDS_Module-1_ChatGPT_Integration-Translator.ipynb"
date: 2025-04-01
draft: false
link: "https://github.com/Dbalette/MSDS_Class_Work"
---

📘 **Description**  
This project demonstrates a modular approach to building a multilingual translator using the LangChain framework and OpenAI’s GPT-4o-mini model. Designed for the MSDS 442 course at Northwestern University, this script showcases secure API integration, prompt engineering, and real-time language translation using large language models.

🔧 **Features**  
- **Secure Environment Setup**: Uses `os` and `getpass` to securely handle API keys for OpenAI, LangChain, and Tavily, avoiding hard-coded credentials.  
- **LLM Integration**: Initializes a GPT-4o-mini chat model via LangChain’s `ChatOpenAI` class for efficient, conversational interactions.  
- **Prompt Engineering**: Dynamically constructs system and user prompts using LangChain’s `PromptTemplate`, guiding the model to translate text between languages.  
- **Interactive Workflow**: Accepts user-defined languages and phrases, fills the prompt templates with actual values, and invokes the model.  
- **Clear Output**: Displays both the final prompt structure and the model’s translation, providing full transparency into the LLM interaction.

🔗 [View the source code on GitHub](https://github.com/Dbalette/MSDS_Class_Work)
