# 📚 AskMyDocs — Chat With Your Documents

> 🤖 An AI-powered **Document Question Answering System** that lets you upload your documents and interact with them using natural language.

AskMyDocs uses **Retrieval-Augmented Generation (RAG)** to retrieve relevant information from uploaded documents and generate accurate, context-aware answers.

---

## ✨ Features

* 📄 **Document Upload** — Upload and process your documents easily.
* 🔍 **Smart Retrieval** — Finds the most relevant information from your documents.
* 💬 **Natural Language Q&A** — Ask questions in simple language.
* 🧠 **RAG-Based Responses** — Generates answers using retrieved document context.
* ⚡ **Fast AI Responses** — Powered by an efficient LLM pipeline.
* 🗂️ **Vector Search** — Stores document embeddings for efficient retrieval.
* 🔐 **Environment Variables** — API keys are kept secure using `.env`.

---

## 🛠️ Tech Stack

| Technology       | Purpose                         |
| ---------------- | ------------------------------- |
| 🐍 Python        | Core Programming Language       |
| 🎨 Streamlit     | Web Application Interface       |
| 🦜 LangChain     | LLM & RAG Framework             |
| 🤖 Groq          | Large Language Model API        |
| 🗃️ ChromaDB     | Vector Database                 |
| 🔎 Hugging Face  | Text Embeddings                 |
| 🔑 python-dotenv | Environment Variable Management |

---

## 🔄 How It Works

```text
📄 Upload Document
       ↓
✂️ Text Extraction & Chunking
       ↓
🧠 Generate Embeddings
       ↓
🗃️ Store in Vector Database
       ↓
❓ User Asks a Question
       ↓
🔍 Retrieve Relevant Chunks
       ↓
🤖 LLM Generates Answer
       ↓
💬 Display Response
```

---

## 📁 Project Structure

```text
AskMyDocs/
│
├── 📄 app.py
├── ⚙️ config.py
├── 📂 file_loader.py
├── ✂️ chunker.py
├── 🤖 llm.py
├── 🔗 rag.py
├── 🗃️ vector_store.py
├── 📋 requirements.txt
├── 📖 README.md
├── 🚫 .gitignore
└── 🔐 .env
```

> 🔒 `.env`, virtual environment files, and Python cache files are excluded from Git using `.gitignore`.

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Shikha-codes/AskMyDocs.git
```

```bash
cd AskMyDocs
```

### 2️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

### 3️⃣ Activate the Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

### 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 5️⃣ Configure API Key

Create a `.env` file in the project root:

```env
GROQ_API_KEY=your_api_key_here
```

⚠️ **Never upload your API key to GitHub.**

### 6️⃣ Run the Application

```bash
streamlit run app.py
```

The application will open in your browser. 🚀

---

## 💡 Use Cases

AskMyDocs can be useful for:

* 📚 Studying from notes and documents
* 📑 Asking questions about reports
* 🔎 Quickly finding information in large documents
* 🎓 Academic research and learning
* 📖 Interacting with reference material

---

## 🧩 RAG Architecture

AskMyDocs follows a Retrieval-Augmented Generation workflow:

**Document → Chunking → Embeddings → Vector Database → Retrieval → LLM → Answer**

This approach allows the model to use relevant information from the uploaded documents while generating responses.

---

## 🚀 Future Improvements

* 📄 Support for more document formats
* 💾 Persistent document storage
* 💬 Conversation history
* 👥 Multi-document conversations
* 📊 Improved retrieval and ranking
* 🌐 Deployment for public access

---

## 👩‍💻 Author

**Sikha Tiwari**

🔗 GitHub: https://github.com/Shikha-codes

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub!

---

### 🚀 Built with Python, RAG & AI
