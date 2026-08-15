# 👽 RAG PDFBot - FastAPI + Streamlit

This is a modular Retrieval-Augmented Generation (RAG) application built using **Streamlit** and **FastAPI**, providing a separation between frontend (UI) and backend (logic). This modular architecture helps in scaling, extending, and deploying the bot in real-world environments.

---

## 🔄 Architecture

The application separates the frontend and backend into independent components.

| Feature | Implementation |
|--------|----------------|
| Codebase | Split into `client/` + `server/` |
| PDF Upload | Async FastAPI API |
| Chat | Calls `/chat` API |
| Vectorstore | Controlled by backend |
| Model Options | Dynamically fetched |
| Inspector | Main panel toggle |
| Splitting | `TokenTextSplitter` |
| UX | Responsive, clear, downloadable |
| Extendability | Easy to plug new LLMs and tools |

---

## 🧪 How It Looks

### Demo

![demo-gif](/assets/rag-bot-fastapi.gif)

---

## 🏗️ Architecture

![architecture](/assets/rag-bot-fastapi-architecture.png)

---

## 🚀 Features

- 📁 Upload multiple PDFs and chat with them
- 🔌 Choose from Groq or Gemini as LLM providers
- 🔎 Query inspector for vectorstore transparency
- 🧠 RAG with LangChain + ChromaDB
- 📦 Streamlit frontend, FastAPI backend
- 🧪 Token-based chunking for LLM precision
- 💬 Downloadable chat history
- 🧰 Tools for reset, undo, clear
- 🌐 Fully API-driven interaction

---

<details>
  <summary>🛠️ Tech Stack</summary>

- **Frontend**: Streamlit
- **Backend**: FastAPI
- **LLMs**: Groq & Gemini via LangChain
- **Vector DB**: ChromaDB
- **Embeddings**: HuggingFace & Google GenAI
- **Chunking**: TokenTextSplitter
- **Parsing**: PyPDF
- **Orchestration**: LangChain Retrieval Chain

</details>

---

## 📦 Installation

```bash
git clone https://github.com/GOVINDSANKAR38/RAG-PDFBot.git
cd RAG-PDFBot

Then return here for real-world patterns.

---

Happy building! 🛠️
