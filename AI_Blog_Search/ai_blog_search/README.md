# AI Blog Search

## Overview

AI Blog Search is an Agentic RAG application designed to enhance information retrieval from AI-related blog posts. It leverages LangChain, LangGraph, and Google's Gemini model to fetch, process, and analyze blog content, providing users with accurate and contextually relevant answers.

## Features

- Document Retrieval using Qdrant as a vector database
- Agentic Query Processing with LangChain and LangGraph
- Relevance Assessment using Gemini model
- Query Refinement for better retrieval
- Streamlit UI for user-friendly interaction
- Graph-Based Workflow for efficient decision-making

## Technologies Used

- **Python 3.10+**
- **LangChain**
- **LangGraph**
- **Qdrant**
- **Google Gemini API**
- **Streamlit**

## Setup Instructions

1. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   .\venv\Scripts\activate
   ```
2. **Install dependencies:**
   ```bash
   pip install -r ai_blog_search/requirements.txt
   ```
3. **Run the application:**
   ```bash
   streamlit run ai_blog_search/app.py
   ```

## Usage

- Enter your API keys in the sidebar.
- Paste the blog link.
- Enter your query about the blog post.
