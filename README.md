# Interactive-AI-chatbot-and-voice-chatbot

<img width="1918" height="1017" alt="image" src="https://github.com/user-attachments/assets/a2abaea1-3730-4de9-bfde-595d10fb7fdf" />

🤖 Interactive AI Chatbot &amp; Voice Chatbot enables natural conversations through text and voice. Powered by NLP, speech recognition, and TTS, it provides real-time responses for support, learning, or personal use. Extendable to multilingual chats and deployable on web or mobile apps.

🤖 Interactive AI Chatbot & Voice Chatbot
📖 Overview

The Interactive AI Chatbot & Voice Chatbot is a conversational AI project that allows users to interact through both text and voice commands. It uses NLP for natural text conversations and speech recognition + text-to-speech (TTS) for voice interactions.
Designed for customer support, personal assistance, and educational use.

🚀 Features

💬 Real-time text-based chatbot.

🎙️ Voice chatbot using Speech-to-Text (STT) & TTS.

🧠 Powered by transformer models for natural conversation.

🌍 Extendable for multilingual conversations.

🔌 Can be integrated with web or mobile apps.

🛠️ Tech Stack

Language: Python

NLP Libraries: Hugging Face Transformers, NLTK, SpaCy

Voice Tools:

Speech Recognition (Google API / Whisper)

gTTS / pyttsx3 for Text-to-Speech

Frameworks (optional): Flask / FastAPI (backend), Gradio / Streamlit (UI)

📦 Installation
# Clone the repository
git clone https://github.com/yourusername/ai-chatbot.git
cd ai-chatbot

# Install dependencies
pip install -r requirements.txt

▶️ Usage
📝 Text Chatbot
python chatbot.py


Example:

User: Hello, how are you?  
Bot: I’m doing great! How can I help you today?  

🎤 Voice Chatbot
python voice_chatbot.py


Speak into the microphone 🎙️

Bot will reply with both text + voice output 🔊

📂 Project Structure
project/
│── data/              # Datasets for training  
│── models/            # Trained models  
│── src/               # Chatbot & voice code  
│── outputs/           # Logs / responses  
│── requirements.txt  
│── README.md  

🔮 Future Enhancements

Add emotion detection for more human-like conversations.

Enable offline voice recognition.

Deploy as a WhatsApp / Telegram bot.

Create a web & mobile UI for easy interaction.

📜 License

This project is licensed under the MIT License – free to use and modify.
