# 🔍 AI Blog Search

## 📌 Overview

AI Blog Search is an Agentic RAG application designed to enhance information retrieval from AI-related blog posts. It leverages LangChain, LangGraph, and Google's Gemini model to fetch, process, and analyze blog content, providing users with accurate and contextually relevant answers.

## ✨ Features

- Document Retrieval using Qdrant as a vector database
- Agentic Query Processing with LangChain and LangGraph
- Relevance Assessment using Gemini model
- Query Refinement for better retrieval
- Streamlit UI for user-friendly interaction
- Graph-Based Workflow for efficient decision-making

## 🧠 Technologies Used

- **Python 3.10+**
- **LangChain**
- **LangGraph**
- **Qdrant**
- **Google Gemini API**
- **Streamlit**

## 📂 Project Structure

```
AI_Blog_Search
├─ ai_blog_search_agent
│  ├─ app.py
│  └─ requirements.txt
└─ README.md

```

## 🛠️ Setup Instructions

1. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   .\venv\Scripts\activate
   ```
2. **Install dependencies:**
   ```bash
   pip install -r ai_blog_search_agent/requirements.txt
   ```
3. **Run the application:**
   ```bash
   streamlit run ai_blog_search_agent/app.py
   ```

## 🚀 Usage

- Enter your API key's in the sidebar
- Paste the AI blog URL
- Enter your query related to the blog content
- Receive accurate, context-aware answers powered by Agentic RAG

## Notes

- This project uses Google's Gemini API and Qdrant API for advanced language processing and for semantic search. You can obtain these API Keys's from these links provided below.
- Google Gemini API Key: https://ai.google.dev/
- Qdrant Cloud API Key: https://cloud.qdrant.io/

## 📸 Screenshots

### HomePage

<img width="1893" height="886" alt="Image" src="https://github.com/user-attachments/assets/7e287381-bb82-4f05-989f-ebdda9f50f43" />
