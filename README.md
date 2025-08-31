# PDF-to-personalize-audio
Turn any PDF into a personalized audiobook, narrated in your own cloned voice, using Deepgram TTS and OpenVoice.

🚀 Features

✅ Extract text from any PDF

✅ Convert text → speech with Deepgram TTS

✅ Clone your own voice with OpenVoice

✅ Generate a complete audiobook with natural narration

✅ Runs entirely on Google Colab (no heavy local setup needed)

🖼️ Project Pipeline
flowchart LR
    A[📂 PDF Upload] --> B[📝 Extract Text]
    B --> C[🔊 Deepgram TTS]
    C --> D[🎙️ Voice Cloning via OpenVoice]
    D --> E[🎧 Final Personalized Audiobook]

📂 Repository Structure
📦 GenAI-PDF-Audiobook
 ┣ 📜 README.md
 ┣ 📓 notebook.ipynb     # Full Google Colab notebook
 ┣ 📂 assets             # Sample configs / checkpoints
 ┗ 📂 outputs            # Final generated audios

⚡ Quick Start

Clone Repository

git clone https://github.com/your-username/genai-pdf-audiobook.git
cd genai-pdf-audiobook


Open in Google Colab

Upload your PDF file

Upload your reference voice clip

Run all cells 🚀

Get Results

Final audiobook saved in your Google Drive

🛠️ Tech Stack

Google Colab

pdfplumber
 – PDF text extraction

Deepgram TTS
 – Natural voice synthesis

OpenVoice
 – Voice cloning

pydub
 – Audio processing

🎧 Results

Example audiobook: (add your sample link here)

Voice cloned output stored in outputs/final_cloned.wav

🌍 Applications

🎓 Education – Teachers narrating material in their own voice

📚 Content Creation – Authors producing audiobooks instantly

🧑‍🤝‍🧑 Accessibility – Personal audiobooks for visually impaired readers

⚠️ Disclaimer

This project is for educational purposes only.
Always use your own voice or get explicit consent before cloning others.
