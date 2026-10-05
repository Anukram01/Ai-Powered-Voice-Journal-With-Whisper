# 🎙️ AI-Powered Voice Journal with Whisper

An intelligent, full-stack digital journaling web application built with **Python (Flask)** and **OpenAI's Whisper**. The application enables users to record voice notes, automatically transcribe audio to text, extract sentiment and emotional insights, maintain digital journal history, and export analytical PDF summaries.

---

## 🌟 Key Features

- **Voice-to-Text Transcription:** Fast, local, and accurate speech recognition powered by OpenAI's Whisper model.
- **In-Browser Audio Recording:** Real-time audio capture and playback via custom JavaScript and MediaRecorder API.
- **Sentiment & Mood Analytics:** Automatic sentiment scoring and emotional trend tracking from journal entries.
- **User Authentication:** Secure sign-up, sign-in, session handling, and protected personal dashboards.
- **Interactive Dashboard:** Visual dashboard showing recent journal activities and analysis metrics.
- **PDF Export Engine:** Generate structured, downloadable PDF reports of voice entries and summaries.

---

## 🛠️ Tech Stack

- **Backend:** Python 3.12, Flask
- **Speech-to-Text:** OpenAI Whisper
- **Frontend:** HTML5, CSS3, JavaScript
- **Database:** SQLite / SQLAlchemy
- **Deployment:** Render (`render.yaml` configured)

---

## 📁 Repository Structure

```text
├── app/
│   ├── services/
│   │   └── transcription.py   # Audio handling & Whisper model inference
│   ├── static/
│   │   ├── app.js             # Client-side audio recording logic
│   │   └── style.css          # UI styles & responsive layout
│   ├── templates/
│   │   ├── auth.html          # Authentication views
│   │   ├── base.html          # Layout shell
│   │   ├── dashboard.html     # Analytics dashboard
│   │   ├── entry_detail.html  # Detailed single entry viewer
│   │   ├── history.html       # Full entries log
│   │   └── index.html         # Main recording interface
│   ├── analysis.py            # Text and sentiment analysis logic
│   ├── auth.py                # Authentication routes & helpers
│   ├── db.py                  # Database initialization & models
│   ├── pdf_analysis.py        # Entry summary extraction
│   ├── pdf_export.py          # PDF generation engine
│   └── routes.py              # Application endpoints
├── main.py                    # Application entry point
├── render.yaml                # Render deployment blueprint
├── requirements.txt           # Project dependencies
└── README.md                  # Project documentation
