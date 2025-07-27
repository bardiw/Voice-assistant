# 🧠 Voice Assistant AI (Python)

A powerful voice-activated virtual assistant written in Python that can answer questions, open websites, take notes, control the system, recognize speech, and more — all with your voice.

> This assistant supports English speech recognition and is extendable for other languages and custom commands.

---

## 🎯 Features

- ✅ Speech recognition using **Google API**
- ✅ Voice responses using **pyttsx3**
- ✅ Search information from **Wikipedia**
- ✅ Real-time **weather** updates using OpenWeatherMap API
- ✅ **Web browser** automation: Google, YouTube, Gmail, News
- ✅ **WolframAlpha** integration for questions & calculations
- ✅ Local commands:
  - ⌚ Show current time
  - 📸 Take photo via webcam
  - 📷 Take screenshot
  - 📝 Write & read notes
  - 🧠 Answer knowledge-based questions
  - 🌤 Weather info
  - 📤 Open Telegram (custom path)
  - 🔐 Logout system
- 🧠 Name learning: remembers user's name during session

---

## 🚀 Getting Started

### 🔧 Prerequisites

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## 🗂️ Project Structure
bash
Copy
Edit
voice-assistant/
│
├── Voice_assistant.py             # Main voice assistant code
├── requirements.txt         # Dependencies
└── README.md                # This file

---

## 🧪 Sample Commands
"Wikipedia Albert Einstein" – searches Wikipedia

"Open YouTube" – opens YouTube

"Search Stack Overflow" – searches web

"What time is it?" – current time

"Write note" – writes a note

"Show note" – reads the saved note

"Take photo" – captures photo

"Screenshot" – takes a screenshot

"Weather" – gives weather report

"Question what is 2 plus 2" – WolframAlpha query

"Logout" – logs out the system

---

## 📌 Customization
- Change the voice in pyttsx3 using:

```
voices = engine.getProperty('voices')
engine.setProperty('voice', voices[1].id)  # Use index based on available voices
```
- Change the Telegram path in this line:

```
os.startfile(r"C:\Users\YourUser\AppData\Roaming\Telegram Desktop\Telegram.exe")
```
- Replace the WolframAlpha API key with your own:

```
app_id = "YOUR_WOLFRAM_KEY"
```
- Replace the OpenWeatherMap API key with yours:
```
api_key = "YOUR_API_KEY"
```

---

👨‍💻 Author
 Bardia Javadi   
 📧 bardia.javadi.dev@gmail.com   
 🌐 GitHub: @bardiw
