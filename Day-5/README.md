# Day 5 – Retrieval-Augmented Generation (RAG)

## 📌 Overview
Day 5 of the Drive Ready AI Agents – One Person Company (OPC) training focused on Retrieval-Augmented Generation (RAG), where an AI model retrieves relevant information from a PDF document and generates answers based on the retrieved content.

In this session, I worked on building a PDF Question-Answering system using Python, embeddings, similarity search and Groq API.

## 📚 Topics Covered
- Introduction to Retrieval-Augmented Generation (RAG).
- Extracting and processing PDF content.
- Splitting documents into smaller text chunks.
- Generating embeddings using a sentence-transformer model.
- Semantic similarity search using FAISS.
- Retrieving relevant chunks based on user questions.
- Connecting an LLM using Groq API.
- Generating answers using retrieved PDF context.

## 🛠️ Technologies Used
- Python
- Google Colab
- Groq API
- FAISS
- NumPy
- Sentence Transformers
- PDF Processing

## 📖 Project – PDF Question-Answering System
The project involves creating a system that allows users to ask questions about the content of a PDF document.

### Workflow
1. Load and extract text from a PDF.
2. Split the extracted text into smaller chunks.
3. Convert text chunks into embeddings.
4. Store embeddings in a FAISS index.
5. Enter a question from the user.
6. Retrieve the most relevant text chunks from the PDF.
7. Send the retrieved context and question to the LLM.
8. Generate an answer based only on the PDF content.

## 🎯 Learning Outcome
Through Day 5, I learned how Retrieval-Augmented Generation (RAG) works, how embeddings help retrieve relevant information, how FAISS performs similarity search, and how an LLM can answer questions based on retrieved PDF content instead of relying only on its general knowledge.

## 📅 Training
**Program:** Drive Ready AI Agents | One Person Company (OPC)  
**Day:** 5  
**Topic:** Retrieval-Augmented Generation (RAG) – PDF Question Answering
