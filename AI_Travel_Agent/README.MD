# 🛫 AI Travel Agent

## 📌 Overview

AI Travel Agent is a **Streamlit-based AI application** that generates **personalized travel itineraries** using Large Language Models.

It automates travel research, planning, and scheduling, helping users quickly create well-structured travel plans tailored to their preferences.

## ✨ Features

- Discover travel destinations, attractions, and accommodations
- AI-generated itineraries based on travel duration, budget, and style
- Real-time web search for activities using SerpAPI
- Export itinerary as a **calendar (.ics) file**
- Supports **cloud-based LLMs** and **local LLMs (Ollama)**
- API-based, configurable, and deployment-ready

## 🛠️ Tech Stack

- **Language:** Python
- **Frontend:** Streamlit
- **LLMs:** OpenAI GPT-4o / Ollama (local)
- **Agent Framework:** Agno
- **Search API:** SerpAPI
- **Utilities:** iCalendar
- **Deployment Ready:** AWS / Local

## 📁 Project Structure

```
AI_Travel_Agent
├─ ai_travel_agent
│  ├─ local_travel_agent.py
│  ├─ requirements.txt
│  └─ travel_agent.py
├─ README.MD
└─ venv

```

## 🚀 Getting Started

### 1. Clone the GitHub repository

```bash
git clone https://github.com/Shyamatluri4/AI_Projects.git
cd AI_PROJECTS/AI TRAVEL AGENT/ai_travel_agent
```

### 2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit App

```bash
streamlit run travel_agent.py
```

### For local LLM usage (with Ollama):

- Install and set up Ollama

- Download and install Ollama: https://ollama.ai
- Start the Ollama server in a separate terminal:

```bash
ollama pull llama3
ollama list
ollama run llama3
```

- Run the Streamlit App

```bash
streamlit run local_travel_agent.py
```

## ⚙️ How it Works

### The AI Travel Agent consists of two main agents:

🔎 Researcher Agent

- Generates intelligent search queries
- Fetches real-world travel data using SerpAPI
- Identifies attractions, stays, and activities

🧭 Planner Agent

- Analyzes research results
- Creates a day-wise personalized itinerary
- Optimizes for time, experience, and user preferences

📅 Calendar Download Feature

### After generating your itinerary:

- Click "Download Itinerary as Calendar (.ics)"
- Save the file locally
- Import into Google Calendar, Apple Calendar, or Outlook
- Each travel day appears as a calendar event with full details

This allows easy access to your travel plan across devices.

## Notes

- This project integrates the OpenAI API for advanced natural language processing and SerpAPI for real-time semantic search. You can obtain these API Keys's from these links provided below.
- OpenAI API Key: https://platform.openai.com/
- SerpAPI Key: https://serpapi.com/

### Local vs Cloud Version

- **travel_agent.py**: Uses OpenAI's GPT-4o for high-quality itineraries (requires OpenAI API key)
- **local_travel_agent.py**: Uses Ollama for local LLM inference without sending data to external APIs (requires Ollama to be installed and running)
