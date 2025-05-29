# 🤖 Agentic Retrieval-Augmented Generation (RAG) with Shivaay LLM

This project demonstrates an **Agentic RAG** approach—where an AI agent **plans**, **searches**, **retrieves**, and **reasons** in multiple steps to answer a complex question. The implementation is done using the [Shivaay LLM API](https://futurixai.com).

---

## 🧩 What Is Agentic RAG?

Agentic RAG goes beyond single-prompt RAG by simulating an autonomous agent that:
1. **Plans** how to answer the query by breaking it into subtasks.
2. **Generates sub-queries** for each subtask to perform targeted retrieval.
3. **Retrieves relevant documents** from a vector database (Pinecone) built on indexed knowledge.
4. **Synthesizes a final answer** by reasoning over the retrieved context.

This multi-step reasoning pipeline is ideal for answering **complex, multi-faceted questions**.

---

## 🗂 File Overview

- `agentic_rag.py`: Main script demonstrating the planning → search → retrieval → reasoning pipeline.

---

