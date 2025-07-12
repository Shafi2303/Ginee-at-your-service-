# 🎙️ Ginee - Desktop Voice Assistant

**Ginee** is a Python-based desktop voice assistant created to respond to user commands using speech recognition and text-to-speech capabilities. It can perform a variety of tasks such as searching Wikipedia, telling the time and date, opening websites, taking screenshots, sending emails, and more — all via voice commands.

---

## 🧠 Features

- 🕒 Tells current time and date
- 🧾 Searches Wikipedia and reads summaries
- 🌐 Opens popular websites like YouTube, Google, and Stack Overflow
- 🎵 Plays random music from a local directory
- 📸 Takes screenshots and saves them automatically
- 📬 Sends emails via voice command
- 📌 Remembers and recalls short notes
- 🔍 Performs Google searches
- 💬 Greets the user based on the time of day

---

## 🛠️ Tech Stack

- **Language:** Python 3.x  
- **Libraries Used:**
  - `pyttsx3` – Text-to-Speech
  - `speech_recognition` – Speech-to-Text
  - `wikipedia` – Wikipedia API
  - `webbrowser` – Opens websites
  - `os` – System-level operations
  - `random` – Random selection (music)
  - `pyautogui` – For screenshots
  - `smtplib`, `email.message` – Sending emails

---

## 🔧 Requirements

Install the required Python packages using pip:

```bash
pip install pyttsx3 SpeechRecognition wikipedia pyautogui
