-># 📄 DocuQuery AI – RAG Based Document Question Answering System

## 🚀 Overview
DocuQuery AI is an AI-powered system that allows users to ask questions from documents (PDF and text files).  
It uses **Retrieval-Augmented Generation (RAG)** to provide accurate, context-aware answers while reducing hallucination.

---

## 🧠 Key Concepts Used
- Retrieval-Augmented Generation (RAG)
- Embeddings
- Vector Databases
- Semantic Search

---

## 📂 Data Used
The project uses multiple documents:
- Research Paper: *Attention Is All You Need*
- Machine Learning Research Paper
- Text Files:
  - Machine Learning Introduction
  - Python Introduction

---

## ⚙️ System Architecture

1. Document Loading (PDF + Text)
2. Text Chunking
3. Embedding Generation
4. Storage in Vector Database (ChromaDB)
5. Query Processing
6. Similarity-based Retrieval
7. Context Extraction

---

## 🔍 RAG Pipeline Flow

User Query → Embedding → Vector DB Search → Top-K Retrieval → Relevant Context → Answer

---

## 💡 Features
- Supports multiple document formats (PDF + TXT)
- Semantic search using embeddings
- Fast retrieval using ChromaDB
- Top-K relevant chunk retrieval
- Similarity score filtering
- Context-aware responses

---

## 🛠️ Tech Stack
- Python
- ChromaDB (Vector Database)
- Custom Embedding Manager

---

## 🧩 Core Component: RAG Retriever

The project implements a custom retriever for semantic search.

### 🔹 Functionality:
- Converts user query into embedding
- Searches vector database
- Retrieves top-K relevant chunks
- Filters based on similarity score

---

## 📁 Project Structure

```
DocuQuery/
│── data/
│   ├── attention_paper.pdf
│   ├── ml_research.pdf
│   ├── ml_basics.txt
│   └── python_intro.txt
│
│── embeddings/
│── vectordb/
│
│── rag_retriever.py
│── embedding_manager.py
│── vector_store.py
│── app.py
│── requirements.txt
│── README.md
```

---

## ⚙️ Installation & Setup

1. Clone the repository:
```
git clone https://github.com/your-username/docuquery-ai.git
```

2. Navigate to the project folder:
```
cd docuquery-ai
```

3. Install dependencies:
```
pip install -r requirements.txt
```

4. Run the project:
```
python app.py
```

---

## ▶️ Usage

1. Load documents into the system  
2. Ask a query  
3. System retrieves relevant chunks  
4. Returns context-based answer  

---

## 📊 Example

**Query:**  
"What is attention mechanism?"

**Process:**  
- Convert query → embedding  
- Search vector database  
- Retrieve top 5 chunks  
- Filter by similarity score  
- Return most relevant context  

---

## 🔮 Future Improvements
- Add frontend UI (React.JS)
- Add multi-language support
- Deploy on cloud (AWS / Azure)
- Improve ranking mechanism

---

## 👩‍💻 Author
Khushi Garg

---

## 📌 Keywords
RAG | Chunking | ChromaDB | Embeddings | Semantic Search | AI Project
->