# My RAG System

## Topic:
Environmental Science and Climate Studies

## What I changed:
- **Documents:** Added 5 PDFs related to environmental science and climate.
- **Chunking:** Changed chunk_size to 1200 and chunk_overlap to 200 for better paragraph context.
- **Retrieval:** Used k=5, fetch_k=10, lambda_mult=0.5 — improved precision in answers.

## How to run:
1. Install requirements: `pip install -r requirements.txt`
2. Run the main file: `python test1_rag_setup.py`

## Test questions:
1. What are the main causes of climate change?
2. How does deforestation affect the carbon cycle?
3. What are the impacts of global warming on biodiversity?
