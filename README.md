# RAG Document Q&A with Groq
Welcome to the RAG Document Q&A with Groq application! This application allows you to interact with research papers, asking questions, and receiving answers based on the content of those documents using a Retrieval-Augmented Generation (RAG) approach with the power of Groq's API and LangChain.

## Features
Document Loading & Processing: Load PDF documents from a directory, split them into manageable chunks, and prepare them for query answering.
Embedding & Vector Storage: Use Ollama Embeddings to convert documents into vectors, stored in an in-memory Chroma vector store.
Real-Time Q&A: Stream user queries to Groq's powerful LLM to generate answers based on the relevant context pulled from research papers.
