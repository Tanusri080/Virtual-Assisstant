# 🤖 Virtual Voice Assistant with GUI

This is a Python-based **Virtual Assistant** with a simple GUI, designed to take voice commands, process them, and respond with spoken output. It can answer questions, provide weather reports, and more!

---

## 🧠 Features

- 🎤 Converts speech to text (STT)
- 🔊 Responds using text-to-speech (TTS)
- ☁️ Real-time weather reporting
- 🖥️ Graphical User Interface (GUI)
- ⚙️ Modular structure for easy expansion

---

## 📁 Project Structure

├── action.py # Main file to start the assistant
├── GUI.py # User interface using tkinter
├── speech_to_text.py # Converts microphone input to text
├── text_to_speech.py # Converts text to audio output
├── weather.py # Fetches live weather information
├── pycache/ # Python cache files


---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
2. Install dependencies: pip install -r requirements.txt
3. Run the assistant: python action.py

## 🌤️ Weather API
The weather.py file uses Google's weather feature through HTTP requests to fetch real-time weather data for a given location.

## 📄 License
This project is open-source and free to use under the MIT License.
