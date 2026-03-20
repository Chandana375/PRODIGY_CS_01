🚀 Mini SOC Cyber Toolkit

📌 Project Overview

The Mini SOC Cyber Toolkit is a web-based cybersecurity application built using Python and Flask.
It demonstrates both encryption techniques and security analysis concepts used in Security Operations Centers (SOC).


🎯 Features

🔐 Caesar Cipher Encryption & Decryption
🧠 Brute Force Attack Simulation
📝 Real-time Logging System (soc.log)
🌐 Web-based Interface (Flask)
❌ Input Validation (prevents crashes)
📊 Log Monitoring Dashboard



🧠 How It Works

Users enter a message and shift value
The system encrypts or decrypts using Caesar Cipher
Brute force shows all possible decryptions (attack simulation)
Every action is recorded in logs (SOC concept)

---

🖥️ Tech Stack

Python
Flask
HTML/CSS
Tkinter (earlier versions)



▶️ Installation & Run

pip install flask
python app.py

Open browser:
http://127.0.0.1:5000



🧪 Example Usage

Encrypt

Input: hello
Shift: 3
Output: khoor

Brute Force

Input: khoor
Output shows all 26 possible shifts



📁 Project Structure

MiniSOC/
│── app.py
│── templates/
│   └── index.html
│── soc.log
│── README.md



💼 Cybersecurity Relevance

This project demonstrates:

Basic cryptography concepts
Attack simulation (brute force)
Logging and monitoring (SOC operations)



🚀 Future Enhancements

🔐 User authentication (login system)
📊 Log analytics dashboard (charts)
🚨 Alert detection system
🌐 Deployment on cloud



This project is developed for learning cryptography and SOC fundamentals.
