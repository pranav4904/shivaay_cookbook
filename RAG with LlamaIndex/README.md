# 🔍 Retrieval-Augmented Generation (RAG) with LlamaIndex

This guide demonstrates how to use **LlamaIndex** with **Shivaay AI** to build a Retrieval-Augmented Generation (RAG) chatbot. This approach enables your bot to pull factual information from custom documents (like PDFs, text files, and web pages) instead of relying only on its pre-trained model.

---

## ✅ What You’ll Learn

- How to load documents using `SimpleDirectoryReader`
- How to build a vector index using `VectorStoreIndex`
- How to connect LlamaIndex to Shivaay AI via OpenAI-compatible API
- How to perform document-based question answering

---

## 🧰 Requirements

Install dependencies:

```bash
pip install llama-index openai faiss-cpu

