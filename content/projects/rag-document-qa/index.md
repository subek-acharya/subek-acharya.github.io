---
title: 'RAG Application: Document Q&A System'
date: 2026-05-01
weight: 20
featured: true

summary: A document question-answering system built with LangChain, Mistral-7B, ChromaDB vector store, and Cohere reranking, providing answers with source citations and confidence scores.

tags:
  - LLM
  - RAG
  - LangChain
  - NLP
  - Mistral-7B
  - ChromaDB
  - Vector Search

links:
  - type: code
    name: GitHub
    url: https://github.com/subek-acharya/RAG-Application

image:
  caption: ''
  focal_point: ''
  preview_only: false
---

Built an end-to-end Retrieval-Augmented Generation (RAG) system for intelligent document Q&A. Key features:

- **LLM**: Mistral-7B for high-quality answer generation
- **Vector Store**: ChromaDB for efficient semantic search over document embeddings
- **Reranking**: Cohere reranker to improve retrieval precision
- **Framework**: LangChain for orchestrating the retrieval and generation pipeline
- **Trust**: Provides source citations and confidence scores for each answer

This project demonstrates modern LLM engineering practices, combining retrieval and generation to create trustworthy AI assistants grounded in domain-specific documents.