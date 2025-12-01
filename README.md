# 🚀 Retrieval-Augmented Generation (RAG) Workflow in n8n  
**Automated Document Intelligence Using n8n, OpenAI & Pinecone**

This project demonstrates how to build a fully automated Retrieval-Augmented Generation (RAG) system in **n8n** — without writing a backend or managing servers. Using n8n’s visual workflow automation, OpenAI’s embedding models, and Pinecone’s vector database, you can turn unstructured documents into searchable, answer-ready knowledge.

---


---

## 🔍 Features & Workflow Steps

### 1. 📂 Document Ingestion  
Documents are pulled directly from **Google Drive** using the n8n Google Drive node.

### 2. ✂️ Text Splitting  
A **Recursive Character Text Splitter** divides documents into small, context-preserving chunks.

### 3. 📄 Data Loading & Preparation  
A **Data Loader** processes the extracted text and prepares it for embedding.

### 4. 🧠 Embedding Generation  
Chunks are sent to **OpenAI Embeddings API**, generating vector representations.

### 5. 📦 Vector Storage in Pinecone  
Vectors + metadata are stored and indexed in **Pinecone**, enabling semantic search.

### 6. 🤖 AI Agent with Vector Store  
An AI Agent retrieves the most relevant context from Pinecone and produces accurate, grounded answers.

### 7. 💬 Conversational Memory  
Conversation history is stored to provide more natural, human-like interactions.

---

## 🎯 What You Can Build

With this workflow, you can create:

- 🤖 Custom AI Chatbots  
- ❓ Automated Q&A Assistants  
- 🏢 Internal Knowledge Search Tools  
- 📚 Document-Based AI Applications  
- 🔎 Context-Aware Retrieval Systems  

All visually built within **n8n** — no custom backend required.
