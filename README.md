🎙️ Sayan's Voice Assistant

A simple Python-based voice assistant that uses speech recognition and text-to-speech to interact with the user through voice commands.

The assistant can recognize spoken commands, tell the current time and date, open websites, perform Google searches, and respond to basic conversations.

✨ Features

- 🎤 Voice command recognition
- 🔊 Text-to-speech responses
- 🕐 Tell the current time
- 📅 Tell the current date
- 🌐 Open Google
- ▶️ Open YouTube
- 🔎 Search the web using Google
- 👋 Basic greeting support
- ❌ Exit using a voice command
- ⚠️ Error handling for unrecognized speech and connection problems

🛠️ Technologies Used

- Python 3
- SpeechRecognition – Converts spoken audio into text
- PyAudio – Provides microphone/audio input
- pyttsx3 – Converts text into speech
- datetime – Provides date and time information
- webbrowser – Opens websites and search results

📋 Requirements

Make sure Python 3 is installed on your computer.

Install the required packages using:

pip install -r requirements.txt

Microphone

A working microphone is required because the application listens for voice commands.

🚀 How to Run

1. Clone the repository

Clone the repository:

git clone https://github.com/SayanTheCoder/OIBSIP_Python_Task1.git

2. Open the project folder

cd "OIBSIP_Python_Task1/VOICE ASSISTANT"

3. Install dependencies

pip install -r requirements.txt

4. Run the assistant

python voice_assistant.py

Example

Say:

Search for Python programming

The assistant will open Google and search for `Python programming`.

📂 Project Structure


VOICE ASSISTANT/
├── voice_assistant.py    Main Python program
├── requirements.txt      Python dependencies
├── .gitignore            Files ignored by Git
└── README.md            Project documentation


⚙️ How It Works

The assistant follows a simple process:


Microphone
    ↓
Speech Recognition
    ↓
Convert Speech to Text
    ↓
Identify Command
    ↓
Perform Action
    ↓
Generate Response
    ↓
Text-to-Speech
    ↓
Speaker


🔮 Future Improvements

Possible improvements for future versions:

- Add more voice commands
- Open applications using voice
- Play music using voice commands
- Weather information
- News updates
- Wikipedia search
- System control commands
- Wake-word detection
- Graphical user interface
- Offline speech recognition
- AI-powered conversational responses

👨‍💻 Author

Sayan Pramanik

This project was created as a Python voice assistant project for learning and experimentation.

⭐ If you find this project useful, consider giving the repository a star!
