# 🧠 Vectorless RAG

A lightweight exploration of **Vectorless Retrieval-Augmented Generation (RAG)** using BM25, PageIndex-style hierarchical retrieval, and agentic reasoning — without relying on embeddings or vector databases.

---

## 🚀 Overview

Traditional RAG systems depend on:

* Embeddings
* Vector databases (FAISS, Pinecone, etc.)
* Semantic similarity search

This project explores an alternative approach:

> **Can we build effective RAG systems without embeddings?**

Yes — using:

* BM25 (keyword-based retrieval)
* Document structure (tree-based reasoning)
* Agentic retrieval strategies

---

## 🧩 Key Ideas

* No vector DB required
* No embedding models required
* Works on CPU (lightweight & fast)
* Explainable retrieval process
* Structure-aware document reasoning

---

## 📂 Repository Structure

```id="structure_vrag"
1_vectorless_rag_math.ipynb          → Mathematical intuition behind retrieval
2_rag_vs_vectorless.ipynb            → Comparison with traditional RAG
3_vectorless_rag.ipynb               → Core implementation
4_rag_simple.ipynb                   → Basic RAG baseline
5_pageIndex_chat_quickstart.ipynb    → PageIndex chat interface
6_agentic_retrieval.ipynb            → Agent-based retrieval system
7_vectorless_rag_pageindex.ipynb     → Full PageIndex pipeline
8_pageindex_RAG_simple.ipynb         → Simplified PageIndex RAG
9_vision_RAG_pageindex.ipynb         → Vision-based RAG experiments
```

---

## 📊 What You Learn

* How BM25 retrieval works internally
* Why vector similarity is not always necessary
* How hierarchical document structures improve reasoning
* Agent-based retrieval pipelines
* PageIndex-style LLM reasoning over documents
* Practical alternatives to embedding-based RAG

---

## ⚙️ Installation

```bash id="install_vrag"
pip install -r requirements.txt
```

---

## ▶️ How to Run

Open any notebook:

```bash id="run_vrag"
jupyter notebook
```

Start with:

```
3_vectorless_rag.ipynb
```

---

## 📚 Concept Comparison

| Feature          | Vector RAG | Vectorless RAG (This Repo) |
| ---------------- | ---------- | -------------------------- |
| Retrieval        | Embeddings | BM25 / Structure           |
| DB Required      | Yes        | No                         |
| Compute          | High       | Low                        |
| Explainability   | Low        | High                       |
| Setup Complexity | High       | Simple                     |

---

## 💡 Use Cases

* Lightweight AI systems
* CPU-based environments
* Research on retrieval methods
* Explainable AI pipelines
* Educational RAG experiments

---

## 📌 Key Insight

> Not all retrieval problems require embeddings.
> Structure + lexical signals can often achieve comparable results with far lower complexity.

---

## 📄 Papers / References

* BM25 Information Retrieval Model
* PageIndex hierarchical retrieval concept
* Traditional RAG architectures

---

## 🧠 Author Note

This repository is part of an exploration into building efficient, explainable AI retrieval systems without heavy infrastructure.

---

## ⭐ If you find this useful

Give the repo a star — or don’t, I’m just code.
