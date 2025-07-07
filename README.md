# groq-llama3-pinecone-chatbot

# Semantic Chatbot with Groq, Pinecone, and PDF Embeddings

This project demonstrates a simple pipeline for building a chatbot that can semantically understand and query content from uploaded PDFs. It uses the SentenceTransformer model for embedding generation, Pinecone as the vector database, and optionally integrates with Groq's LLM APIs for further processing.

## 🧠 Features

- Upload and process scanned or digital PDF documents
- Extract text using pdfminer and fallback to Tesseract OCR for scanned files
- Split content into manageable chunks using LangChain
- Generate sentence embeddings with all-roberta-large-v1
- Store and query embeddings using Pinecone
- Run simple semantic search on the content

## 📦 Installation

```bash
pip install sentence-transformers
pip install pinecone-client
pip install langchain
pip install pdfminer.six
pip install pytesseract
pip install pdf2image
