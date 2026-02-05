# 🤖 AI Resume Job Matcher

An AI-powered application that analyzes **Resumes** and matches them with suitable **job descriptions** using LLM.

This project is a Streamlit web application that matches a resume to a job description using a local Large Language Model (LLM) via Ollama. It provides a fit score, strengths, and improvement suggestions for your resume.

## 🚀 Features

- Upload resume and job description (PDF or TXT)
- Uses local LLM (Ollama) for analysis
- Fit score (0-100%)
- Key strengths and improvement suggestions
- Downloadable match report

## 🛠️ Tech Stack

- Python
- Streamlit
- Ollama (for running local LLM models)
- PyMuPDF (for PDF parsing)
- Requests (for HTTP API calls to Ollama)

## 📂 Project Structure

```
AI_Resume_Job_Matcher
├─ README.md
└─ resume_job_matcher
   ├─ app.py
   └─ requirements.txt

```

## ⚡ Setup Instructions

### 1. Create and activate a virtual environment:

```bash
   python -m venv venv
   .\venv\Scripts\activate
```

### 2. Install dependencies:

```bash
   pip install -r requirements.txt
```

### 3. Install and set up Ollama

- Download and install Ollama: https://ollama.ai
- Start the Ollama server in a separate terminal:

```bash
ollama pull llama3
ollama list
ollama run llama3
```

### 4. Run the Streamlit app

```bash
streamlit run resume_job_matcher/app.py

```

## ❗ Troubleshooting

- If you see a connection error to `localhost:11434`, ensure the Ollama server is running.
- Make sure you have pulled the required model (e.g., llama3).

## 📸 Screenshots

### HomePage

<img width="1900" height="875" alt="Image" src="https://github.com/user-attachments/assets/df5e58a2-0219-48eb-9506-365fd6f4ad4a" />
