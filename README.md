# Multi-PDF Q&A with RAG-powered LLM

**LinkedIn** : https://www.linkedin.com/in/sadhikbasha/

**Problem Statement:**

1.) The "Multi-PDF Q&A with RAG-powered LLM" project provides an intelligent system to analyze and query multiple PDF documents using a Retrieval-Augmented Generation (RAG) approach.

2.) This project extracts text, intelligently chunks it, generates embeddings, and retrieves relevant content for context-aware responses.

3.) With a Streamlit UI, users can upload PDFs and ask natural language questions, receiving accurate, document-grounded answers in real time.

---

**Features**

Automated text extraction from PDFs using PyPDF.

Semantic chunking with RecursiveCharacterTextSplitter.

Embedding generation with Google Generative AI Embeddings (embedding-001).

FAISS vector database for efficient similarity search.

Gemini LLM (gemini-1.5-flash) for context-aware Q&A.

Streamlit interface for document upload and querying.

---

**Tools**

Python, PyPDF, LangChain, FAISS, Google Generative AI API, Streamlit

---

**Approach**

PyPDF: Extracts text from multi-page PDF documents.

RecursiveCharacterTextSplitter: Splits text into meaningful chunks while preserving context.

Google Generative AI Embeddings: Converts text into dense embeddings.

FAISS: Stores and retrieves document embeddings for similarity search.

Gemini LLM (gemini-1.5-flash): Generates context-aware answers based on retrieved chunks.

Streamlit: Builds an interactive dashboard for PDF upload and Q&A.

---

**Findings**

The system successfully enables document-grounded Q&A across multiple PDFs, demonstrating the power of RAG (Retrieval-Augmented Generation) for real-world document analysis and knowledge extraction.

---
**Prerequesting Library**

→ All required libraries and environment setup details are documented in the requirements.txt file.
