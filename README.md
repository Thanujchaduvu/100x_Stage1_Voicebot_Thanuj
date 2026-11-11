# 100x Stage 1 AI Voice Bot & Live RAG Agent — Thanuj Chaduvu

This repository contains the single-file, production-grade interactive **Voice Bot & Live RAG Web Application** built for **Stage 1 of the 100x AI Agent Team selection process**.

## 🌟 Key Features

1. **Grounded RAG Retrieval Engine**:
   - Built-in client-side vector-like search engine using token TF-IDF keyword matching.
   - Strictly grounded in Thanuj Chaduvu's resume, academic history (B.Tech in Data Science, CMR Technical Campus, CGPA 8.39), and project work (*GrowEasy AI*, *Smart Hospital Management System*, *Fireflies AI Clone*).

2. **Full Voice Capabilities (Web Speech API)**:
   - **Speech-to-Text (STT)**: Real-time microphone listening and voice transcription.
   - **Text-to-Speech (TTS)**: Dynamic voice playback automatically prioritized for **Male Voice** profiles, with rate, pitch, and voice controls.
   - **Canvas Audio Waveform Visualizer**: Live neon wave animations reacting to active listening and speaking states.

3. **Gemini LLM Integration (`gemini-3-flash-preview`)**:
   - Direct integration with Google Gemini API with fallback to RAG context responses if no API key is provided.
   - Key setting modal supporting persistent local storage saving.

4. **100x Stage 1 Evaluation Suite**:
   - Dedicated 1-click prompt chips for all 5 evaluation questions (*Life Story*, *#1 Superpower*, *Top 3 Growth Areas*, *Misconception*, *Pushing Limits*).
   - Candidate Resume Dossier Modal.
   - Built-in 1-click email submission helper pre-configured for `bhumika@100x.inc` with subject line: `GEN AI: GEN AI ROUND 1 ASSESSMENT (LINKEDIN - CHADUVU THANUJ)`.

---

## 🚀 Quick Start / Local Setup

1. Simply extract `100x-ai-voicebot.zip`.
2. Double click `index.html` to open it in any modern browser (Chrome / Edge recommended for full Web Speech API support).
3. No build tools, Node.js packages, or terminal installations are required!

---

## 🌐 Deploying to GitHub & GitHub Pages

1. Create a new public repository on [GitHub](https://github.com) named `100x-ai-voicebot`.
2. Upload `index.html` and `README.md`.
3. Go to **Repository Settings** -> **Pages** -> Select `main` branch and root `/` folder -> Click **Save**.
4. Your application will be live at `https://thanujchaduvu.github.io/100x-ai-voicebot/`.

---

## 📬 Contact & Candidate Info
- **Candidate Name:** Thanuj Chaduvu
- **Email:** chaduvuthanuj@gmail.com
- **Phone:** +91-7661007080
- **LinkedIn:** [linkedin.com/in/chaduvu-thanuj04](https://linkedin.com/in/chaduvu-thanuj04)
- **GitHub:** [github.com/Thanujchaduvu](https://github.com/Thanujchaduvu)
