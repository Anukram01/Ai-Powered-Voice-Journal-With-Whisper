# Voice Journal with Whisper

A full-stack speech-to-text journaling application built using Python (Flask) and OpenAI Whisper. It records voice notes directly in the browser, transcribes speech locally, extracts sentiment trends, stores journal history, and generates downloadable PDF reports.

## Tech Stack
- **Backend:** Python 3.12, Flask
- **Speech Recognition:** OpenAI Whisper
- **Frontend:** HTML5, CSS3, JavaScript (MediaRecorder API)
- **Database:** SQLite / SQLAlchemy
- **Deployment:** Render (`render.yaml` configured)

## Features
- **In-Browser Audio Capture:** Real-time audio recording using native Web APIs.
- **Local Whisper Transcription:** Offline speech-to-text processing ensuring user privacy.
- **Sentiment & Mood Tracking:** Extracts emotional insights and journal trends.
- **Authentication & Dashboard:** Secure user accounts and personal entry management.
- **PDF Export:** Generates formatted analytical summaries for offline use.

## Quick Setup

### 1. Prerequisites
- Python 3.10+ installed
- **FFmpeg** installed and added to system `PATH` (required by Whisper)

### 2. Installation & Run
```bash
# Clone the repository
git clone [https://github.com/Anukram01/Ai-Powered-Voice-Journal-With-Whisper.git](https://github.com/Anukram01/Ai-Powered-Voice-Journal-With-Whisper.git)
cd Ai-Powered-Voice-Journal-With-Whisper

# Setup virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run application
python main.py
