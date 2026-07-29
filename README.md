# Star Wars RAG

A self-contained Jupyter notebook that builds a Retrieval-Augmented Generation
(RAG) pipeline from scratch over the Star Wars screenplays: document loading,
chunking, embeddings, vector search, and grounded generation, all running
locally.

## How it works

- Loads and chunks the screenplay PDFs with RecursiveCharacterTextSplitter
- Embeds chunks with Nomic embeddings into an in-memory vector store
- Routes questions through a LangGraph workflow that retrieves relevant scenes
  and answers with a local Llama model via ChatOllama
- No API keys and no cloud calls; everything runs on your machine

## Run it

1. Install [Ollama](https://ollama.com) and pull a Llama model
2. Place your own screenplay PDFs in a `Starwars Documents/` folder
   (the PDFs are not distributed with this repo)
3. Open the notebook and run top to bottom

Built as a hands-on exercise in retrieval quality: chunking strategy, embedding
choice, and retrieval routing all change the answers, and the notebook makes
those effects visible.
