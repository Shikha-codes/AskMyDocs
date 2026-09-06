# Chat With Your Documents

An AI-powered RAG application that allows users to upload PDF, DOCX, and TXT files and ask questions based on their uploaded documents.

## Features

- Upload PDF, DOCX, and TXT files
- Extract text from uploaded documents
- Split text into overlapping chunks
- Generate embeddings using Sentence Transformers
- Store document embeddings using ChromaDB
- Retrieve relevant document chunks based on user questions
- Generate AI-powered answers using Groq LLM
- Display source documents and relevance scores
- Maintain chat history
- Clear documents and chat functionality
- Adjustable model settings

## Technologies Used

- Python
- Streamlit
- Groq API
- Sentence Transformers
- ChromaDB
- PyPDF
- Python-DOCX
- Retrieval-Augmented Generation (RAG)

## Project Workflow

```text
User Uploads Document
        ↓
Text Extraction
        ↓
Text Chunking
        ↓
Generate Embeddings
        ↓
ChromaDB Vector Store
        ↓
Retrieve Relevant Chunks
        ↓
RAG Context Building
        ↓
Groq LLM
        ↓
AI Generated Answer
```

## Installation

Clone the repository:

```bash
git clone YOUR_REPOSITORY_LINK
```

Navigate to the project folder:

```bash
cd chat-with-your-documents-rag
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment:

### Windows

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Environment Setup

Create a `.env` file in the project folder and add your Groq API key:

```env
GROQ_API_KEY=your_api_key_here
```

## Run the Application

```bash
streamlit run app.py
```

## How It Works

1. Upload a PDF, DOCX, or TXT document.
2. The application extracts text from the uploaded file.
3. The extracted text is divided into overlapping chunks.
4. Sentence Transformers generates embeddings for the chunks.
5. ChromaDB stores the embeddings.
6. The application retrieves the most relevant chunks based on the user's question.
7. The retrieved context is passed to the Groq LLM.
8. The LLM generates an answer based on the uploaded document context.

## Author

Sikha Tiwari