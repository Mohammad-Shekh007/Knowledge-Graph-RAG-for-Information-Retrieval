# KG RAG for Information Retrieval

This project implements a **Knowledge Graph–based Retrieval-Augmented Generation (KG RAG)** system using **LlamaIndex** and **OpenAI**.

The system loads PDF documents, builds a knowledge graph from their content, and answers questions by reasoning over relationships instead of only matching similar text.

This is a **Naive KG RAG** implementation.

---

## What the System Does

- Loads PDF files
- Extracts text
- Builds a Knowledge Graph index
- Retrieves connected facts
- Uses an LLM to generate answers

---

## RAG Type

- Naive Knowledge Graph RAG  
- Not Advanced or Modular RAG

---

## Requirements

- Python 3.9+
- llama-index
- pymupdf
- python-dotenv

---

## Environment Setup

Create a `.env` file:

```env
OPENAI_API_KEY=your_api_key_here
How to Run
python main.py


Ask questions in the terminal.

Limitations

No ontology rules

No reranking

No advanced orchestration

---

## ⚠️ Security & Privacy Notice

Do **not** upload or use private, confidential, or sensitive documents for retrieval.  
This system sends retrieved content to OpenAI models for processing, so any data used should be safe to share with third-party APIs.
