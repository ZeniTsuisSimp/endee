# AceMate - AI Exam Preparation Assistant

Built by: Aman Kumar (ZeniTsuisSimp)

## Project Repository
https://github.com/ZeniTsuisSimp/AceMate

## Live Demo
https://acemate-production.up.railway.app

## What it does
AceMate transforms PDFs into a searchable vector knowledge base 
using Endee Vector DB. Students upload notes and syllabus, then 
interact with an AI that answers questions, predicts exam questions, 
summarizes topics, generates MCQs, and tracks weak areas.

## How Endee is Used
- 384-dimension cosine similarity index
- PDF chunks stored as vectors with metadata
- Semantic search retrieves relevant chunks for RAG context
- Source attribution per answer (file + page number)

## Tech Stack
Endee Vector DB | Sarvam AI | Streamlit | sentence-transformers | PyMuPDF
