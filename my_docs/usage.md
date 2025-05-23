## Usage

- There are two components
    - Backend(FastAPI with Llamaindex)
    - Frontend (Vite+React)

This guide helps you set up and run the Voice-Based Video Search App on your machine.

---

## 🧱 Prerequisites

Ensure you have:

- Python 3.10 or newer
- `ffmpeg` installed (used by `moviepy`)
- A valid API key from [Google AI Studio](https://makersuite.google.com/app) **or** [Cerebras](https://cerebras.net/)

---

## 📦 Install Dependencies

Create a virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```
- `pip install -r requirments.txt`

```
# Core dependencies
fastapi
uvicorn
pydantic
python-multipart
typing-extensions


moviepy
faster-whisper


llama-index
llama-index-embeddings-huggingface
llama-index-llms-openai
llama-index-llms-cohere
llama-index-llms-huggingface
sentence-transformers
faiss-cpu
torch
transformers



# Data processing
numpy
scikit-learn
matplotlib
pandas
```

