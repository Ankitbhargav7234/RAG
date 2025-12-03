# RAG
📄 Retrieval-Augmented Generation (RAG) Pipeline

This project demonstrates how to build a RAG (Retrieval-Augmented Generation) system using:

Sentence-Transformers for creating embeddings

FAISS for vector similarity search

LangChain text splitters for chunking the knowledge source

Hugging Face Transformers for generating responses

Python / Colab environment

The system retrieves the most relevant context from a knowledge base and generates answers to user queries.

🚀 Features

✔ Load custom knowledge text file
✔ Split long documents into meaningful chunks
✔ Convert chunks to vector embeddings
✔ Store & search embeddings using FAISS
✔ Retrieve top-K relevant chunks
✔ Feed context into a Hugging Face text-generation model
✔ Ask questions using natural language
