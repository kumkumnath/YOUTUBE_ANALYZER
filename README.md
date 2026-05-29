# 🎥 AI YouTube Video Analyzer

AI YouTube Video Analyzer is an Agentic AI-powered application built using Streamlit, Agno, and OpenAI models. The project analyzes YouTube videos and generates structured insights including timestamps, summaries, topic breakdowns, and key learning points.

---

# 🚀 Features

* Analyze YouTube videos using AI
* Generate detailed video summaries
* Create structured timestamps
* Detect key topics and transitions
* Interactive Streamlit UI
* Powered by OpenAI GPT models
* Uses Agno Agent Framework

---

# 🛠️ Tech Stack

* Python
* Streamlit
* Agno
* OpenAI
* YouTubeTools
* dotenv

---

# 📂 Project Structure

```bash
├── ui.py
├── youtube_analyzer.py
├── .env
├── requirements.txt
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone <your-repo-link>
cd <repo-name>
```

## Create Virtual Environment

```bash
python -m venv venv
```

## Activate Environment

### Windows

```bash
venv\Scripts\activate
```

### Mac/Linux

```bash
source venv/bin/activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Variables

Create a `.env` file and add:

```env
OPENAI_API_KEY=your_api_key
```

---

# ▶️ Run Project

```bash
streamlit run ui.py
```

---

# 📸 How It Works

1. Paste a YouTube video link
2. Click **Analyze Video**
3. AI generates:

   * Video overview
   * Timestamps
   * Topic segmentation
   * Key insights
   * Learning points
