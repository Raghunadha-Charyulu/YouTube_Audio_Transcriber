# 🎙️ YouTube Audio Transcriber using Whisper and yt-dlp

A Python-based tool to download audio from YouTube videos and transcribe it into readable, stanza-formatted text using OpenAI Whisper.

---

## 📌 Description

This project extracts audio from a YouTube video using `yt-dlp` and transcribes it using OpenAI’s Whisper ASR model.  
The transcribed text is formatted into **stanzas** based on silence gaps, making it ideal for **lyrics**, **speeches**, and **multilingual subtitles**.

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **yt-dlp** – for downloading YouTube audio
- **Whisper (by OpenAI)** – for transcription
- **FFmpeg** – for audio processing
- **Librosa** (optional) – for advanced audio feature extraction
- **OS module** – file handling

---

## ✨ Features

- 🎵 Extracts and transcribes YouTube audio
- 🗣️ Supports multilingual transcription (e.g., Telugu, Hindi, etc.)
- 📄 Outputs clean, stanza-formatted text based on silence detection
- 🧠 Uses OpenAI Whisper for high-accuracy transcription

---

## ⚙️ How to Run

```bash
# Clone the repository
git clone https://github.com/Raghunadha-Charyulu/youtube-audio-transcriber.git
cd youtube-audio-transcriber

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the script
python transcriber.py
