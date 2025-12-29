# 🧠 RAG LangGraph Chatbot with Memory

A **production-style Retrieval-Augmented Generation (RAG) chatbot** built using **LangChain, LangGraph, and FAISS**, capable of **context-aware, memory-driven conversations** over a custom knowledge base.

This project demonstrates **real-world AI system design**, combining LLM orchestration, vector search, and conversational memory with a full-stack implementation.

---

## 🚀 Project Overview

This chatbot answers user queries by:
- Retrieving **relevant information from a knowledge base**
- Maintaining **conversation memory across turns**
- Generating **accurate, grounded responses** using an LLM

Unlike basic chatbots, this system uses **LangGraph workflows** to control how retrieval, memory, and generation interact — making it scalable, modular, and production-ready.

---

## ✨ Key Features

- 🔍 **Retrieval-Augmented Generation (RAG)** using FAISS vector search  
- 🧠 **Conversation Memory** for multi-turn contextual understanding  
- 🔗 **LangGraph-based agent workflow** for controlled reasoning  
- 📚 Custom **knowledge base ingestion & indexing**  
- ⚙️ Modular backend + frontend architecture  
- 🌐 Interactive chat UI  

---

## 🛠️ Tech Stack

**AI / ML**
- LangChain
- LangGraph
- FAISS
- LLMs (OpenAI / compatible models)

**Backend**
- Python
- FastAPI (or equivalent API layer)

**Frontend**
- Web-based chat interface (React / JS)

**Data**
- Vector embeddings
- FAISS index
- Document knowledge base

---

## 🧱 System Architecture

```

User → Frontend UI
↓
Backend API
↓
LangGraph Workflow
├── Retrieve relevant vectors (FAISS)
├── Inject conversation memory
└── Generate grounded response (LLM)

````

---

## ⚙️ How It Works

1. **Document Ingestion**
   - Knowledge base files are chunked and embedded.

2. **Vector Indexing**
   - Embeddings are stored in a FAISS index for semantic retrieval.

3. **Query Processing**
   - User query → relevant documents retrieved → memory added → LLM generates response.

4. **Memory Update**
   - Conversation history is stored and reused for future queries.

---

## 📦 Installation & Setup

```bash
git clone https://github.com/ishasingh2704/rag-langgraph-chatbot-memory.git
cd rag-langgraph-chatbot-memory
````

```bash
pip install -r requirements.txt
```

Create a `.env` file:

```env
OPENAI_API_KEY=your_api_key
```

Build the FAISS index:

```bash
python backend/build_index.py
```

Run the backend:

```bash
python backend/app.py
```

Run the frontend:

```bash
cd frontend
npm install
npm start
```

---

## 📌 Use Cases

* AI Knowledge Assistant
* Documentation Q&A Bot
* Customer Support Automation
* Educational Tutor
* Internal Enterprise Chatbot

---

## 📈 Why This Project is relevant

 Demonstrates **RAG architecture**, not just prompt engineering
 Shows **agentic AI workflows** using LangGraph
 Covers **ML + backend + frontend integration**
 Focuses on **memory, scalability, and real-world AI design**
 Aligns with current industry adoption of **LLM systems**

---

## 🔮 Future Enhancements

* Persistent long-term memory (database-backed)
* Multi-user session handling
* Streaming responses
* Model fine-tuning for domain knowledge
* Cloud deployment (Docker / Kubernetes)

---

## 👩‍💻 Author

**Isha Singh**
Computer Science Undergraduate

Interested in **AI/ML, Full-Stack Systems, and Agentic AI**

---

⭐ If you found this project useful, feel free to star the repository!
