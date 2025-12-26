# Enterprise Document Intelligence System using RAG
A Retrieval-Augmented Generation (RAG) system that enables context-aware question answering over enterprise documents.
The system ingests organizational PDFs (including scanned documents using OCR), converts them into vector embeddings stored in FAISS, and uses a Generative AI model (Gemini) to produce accurate, grounded, and concise answers based strictly on retrieved document context, minimizing hallucinations.
