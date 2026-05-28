# Production_Grade_RAG
Ask questions over your documents, get answers with provable citations or no answer at all
<img width="1302" height="682" alt="image" src="https://github.com/user-attachments/assets/5f40b3b5-c383-4ef2-9015-57e6a69a6433" />
High-Level Ingestion Flow
Input (PDF / MD / Web)
        ↓
Document Loaders
        ↓
Text Cleaning & Normalization
        ↓
Chunking (500–800 tokens, overlap 100)
        ↓
Metadata Enrichment
        ↓
Output → Ready for Embedding + Storage

