# PDF-analyser
# 📄 Intelligent Document Q&A Chatbot using RAG

## 🚀 Project Overview

This project is an AI-powered chatbot that allows users to upload PDF documents and ask questions based on the content. It uses **Retrieval-Augmented Generation (RAG)** to provide accurate and context-aware answers.

---

## 🧠 Key Features

* 📂 Upload PDF documents dynamically
* 🔍 Extract and process document content
* 🧩 Smart text chunking for efficient retrieval
* 📊 Semantic search using vector embeddings
* 🤖 AI-generated answers using LLM
* 💬 Chat-like interaction with memory support
* ⚡ Fast and accurate responses

---

## 🛠️ Tech Stack

* Python
* LangChain
* FAISS (Vector Database)
* Hugging Face Transformers
* Streamlit (for UI)

---

## ⚙️ How It Works

1. User uploads a PDF
2. PDF is converted into text
3. Text is split into smaller chunks
4. Chunks are converted into embeddings
5. Stored in FAISS vector database
6. User asks a question
7. Relevant chunks are retrieved
8. LLM generates answer based on context

---

## 🧩 Project Architecture

```
User Input → PDF Upload → Text Splitting → Embeddings → FAISS
       ↓
   Query → Similarity Search → Context Retrieval → LLM → Answer
```

---

## 📦 Installation

```bash
pip install langchain faiss-cpu sentence-transformers transformers streamlit pypdf
```

---

## ▶️ Usage

Run the Streamlit app:

```bash
streamlit run app.py
```

---

## 📌 Example

**Input Question:**

```
What is this document about?
```

**Output:**

```
The document discusses...
```

---

## 🔥 Key Concepts Used

* Retrieval-Augmented Generation (RAG)
* Embeddings & Vector Search
* Prompt Engineering
* Context Window Optimization

---

## ⚡ Future Improvements

* Support for multiple PDFs
* Better LLM models (LLaMA / APIs)
* Improved UI design
* Deployment on cloud
* Voice-based interaction

---

## 🎯 Resume Description

**"Developed an AI-powered document question-answering system using RAG, enabling users to upload PDFs and receive context-aware responses using LLMs."**

---

## 🙌 Acknowledgment

This project demonstrates practical implementation of modern LLM applications combining retrieval systems and generative AI.

---

## 📬 Contact

For any queries or collaboration:

* Name: Swathi
* Role: AIML Student | Aspiring AI Engineer

---
