# RAG_Model_Starwars
 This is a RAG Model which can be built on your local machine which enables you to create fine tuning model using Starwars Screenplay documents

This repository contains a fully self‑contained Jupyter Notebook demonstrating how to build a Retrieval‑Augmented Generation (RAG) pipeline from scratch — themed entirely around Star Wars. You’ll learn how to:

Ingest & preprocess DOCX, XLSX, and PDF scripts
Split documents into context‑rich chunks
Index them in a local vector store (Nomic + SKLearn embeddings)
Route user questions intelligently between Star Wars documents and a web search fallback
Generate concise, context‑grounded answers using Ollama’s 3 B‑parameter instruct model
Grade both document relevance and answer hallucinations with JSON‑structured evaluation
Produce clean, structured JSON outputs for any number of Star Wars–related queries
Everything runs locally on modest hardware (8 GB+ RAM) with zero cost for core dependencies. Swap in a larger cloud LLM (ChatGPT, Grok, etc.) or expand your vector store with additional Star Wars scripts to instantly boost performance.
