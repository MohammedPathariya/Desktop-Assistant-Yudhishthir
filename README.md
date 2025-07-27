# 🧠 Yudhishthir – Python Desktop Assistant

**Yudhishthir** is a multifunctional, voice-activated desktop assistant built using Python. It combines speech recognition, automation, and a variety of Python libraries to create a smart personal assistant that can respond to voice commands, answer questions, automate tasks, and even entertain with games.

---

## 📌 About the Project

This project was created as part of a Project-Based Learning (PBL) initiative by **Team Pandav**:

- Prasad Unecha  
- Yash Kulkarni  
- Mohammed Pathariya  

The assistant is named **Yudhishthir** after the eldest Pandava prince in Indian mythology — a symbol of wisdom, truth, and guidance. Just like its namesake, this assistant is designed to help users with information, utilities, and fun activities in an interactive, intelligent way.

---

## 🚀 Features

- 🎙️ Voice Interaction using Speech Recognition and pyttsx3
- 📖 Wikipedia search and spoken summaries
- ⏰ Time reporting via voice
- 📧 Email sending to predefined contacts
- 🏆 Certificate generator with mail delivery (CSV + PIL + SMTP)
- 🧮 GUI-based calculator using Tkinter
- 💰 Amazon price tracker with email alerts
- 🗺️ Location finder using Google Maps
- 🌦️ Weather updates using OpenWeatherMap API
- 🔒 Security surveillance with motion detection (OpenCV + alert sound)
- 🎮 Games:
  - Tic Tac Toe (vs friend or computer)
  - Rock-Paper-Scissors with voice control
- 🧠 Custom responses and introduction

---

## 🗂️ Project Structure

```

Desktop Assistant YUDHISHTHIR/
│
├── assistant.py            # Main assistant logic and voice loop
├── email\_alert.py          # Price alert mailer script
├── camera.py               # Security surveillance system
├── games.py                # Rock-Paper-Scissors game logic
├── data.csv                # CSV data for certificate generation
├── image.jpeg              # Certificate template
├── pictures/               # Folder for storing generated certificates
├── log.txt                 # Tic Tac Toe game history
├── alert.wav               # Alert sound for surveillance

````

---

## 🛠️ Technologies & Libraries Used

- Python 3.x
- `speech_recognition`, `pyttsx3`
- `wikipedia`, `webbrowser`
- `tkinter`, `PIL`, `pandas`, `csv`
- `smtplib`, `email.message`, `EmailMessage`
- `requests`, `beautifulsoup4`
- `opencv-python`, `winsound`
- `pyautogui`, `autoit`

---

## 🔧 How to Run

1. Clone the repo:
   ```
   git clone https://github.com/yourusername/Yudhishthir-Desktop-Assistant.git
   cd Yudhishthir-Desktop-Assistant
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the assistant:

   ```bash
   python assistant.py
   ```

> Make sure you have a microphone, speaker, and webcam enabled for full functionality.

---

## ✅ Sample Commands

* “Search Einstein on Wikipedia”
* “What’s the time?”
* “Send certificate”
* “Play Tic Tac Toe”
* “Check weather in Delhi”
* “Open Google”
* “Find location of Taj Mahal”
* “Play rock paper scissors”
* “Send email to Yash”
* “Start calculator”
* “Activate security”

---

## 📦 Sample `requirements.txt`

```text
speechrecognition
pyttsx3
wikipedia
pillow
pandas
opencv-python
requests
beautifulsoup4
pyautogui
autoit
```

---

## ⚠️ Security Note

This project contains hardcoded email credentials for certificate and alert features. In a production environment, always:

* Use `.env` files to store credentials
* Load them using `python-dotenv`
* Never push sensitive data to public repositories

---

## 🏛️ Acknowledgements

This project was developed under the guidance of **Dr. Usha Polina**, faculty at Pune Institute of Computer Technology, with specialization in Solar Cell Physics and extensive experience in research and teaching.

---

## 💬 Contact

📧 Email: [yudhishthirpbl@gmail.com](mailto:yudhishthirpbl@gmail.com)
🏫 Developed at: Pune Institute of Computer Technology (PICT)

---

## 🧠 Inspiration

Yudhishthir isn’t just a code assistant — he’s a mythologically inspired helper created by passionate students to demonstrate the power of voice control, automation, and AI in daily tasks.
