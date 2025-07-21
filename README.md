# 🌍 SAWA – Real-Time Multilingual Meeting Platform

**SAWA** is an AI-powered web platform that enables seamless real-time communication between people speaking different languages. It integrates advanced speech-to-text, translation, and text-to-speech technologies to provide real-time audio dubbing and multilingual chat within virtual meetings.

SAWA Poster
https://your-poster-link-or-banner-image-if-hosted](https://docs.google.com/presentation/d/1VAENJq-BjQESXTYUiCrM1vkSdQ-l5fBD/edit?usp=sharing&ouid=102473138781845686455&rtpof=true&sd=true

---

## 🚀 Features

- 🎙️ **Real-Time Speech Translation**: Convert spoken language into live text and translate it instantly.
- 🔊 **Live Audio Dubbing**: Hear translated speech using AI voice synthesis.
- 💬 **Multilingual Chat**: Auto-translate chat messages between participants.
- 🖥️ **Screen Sharing & Whiteboard**: Share content and annotate collaboratively.
- 🔐 **Secure & Compliant**: Session logging, permission management, and GDPR-ready design.

---

## 🛠️ Tech Stack

### 💻 Frontend
- HTML5, CSS3, JavaScript
- Bootstrap for responsive UI

### 🧠 Backend
- Django (Python) for server-side logic and API
- MySQL & MongoDB for structured and unstructured data

### 🤖 AI / ML
- OpenAI Whisper — Real-time Speech-to-Text (STT) & Translation
- Google Text-to-Speech (gTTS) — Text-to-Speech synthesis
- Streamlit & Pygame — Real-time audio streaming
- Agora — Voice and video integration (optional)

### 🎨 Design
- Figma — UI/UX Prototyping

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/Mohamedgamal851/SAWA.git
cd SAWA

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt

python manage.py runserver

