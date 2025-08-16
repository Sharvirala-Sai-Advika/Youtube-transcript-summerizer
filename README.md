YouTube Transcript Summariser

📖 Project Overview

The YouTube Video Summariser is a Chrome Extension integrated with a Flask-based backend API that automatically fetches YouTube video transcripts and generates concise summaries using NLP techniques.

This project aims to save users’ time by providing quick insights from long YouTube videos, helping students, professionals, and general users access key information efficiently.

✨Features

--Fetches YouTube video transcripts automatically

--Performs abstractive text summarization using Hugging Face Transformers

--Chrome Extension with a simple popup interface

--REST API built with Flask to handle summarization

--Provides concise, human-readable summaries for quick learning

🏗 System Architecture

Components:

--Chrome Extension (Frontend) → Fetches transcript & displays summary

--Flask Server (Backend) → Handles summarization using NLP models

--YouTube Transcript API → Retrieves video subtitles/transcripts

--Transformers (NLP) → Generates abstractive summaries

Architecture Flow:

--User clicks Summarise button in the extension

--Extension fetches transcript using backend API

--Flask server processes transcript with Hugging Face Transformers

--Summary returned & displayed in Chrome popup

🛠 Technologies Used

--Frontend: HTML, CSS, JavaScript (Chrome Extension)

--Backend: Python, Flask

--APIs & Libraries:

-youtube-transcript-api – Fetching video transcripts

-transformers – NLP summarization

⚙ Installation & Setup

🔹 1. Clone the Repository

git clone https://github.com/Sharvirala-Sai-Advika/Youtube-transcript-summerizer.git

cd Youtube-transcript-summerizer

🔹 2. Install Backend Dependencies

Ensure you have Python 3.x installed. Then run:

pip install flask youtube-transcript-api transformers

🔹 3. Run Flask Server

python app.py

This will start the backend API at http://127.0.0.1:5000/.

🔹 4. Load Chrome Extension

Open Chrome → Go to chrome://extensions/

Enable Developer Mode

Click Load unpacked and select the project folder

The extension will appear in your toolbar

🚀 How to Use

Open any YouTube video with subtitles enabled.

Click on the YouTube Summariser Extension icon in Chrome.

Press the Summarise button.

Wait for processing — a concise summary of the video will appear.





