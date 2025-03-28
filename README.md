# Speech-to-Text (STT) Whisper

## 📌 Overview
This project utilizes OpenAI's **Whisper** model to transcribe audio into text. It includes a **custom AudioProcessor** for preprocessing audio, converting it into **log-Mel spectrograms**, and ensuring compatibility with the Whisper model.

## 🚀 Features
- **Audio Preprocessing**: Converts audio files into spectrograms
- **Whisper Model Integration**: Uses OpenAI's Whisper for transcription
- **Normalization & Tensor Conversion**: Ensures correct input format
- **Batch Processing**: Handles multiple files efficiently

---

## 🛠️ Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/puravgupta2002/stt-Whisper2002.git
cd stt-Whisper2002
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
> Ensure `torch` and `transformers` are installed for the Whisper model.

---

