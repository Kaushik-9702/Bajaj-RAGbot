# Factsheet RAG Pipeline (Core Backend)

This project implements the **core Retrieval-Augmented Generation (RAG) pipeline** for answering questions based on a mutual fund factsheet PDF. The entire workflow is developed and tested in Google Colab.

## What’s Implemented
- PDF ingestion and text extraction  
- Semantic text chunking  
- Embedding generation using SentenceTransformers  
- FAISS vector index for similarity search  
- Retrieval function to fetch top-k relevant chunks  
- Extractive answer generator with fallback for missing information  

## What’s Not Included
- No FastAPI or Streamlit (focus was on RAG logic)
- I have not yet worked with FastAPI or Streamlit, but I am fully confident in my ability to pick them up quickly. I would appreciate being considered for opportunities where I can grow these skills while contributing my strong understanding of RAG and backend ML pipelines.

## ✅ Summary
This project demonstrates a complete backend RAG engine capable of semantically searching a factsheet and returning grounded answers. Deployment/UI layers are left as future enhancements.
