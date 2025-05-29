# 🔍 Retrieval-Augmented Generation (RAG) using Shivaay LLM

This repository demonstrates two practical implementations of **Retrieval-Augmented Generation (RAG)** using the **Shivaay LLM API**. RAG enhances the performance of large language models by incorporating relevant external information—either from search results or documents—before generating responses. This helps produce more accurate, context-aware answers.

---

## 📌 rag-basic: Search-Based RAG

### Description
`rag-basic.py` simulates a lightweight RAG pipeline that generates optimized search queries and uses mocked search results as context for answering questions.

### Key Features
-  Generates 3 refined search queries from a user question.
-  Uses a predefined/mock context to simulate retrieved data.
-  Answers the user's question using only the provided context through Shivaay LLM.

### When to Use
Use this when working with a search-based RAG system where you fetch search results or database content externally and want to use that as the input context for an LLM.

---

## 📌 rag-adv: PDF-Based Advanced RAG

### Description
`rag_advanced.py` performs end-to-end document-based RAG using a PDF file. It extracts text, chunks it, ranks the most relevant sections, and then sends those to Shivaay LLM for a contextual response.

### Key Features
-  Parses local or online PDFs to extract clean text.
-  Splits content into manageable chunks with overlap.
-  Selects top-k most relevant chunks based on keyword overlap with the query.
-  Answers the query using the most relevant parts of the document.

### When to Use
Best suited for:
- Answering questions from lengthy documents like reports or research papers.
- Building custom Q&A tools based on proprietary data or files.

---


