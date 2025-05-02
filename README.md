# 🎥 Multimodal AI Agent - Video Summarizer

An AI-powered application built with Streamlit that analyzes and summarizes videos using Google's Gemini 2.0 Flash model and the Phi Agent framework. Enhanced with DuckDuckGo for web-based context retrieval.

---

## 🌟 Features

- Upload `.mp4`, `.mov`, `.avi` videos
- Ask questions about the video content
- Summarized analysis using Google Gemini 2.0 Flash
- Web-augmented answers via DuckDuckGo
- Streamlit-based interactive UI

---

## 📦 Requirements

- Python 3.10+
- Google API Key (for Gemini)
- FFmpeg (for some video formats)
- Internet access (for API and web search)

---

## 💻 Installation Guide

### 🔧 1. Install Python 3.10+

git clone https://github.com/yourusername/video-ai-summarizer.git
cd video-ai-summarizer
conda create -n videoSummerizer
conda activate videoSummerizer
pip install -r requirements.txt

##############################################


🔐 5. Set Up Your Google API Key
Go to Google AI Studio

Sign in with your Google account

Generate an API key

In the root directory of the project, create a .env file:

env
Copy
Edit
GOOGLE_API_KEY=your_google_api_key_here


##################################################


streamlit run app.py


