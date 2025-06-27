# 🤖 AI-Powered Help Bot for MOSDAC

An intelligent chatbot that leverages NLP and Knowledge Graphs to retrieve precise, contextual information from the [MOSDAC portal](https://www.mosdac.gov.in) — enhancing usability, accessibility, and navigation through complex satellite data and documentation.

---

## 🚀 Problem Statement

The MOSDAC portal hosts valuable satellite and meteorological data, FAQs, and scientific documentation. However, its layered structure and mixed content types make information discovery challenging.

This AI-based Help Bot enables:
- 🔍 Context-aware search and intelligent responses
- 🧠 Knowledge graph-based understanding of entities and relationships
- 🗺️ Spatially-aware queries for geospatial content
- 🔄 Modular architecture for reuse in similar government/public portals

---

## 🧠 Key Features

- ✅ NLP-powered chatbot with intent recognition & entity extraction  
- ✅ Knowledge Graph for document-aware querying  
- ✅ Real-time RAG (Retrieval-Augmented Generation) integration  
- ✅ Multi-turn conversations with logical consistency  
- ✅ Clean and responsive chatbot UI  
- ✅ Scalable & modular backend for other portals

---

## ⚙️ Tech Stack

### 🧩 Backend
- Python, FastAPI, LangChain
- spaCy, Rasa, Haystack
- Neo4j / NetworkX for Knowledge Graphs

### 🖥️ Frontend
- React.js, HTML, CSS
- Chat UI libraries (custom or open source)

### 📄 Data Extraction
- BeautifulSoup, Scrapy, PyMuPDF, python-docx

### ☁️ Deployment
- Frontend → Vercel  
- Backend → Render / Heroku

---

## 📁 Folder Structure

```
mosdac-helpbot/
├── README.md
├── frontend/           # React chatbot interface
├── backend/            # FastAPI server with LangChain pipeline
├── data/               # Scraped PDFs, FAQs, tables
├── nlp/                # spaCy/Rasa NLP models
├── knowledge_graph/    # Entity-relation logic and scripts
├── docs/               # Poster, idea submission, architecture
└── .gitignore
```

---

## 🛠️ How to Run Locally

### 🧠 Backend (FastAPI + LangChain)
```bash
cd backend
pip install -r requirements.txt
uvicorn app:main --reload
```

### 💬 Frontend (React)
```bash
cd frontend
npm install
npm run dev
```

---

## 📊 Evaluation Metrics

| Metric | Description |
|--------|-------------|
| 🎯 Intent Recognition | Accuracy of query classification |
| 🧩 Entity Recognition | Precision in extracting relevant topics |
| 🧠 Response Accuracy | Coverage & correctness of answers |
| 🔁 Context Consistency | Logical flow in multi-turn conversations |

---

## 👨‍💻 Team Members

- **Shree** – UI Flow, Roadmap, Documentation, Dataset Preparation  
- **Sneha Manded** – AI/NLP Lead, Backend Developer, Graph Architecture  
- **Sneha Patil** – Frontend Developer, UI Integration, API Linking  

---

## 📌 Status
✅ Idea Submitted  
🔄 MVP In Development  
🚀 Preparing for Hackathon Finale

---

## 📣 License
MIT License – Use freely with attribution.

---

## 🌐 Useful Links
- [MOSDAC Portal](https://www.mosdac.gov.in)
- [LangChain](https://www.langchain.com)
- [Neo4j](https://neo4j.com/)
