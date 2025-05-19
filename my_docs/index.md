# Voice Activated Video Search using RAG

Welcome to the official documentation!

- This page contains the documentation for Voice Activated Video Search using RAG

- To help you understand and use the app effectively, the documentation is divided into the following sections:

- [Tech Stack](tech-stack.md) — All the technologies used in this app.
- [Whisper Statistics](whisper.md)- Whisper model comparison and statistics.
- [Architecture](architecture.md) — Component-level architecture diagram and explanation.
- [Process Flow](process-flow.md) — End-to-end flow from video upload to response.
- [How to Use](usage.md) — Instructions to set up, run, and interact with the app.
- [Different containers created using docker](dockerisations.md) -

> ⚠️ **Before you start:**  
> To use the application, please make sure you have a valid **API key** from either:
> - [Google AI Studio](https://makersuite.google.com/) *(for Gemini)*
> - [Cerebras API Console](https://www.cerebras.net/products/wsc/) *(for Cerebras LLM)*  
>  
> You'll need to enter this key when interacting with the app to enable LLM-based responses.


##  What This App Does

-  Converts speech in videos to text using **Whisper**
-  Generates semantic embeddings with **MiniLM** for deep search
-  Uses Gemini and Cerebras(Llama models) models LLM-based responses
-  Supports multiple video files with timestamped insights
-  Uses **FAISS** to index and search over large transcript databases
-  Allows users to ask questions and get audio + text responses.
-  Uses the **Llamaindex** framework to index and search over large transcript databases.