# 📈 AI Startup Trend Analysis Agent

The **AI Startup Trend Analysis Agent** is an intelligent research tool designed for entrepreneurs and startup enthusiasts. It generates actionable insights by identifying emerging startup trends, market gaps, and growth opportunities across various industries.

The system combines **Newspaper4k** and **DuckDuckGo Search** to collect and analyze startup-related news articles and market data. It uses **Google-Gemini AI** to extract patterns and produce meaningful trend insights.

## 📂 Project Structure

```
AI_Startup_Trend_Analysis
├─ ai_startup_trend_analysis_agent
│  ├─ requirements.txt
│  └─ startup_trends_agent.py
└─ README.md

```

## ⚙️ Technologies Used

- Python
- Newspaper4k
- DuckDuckGo
- Google Gemini (Google AI Gemini API)
- streamlit
- Agno Framework

### ✨ Features

- **AI-Powered Trend Detection** – Identifies emerging startup and technology trends.
- **Automated News Aggregation** – Collects startup news and funding insights using DuckDuckGo.
- **Content Extraction & Summarization** – Uses Newspaper4k to extract and summarize article content.
- **Market Opportunity Insights** – Highlights potential gaps and business opportunities.
- **Interactive Streamlit UI** – User-friendly interface for research and exploration.

### 🛠️ Getting Started

1. **Clone the repository**:

```bash
   git clone <repo>

```

2. **Create and activate a virtual environment**:

```bash
   # For macOS/Linux
   python -m venv venv
   source venv/bin/activate

   # For Windows
   python -m venv venv
   .\venv\Scripts\activate

```

3. **Install the required packages**:

```bash
   pip install -r ai_startup_trend_analysis_agent/requirements.txt

```

4. **Run the application**:

```bash
   streamlit run startup_trends_agent.py

```

### Important Note

- The system specifically uses Google's Gemini API for advanced language processing. You can obtain your Google Gemini API key from the Google AI Studio or Google Cloud Console (https://ai.google.dev/)

## 📸 Screenshots

### HomePage

<img width="1888" height="829" alt="Image" src="https://github.com/user-attachments/assets/b0991808-45c8-47a6-bd0b-d0be38c39c1b" />
