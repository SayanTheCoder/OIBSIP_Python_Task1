# 🎙️ Sayan's Voice Assistant

A simple and interactive **Python-based Voice Assistant** that uses speech recognition and text-to-speech technology to interact with users through voice commands.

The assistant can recognize spoken commands, provide the current date and time, open websites, perform Google searches, and respond to basic conversational commands.

## ✨ Features

* 🎤 Voice command recognition
* 🔊 Text-to-speech responses
* 🕐 Current time information
* 📅 Current date information
* 🌐 Open Google using voice commands
* ▶️ Open YouTube using voice commands
* 📚 Open Wikipedia using voice commands
* 🔎 Perform Google searches
* ▶️ Search YouTube by voice
* 📚 Search Wikipedia by voice
* 👋 Basic greeting and conversational responses
* ❌ Exit the assistant using a voice command
* ⚠️ Error handling for unrecognized speech
* 🌐 Handles internet connection errors

## 🛠️ Technologies Used

| Technology            | Purpose                             |
| --------------------- | ----------------------------------- |
| **Python 3**          | Core programming language           |
| **SpeechRecognition** | Converts spoken audio into text     |
| **PyAudio**           | Provides microphone and audio input |
| **pyttsx3**           | Converts text into speech           |
| **datetime**          | Provides current date and time      |
| **webbrowser**        | Opens websites and search results   |

## 📋 Requirements

Before running the project, make sure **Python 3** is installed on your system.

A working **microphone** and an **active internet connection** are also recommended.

### Install Dependencies

Open a terminal in the project directory and run:

```bash
pip install -r requirements.txt
```

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/SayanTheCoder/OIBSIP_Python_Task1.git
```

### 2. Open the Project Folder

```bash
cd "OIBSIP_Python_Task1/VOICE ASSISTANT"
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

### 4. Run the Voice Assistant

```bash
python voice_assistant.py
```

## 🎤 Example Usage

After starting the assistant, speak a command such as:

```text
Search for Python programming
Search YouTube for Python programming
Search Wikipedia for Python programming
```

The first command opens Google search results. The YouTube and Wikipedia commands open search results on their respective sites.

Other example commands include:

```text
What is the time?
What is today's date?
Open Google
Open YouTube
Open Wikipedia
Search for funny cat videos on YouTube
Search Wikipedia for Ada Lovelace
Hello
Exit
```

## 📂 Project Structure

```text
VOICE ASSISTANT/
│
├── voice_assistant.py    # Main Python program
├── requirements.txt      # Required Python packages
├── .gitignore            # Files ignored by Git
└── README.md             # Project documentation
```

## ⚙️ How It Works

The assistant follows a simple voice-processing workflow:

```text
        🎤 Microphone
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
        🔊 Speaker
```

### Process

1. The microphone captures the user's voice.
2. Speech recognition converts the voice into text.
3. The program identifies the user's command.
4. The appropriate action is performed.
5. The assistant generates a response.
6. The response is converted into speech.
7. The response is played through the speaker.

## 🔮 Future Improvements

The project can be extended with additional features such as:

* 🎤 More voice commands
* 🖥️ Voice-controlled application launching
* 🎵 Music playback using voice commands
* 🌦️ Weather information
* 📰 News updates
* 📚 Wikipedia search
* ⚙️ System control commands
* 🔑 Wake-word detection
* 🖼️ Graphical User Interface (GUI)
* 📴 Offline speech recognition
* 🤖 AI-powered conversational responses
* 🧠 Natural language processing
* 📱 Smart-device integration

## 👨‍💻 Author

**Sayan Pramanik**

This project was developed as a **Python Voice Assistant project** for learning, experimentation, and understanding speech recognition and text-to-speech technologies.

## ⭐ Support

If you find this project useful or interesting, consider giving the repository a ⭐ **Star** on GitHub.
