https://github.com/RoshiniNishad/NOVA-Next-Gen-Optimized-Virtual-Assistant-
# NOVA-Next-Gen-Optimized-Virtual-Assistant

NOVA-Next-Gen-Optimized-Virtual-Assistant is an AI-powered virtual assistant that leverages speech recognition, computer vision, and natural language processing to provide an interactive and intelligent assistant experience.

## 🚀 Features
- **Voice Commands**: Recognizes and responds to voice commands.
- **Hotword Detection**: Listens for a specific wake word to activate.
- **Face Recognition**: Identifies authorized users via computer vision.
- **Automation**: Controls applications and performs automated tasks.
- **Web Integration**: Fetches information from the internet.
- **Custom Commands**: Users can define custom voice commands.

---

## 🛠️ Installation & Setup
### 1️⃣ Clone the Repository
```sh
 git clone https://github.com/RoshiniNishad/NOVA-Next-Gen-Optimized-Virtual-Assistant.git
 cd NOVA-Next-Gen-Optimized-Virtual-Assistant
```

### 2️⃣ Create & Activate Virtual Environment
```sh
python -m venv envJarvis
```
#### **For Windows**
```sh
envJarvis\Scripts\activate
```
#### **For macOS/Linux**
```sh
source envJarvis/bin/activate
```

### 3️⃣ Install Dependencies
First, ensure you have `pip` updated:
```sh
pip install --upgrade pip
```
Then install the required modules:
```sh
pip install -r requirements.txt
```

⚠️ If `requirements.txt` is missing, install dependencies manually:
```sh
pip install eel opencv-python numpy speechrecognition pyttsx3 pyautogui pvporcupine pyaudio
```

---

## ▶️ Running the Project
```sh
python run.py
```

If you encounter module errors (e.g., `ModuleNotFoundError: No module named 'pyaudio'`), follow the troubleshooting section below.

---

## ❌ Troubleshooting
### 1️⃣ Missing `pyaudio`
#### **Windows**
1. Download `pyaudio` from [here](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio)
2. Install it via:
   ```sh
   pip install <downloaded-file.whl>
   ```

#### **macOS/Linux**
```sh
sudo apt-get install portaudio19-dev
pip install pyaudio
```

### 2️⃣ Missing `pvporcupine`
```sh
pip install pvporcupine
```

### 3️⃣ Missing `cv2` (OpenCV)
```sh
pip install opencv-python
```

---

## 📂 Project Structure
```
NOVA-Next-Gen-Optimized-Virtual-Assistant/
│── backend/
│   ├── auth/
│   │   ├── recoganize.py
│   ├── feature.py
│   ├── db.py
│   ├── helper.py
│── frontend/
│── main.py
│── run.py
│── requirements.txt
│── config.py
```

---

## 📌 To-Do & Future Enhancements
- Add GPT-4 integration for better conversational AI.
- Implement GUI-based command execution.
- Improve NLP-based command understanding.

---

## 🤝 Contributing
Feel free to fork this project and submit pull requests!

---

## 📄 License
This project is licensed under the MIT License.

