# ⚙️ Tech Stack

This section outlines the core technologies used in building the Voice-Based Video Search App, categorized by function.

---

## 🖥️ Frontend

| Technology | Purpose                           |
|------------|------------------------------------|
| **React**  | Frontend framework for building UI |
| **Vite**   | Lightning-fast dev/build tool      |
| **JavaScript** | Programming language for client logic |
| **Tailwind CSS** (optional) | Utility-first CSS framework for design |

---

## 🧠 Backend

| Technology     | Purpose                               |
|----------------|----------------------------------------|
| **FastAPI**    | REST API backend framework (Python)    |
| **Uvicorn**    | ASGI server for running FastAPI        |
| **moviepy**    | Extracts audio from uploaded videos    |
| **whisper** | Transcribes video audio to text       |

---

## 🧮 Embeddings & Vector Search

| Technology               | Purpose                                  |
|--------------------------|-------------------------------------------|
| **Hugging Face Transformers** | Provides `all-MiniLM-L6-v2` embedding model |
| **FAISS**                | High-speed vector similarity search       |

---

## 🧠 LLM & RAG (Retrieval-Augmented Generation)

| Technology  | Purpose                          |
|-------------|-----------------------------------|
| **Gemini 1.5 flash** | LLM for inference |
| **Gemini 2.5 flash** | LLM for inference |
| **Gemini 2.0 flash** | LLM for inference |
| **Llama 3.1 8b** | LLM for inference |
| **Llama 70b** | LLM for inference |

---

## 🎧 Audio & Response Features

| Technology       | Purpose                           |
|------------------|------------------------------------|
| **gTTS / pyttsx3** | Converts response text to speech |

---

## 🛠️ Deployment

| Platform     | Purpose                        |
|--------------|---------------------------------|
| **Docker** |  | Deployment


---

## ✅ Summary

This app is built using free, open-source, and local-first tools to ensure accessibility without reliance on paid APIs or GPUs. The stack is modular and can be extended or optimized as needed.

