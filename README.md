
 LangChain Gemini 2.5 Starter Notebook

This repository contains a clean, minimal boilerplate for interacting with Google's Gemini 2.5 Flash model using the LangChain orchestration framework. 

 🚀 Overview
The project serves as a foundational "Hello World" smoke test for LLM applications. It demonstrates the fundamental building blocks required to start developing advanced AI agents, chatbots, or data extraction tools.

 🛠️ Key Features Implemented
* Secure Key Management:** Utilizes Google Colab's `userdata` secrets tool to prevent the accidental leakage of private API keys.
* Unified Model Initialization:** Leverages LangChain's modern `init_chat_model` API to seamlessly load the `google_genai:gemini-2.5-flash` model.
* Structured Conversation Flow:** Sets explicit personas and user prompts using LangChain's native `SystemMessage` and `HumanMessage` schemas.

 📋 Prerequisites
To run this notebook, you will need:
* A Google Colab environment.
* A Gemini API Key (stored safely in your Colab Secrets under the key name `GEMINI_API_KEY`).
* The `langchain-google-genai` library installed.
