

---

# Generative AI & LangChain Laboratory

This repository contains a structured curriculum of Jupyter Notebooks exploring the development and optimization of AI applications using **LangChain** and **Retrieval-Augmented Generation (RAG)**.

## 📂 Notebook Overview

### 1. LangChain Foundations

* **Concepts:** Introduction to the LangChain framework, model stochasticity (Temperature), and System/Human/AI message roles.
* **Architecture:** Implementation of **LCEL (LangChain Expression Language)** to build modular AI pipelines.

### 2. Prompt Engineering

* **Frameworks:** Application of the **CO-STAR** method for structured prompting.
* **In-Context Learning:** Utilizing **Zero-Shot** and **Few-Shot** learning to enable pattern matching without model training.
* **Dynamic Templates:** Separating instructions from data using advanced prompt selectors.

### 3. Advanced Reasoning

* **Chain of Thought (CoT):** Implementing latent reasoning to improve logic and mathematical accuracy.
* **Tree of Thoughts (ToT):** Evaluating multiple reasoning branches through "Judge" agent architectures.
* **Graph of Thoughts (GoT):** Aggregating and synthesizing diverse ideas into a single coherent output.

### 4. Retrieval-Augmented Generation (RAG)

* **Embeddings:** Converting text into high-dimensional vectors for semantic search.
* **Vector Stores:** Using **FAISS** to manage and query "non-parametric" memory (external facts).
* **Indexing:** Comparative analysis of **Flat, IVF, HNSW, and PQ** indexing based on speed and memory trade-offs.

## 🛠️ Tech Stack

* **Orchestration:** LangChain
* **Vector Database:** FAISS
* **LLMs:** Google Gemini & Llama 3.1
* **Embeddings:** Hugging Face Transformers (`all-MiniLM-L6-v2`)

---

