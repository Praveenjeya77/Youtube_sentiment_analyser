# 📊 YouTube Comment Sentiment Analyzer

Analyze the sentiment of YouTube video comments using NLP! This application fetches comments from a YouTube video and classifies each as **positive**, **neutral**, or **negative** using a Hugging Face transformer model.

## 🚀 Features

- Extracts comments from a YouTube video  
- Analyzes comment sentiment using a pre-trained Hugging Face pipeline  
- Simple and interactive Gradio-based web interface  
- Supports up to 100 comments at once

## 🧠 How It Works

1. Paste a YouTube video URL.  
2. Choose how many comments to analyze.  
3. Click the **Analyze** button.  
4. View sentiment results in a table, including sentiment label and confidence score.

## 🛠️ Technologies Used

- **Python**  
- **Gradio** – for building the web interface  
- **Hugging Face Transformers** – for sentiment analysis  
- **Google API Client** – to interact with YouTube Data API  
- **Pandas** – for comment data handling and display  
- **Regex** – for extracting video IDs from YouTube URLs

## 📌 Notes

- Make sure the YouTube Data API v3 is enabled for your Google Cloud project.  
- Sentiment analysis model is limited to the first 512 characters of each comment due to transformer input limits.
