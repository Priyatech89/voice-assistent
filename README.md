# voice-assistent
A voice assistant is an AI-powered tool that understands spoken commands and responds with helpful information or actions. It allows users to interact hands-free to complete everyday tasks quickly and easily.
Bibble is a Python-based voice assistant that listens to voice commands and performs various tasks such as searching Wikipedia, opening websites, telling jokes, playing music, and more.

This project demonstrates the use of Speech Recognition and Text-to-Speech technologies in Python.

🚀 Features

🎧 Voice command recognition

🗣️ Text-to-speech responses

📚 Wikipedia search (who is / what is / tell me about)

🌐 Open popular websites (Google, YouTube, GitHub, WhatsApp, etc.)

😂 Random jokes

✍️ Poems / Shayari

🎵 Play random Spotify songs

⏰ Tell current time

🎲 Fun actions (coin flip, dice roll)

❌ Exit using voice commands

🛠️ Technologies Used

Python 3

pyttsx3 – Text to Speech

speech_recognition – Speech Recognition

sounddevice – Audio Recording

wikipedia – Wikipedia Search

numpy, scipy – Audio Processing

📦 Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/bibble-voice-assistant.git
cd bibble-voice-assistant

2️⃣ Install Dependencies
pip install -r requirement.txt


⚠️ Important Note:
This project uses pyttsx3 with sapi5, so it works best on Windows OS.

▶️ How to Run
python app.py


When the program starts, the assistant:

Greets the user based on the current time

Listens to voice commands via microphone

Executes actions based on recognized commands

🗣️ Example Voice Commands

"Open YouTube"

"Open Google"

"Who is Albert Einstein"

"Tell me a joke"

"Play a song"

"What is the time"

"Flip a coin"

"Roll a dice"

"Exit" / "Bye"

📁 Project Structure
├── app.py
├── requirement.txt
└── README.md

⚠️ Limitations

Internet connection required for speech recognition and Wikipedia

Spotify songs open in a web browser

Designed primarily for Windows systems

🌟 Future Enhancements

Add GUI (Tkinter / PyQt)

Improve natural language understanding

Integrate Weather API

Add email and messaging automation

Custom wake-word support

❤️ Author

Developed using Python
If you like this project, don’t forget to ⭐ the repository and contribute!
