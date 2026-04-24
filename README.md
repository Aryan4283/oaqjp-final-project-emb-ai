# Emotion Detection Flask App

## 📌 About
This project is a web-based Emotion Detection application built using Python and Flask.  
It analyzes user input text and detects emotions such as anger, disgust, fear, joy, and sadness.

This project was developed as part of the IBM Skills Network course.

---

## ⚙️ Tech Stack
- **Python**
- **Flask**
- **IBM Watson NLP API**
- **Requests**
- **PyLint**

---

## 🚀 Features
- Emotion detection using NLP
- Displays dominant emotion
- Web interface using Flask
- Error handling for invalid input
- Unit testing implemented

---

## 🧠 How It Works
1. User enters text in the web interface.
2. The Flask server sends a request to the IBM Watson NLP API.
3. The API returns emotion scores.
4. The app extracts and displays scores for:
   - Anger
   - Disgust
   - Fear
   - Joy
   - Sadness
5. The dominant emotion is calculated and shown to the user.

---

## ▶️ Run Locally

1. Install the required dependencies:
```bash
pip install flask requests
```

2. Run the server:
```bash
python3 server.py
```

3. Open your browser and navigate to:  
`http://localhost:5000`

---

## ⚠️ Error Handling
If no input is provided or the text is invalid, the app will return the following message:  
> `Invalid text! Please try again!`

---

## 📂 Project Structure

```text
.
├── EmotionDetection/
│   ├── emotion_detection.py
│   └── __init__.py
├── server.py
└── test_emotion_detection.py
```

---

## 📚 Acknowledgement
This project is based on an IBM Skills Network lab.

---

## 👤 Author
Aryan Sarad
