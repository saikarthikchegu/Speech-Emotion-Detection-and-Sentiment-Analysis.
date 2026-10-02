# Speech Emotion Detection and Sentiment Analysis

A dual-pipeline deep learning system that analyzes both **acoustic features** (for emotion recognition) and **spoken text transcriptions** (for sentiment analysis) from speech audio.

---

## 📌 Project Overview

Speech carries rich information beyond just words. This project processes raw audio inputs (`.wav`, `.mp3`) through two synchronized analytical pipelines:

1. **Acoustic Emotion Recognition:** Extracts Mel-Frequency Cepstral Coefficients (MFCCs) and acoustic properties to classify emotions (*Happy, Sad, Angry, Neutral, Fearful, Surprise*).
2. **Textual Sentiment Analysis:** Transcribes spoken audio to text using Automated Speech Recognition (ASR) and analyzes the sentiment (*Positive, Negative, Neutral*) using transformer-based NLP models.

---

## 🏗️ Architecture Pipeline
