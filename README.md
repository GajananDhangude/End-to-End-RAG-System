# End-to-End-RAG-System
A production-style Retrieval-Augmented Generation (RAG) system built in a Colab notebook using HuggingFace embeddings, ChromaDB vector store, KNN retrieval, and Groq LLaMA-3 for fast, grounded question answering.
# End-to-End RAG System (Colab Notebook)

This project demonstrates an end-to-end Retrieval-Augmented Generation (RAG) system implemented in a Google Colab notebook. The system retrieves relevant document context using vector similarity search and generates grounded answers using a large language model.

## 🔹 Features
- PDF document ingestion and chunking
- HuggingFace sentence embeddings (MiniLM)
- ChromaDB vector store with KNN similarity search
- API-free local retrieval pipeline
- Groq LLaMA-3 for low-latency answer generation
- Hallucination-controlled prompt design
- Modern LangChain LCEL-based RAG pipeline

## 🔹 Tech Stack
- Python
- LangChain (LCEL)
- HuggingFace Sentence Transformers
- ChromaDB
- Groq (LLaMA-3)
- Google Colab

## 🔹 Workflow
1. Load and chunk documents
2. Generate embeddings and store them in ChromaDB
3. Retrieve top-K relevant chunks using KNN similarity search
4. Inject retrieved context into the LLM prompt
5. Generate grounded answers based on the retrieved context

## 🔹 Why This Project
This project focuses on building a practical, explainable RAG system rather than a toy example. The design cleanly separates retrieval and generation, reflecting real-world AI engineering practices.

## 🔹 Future Work
- Convert notebook to FastAPI backend
- Add conversational memory
- Add source citation in responses
- Dockerize and deploy on cloud

---
