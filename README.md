# 📄 Document Intelligence Chatbot (RAG-Based)

## 🚀 Overview

This project is a full-stack AI-powered chatbot that allows users to upload documents (PDF/TXT) and ask questions based on their content.

It uses Retrieval-Augmented Generation (RAG) to provide accurate, context-aware answers along with source citations.

---

## 🧠 Key Features

* 📂 Upload and process documents
* 🔍 Semantic search using vector embeddings
* 🤖 Context-aware Q&A system
* 📑 Source citation for answers
* ⚡ Fast retrieval using ChromaDB

---

## 🛠️ Tech Stack

* Frontend: React.js
* Backend: Flask (Python)
* Vector DB: ChromaDB
* Embeddings: OpenAI / HuggingFace
* LLM: GPT / LLM API

---

## 📌 Use Case

Helps users quickly extract insights from large documents like research papers, reports, and notes.

---

## ⚙️ How It Works

1. Upload document
2. Text is chunked and embedded
3. Stored in vector database
4. User asks query
5. Relevant chunks retrieved
6. LLM generates final answer
