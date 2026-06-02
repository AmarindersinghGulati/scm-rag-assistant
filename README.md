# scm-rag-assistant

## Project Overview

This project implements a Retrieval-Augmented Generation (RAG) chatbot for Supply Chain Governance and Supplier Risk Analysis using Flowise.

The chatbot answers questions related to:

* Supplier governance policies
* Supplier performance metrics
* Compliance risks
* Procurement thresholds
* Active disruptions
* Supplier watch lists

---

## Technologies Used

* Flowise AI
* Qdrant Vector Database
* HuggingFace Embeddings
* Groq LLM (Llama 3.1)
* CSV + PDF document ingestion
* Conversational Retrieval QA Chain

---

## Architecture

PDF + CSV Documents
↓
Chunking & Embeddings
↓
Qdrant Vector Store
↓
Retriever
↓
Groq LLM
↓
RAG-based Response Generation

---

## Features

* Retrieval-Augmented Generation (RAG)
* Semantic search
* Supplier risk analysis
* Governance policy retrieval
* Hallucination prevention
* Public chatbot deployment

---

## Embedding Model

sentence-transformers/all-MiniLM-L6-v2

---

## LLM Used

llama-3.1-8b-instant via Groq API

---

## Vector Database

Qdrant Cloud

---

## Public Chatbot URL

https://cloud.flowiseai.com/chatbot/63c25ba2-6bca-4adf-a02e-107c0d9c4bb1

---

## Challenges Faced

* Gemini API quota limitations
* Vector database configuration
* Retrieval tuning and duplicate chunk handling

---

## Solution Improvements

* Migrated to Groq LLM
* Tuned Top-K retrieval
* Improved response prompts
* Added hallucination prevention

---

## Author

Amarindersingh Gulati

