# Voice Journal with Whisper

A full-stack speech-to-text journaling application built using Python (Flask) and OpenAI Whisper[span_0](start_span)[span_0](end_span)[span_1](start_span)[span_1](end_span)[span_2](start_span)[span_2](end_span). It records voice notes directly in the browser, transcribes speech locally, extracts sentiment trends, stores journal history, and generates downloadable PDF reports[span_3](start_span)[span_3](end_span)[span_4](start_span)[span_4](end_span)[span_5](start_span)[span_5](end_span).

## Tech Stack
- **Backend:** Python 3.12, Flask[span_6](start_span)[span_6](end_span)[span_7](start_span)[span_7](end_span)[span_8](start_span)[span_8](end_span)
- **Speech Recognition:** OpenAI Whisper[span_9](start_span)[span_9](end_span)[span_10](start_span)[span_10](end_span)[span_11](start_span)[span_11](end_span)
- **Frontend:** HTML5, CSS3, JavaScript (MediaRecorder API)[span_12](start_span)[span_12](end_span)[span_13](start_span)[span_13](end_span)[span_14](start_span)[span_14](end_span)
- **Database:** SQLite / SQLAlchemy[span_15](start_span)[span_15](end_span)[span_16](start_span)[span_16](end_span)
- **Deployment:** Render (`render.yaml` configured)[span_17](start_span)[span_17](end_span)[span_18](start_span)[span_18](end_span)

## Features
- **In-Browser Audio Capture:** Real-time audio recording using native Web APIs[span_19](start_span)[span_19](end_span)[span_20](start_span)[span_20](end_span)[span_21](start_span)[span_21](end_span).
- **Local Whisper Transcription:** Offline speech-to-text processing ensuring user privacy[span_22](start_span)[span_22](end_span)[span_23](start_span)[span_23](end_span)[span_24](start_span)[span_24](end_span).
- **Sentiment & Mood Tracking:** Extracts emotional insights and journal trends[span_25](start_span)[span_25](end_span)[span_26](start_span)[span_26](end_span).
- **Authentication & Dashboard:** Secure user accounts and personal entry management[span_27](start_span)[span_27](end_span)[span_28](start_span)[span_28](end_span)[span_29](start_span)[span_29](end_span).
- **PDF Export:** Generates formatted analytical summaries for offline use[span_30](start_span)[span_30](end_span)[span_31](start_span)[span_31](end_span).

## Quick Setup

### 1. Prerequisites
- Python 3.10+ installed[span_32](start_span)[span_32](end_span)[span_33](start_span)[span_33](end_span)
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
