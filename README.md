---
title: Gradio AI Document Intelligence & Semantic Retrieval
emoji: 📄
colorFrom: blue
colorTo: indigo
sdk: gradio
sdk_version: 6.25.0
app_file: app.py
pinned: false
---
# AI Document Intelligence & Semantic Retrieval

An AI document retrieval system that extracts PDF content,
creates semantic embeddings, and retrieves the most relevant
information using FAISS.

## Technologies

- Python
- PyMuPDF4LLM
- Sentence Transformers
- FAISS
- NumPy
- Gradio

## Architecture

PDF
→ 
PyMuPDF4LLM
→ 
Markdown
→ 
Structure-aware Chunking
→ 
Sentence Transformers
→ 
FAISS
→ 
Semantic Search
→ 
Gradio

## Features

- PDF text extraction
- Structure-aware chunking
- Metadata
- Semantic embeddings
- FAISS vector search
- Relevance scoring
- Gradio interface

## Run locally

```bash
pip install -r requirements.txt
python app.py
