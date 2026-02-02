# Page-indexing

# Vectorless RAG with PageIndex

## What is Vectorless RAG?

Vectorless RAG (Retrieval-Augmented Generation) is a method for building AI-powered question-answering systems **without using embeddings or vector databases**.  
Instead of searching over vector representations, it relies on **structured document hierarchies** to find the most relevant content for a question.

## How PageIndex Differs from Traditional RAG

- **Traditional RAG:** uses embeddings, similarity search, and vector databases to find relevant chunks of text.  
- **PageIndex:** builds a **document tree**, lets the AI reason over the structure, and directly selects the most relevant nodes.  
  - No vectors, no approximate nearest neighbor search  
  - Preserves **document context and hierarchy** for more precise reasoning  
  - Simplifies the pipeline for PDF and structured content 

This is a test change for pull request.

