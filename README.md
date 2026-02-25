# Final Project

## Emotion Detection Application

This project is a web-based Emotion Detection application built using the Watson NLP Library and Flask.

## Project Description

The application analyzes text input and detects the following emotions:
- Anger
- Disgust
- Fear
- Joy
- Sadness

It also identifies the **dominant emotion** from the analyzed text.

## Project Structure
```
final_project/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── server.py
├── test_emotion_detection.py
└── README.md
```

## How to Run

1. Install dependencies:
```bash
pip install flask
```

2. Start the server:
```bash
python3 server.py
```

3. Open your browser and go to:
```
http://localhost:5000
```

## Running Unit Tests
```bash
python3 -m unittest test_emotion_detection.py
```

## Technologies Used

- Python 3
- Flask
- Watson NLP Emotion Detection API
- HTML/CSS/JavaScript
