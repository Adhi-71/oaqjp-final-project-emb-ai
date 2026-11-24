# Final project

Emotion Detection AI web application built with Python, Flask, and the IBM Watson NLP EmotionPredict service for the **IBM Build & Deploy AI Applications with Python & Flask** course (`oaqjp-final-project-emb-ai`).

## Project Structure

```text
oaqjp-final-project-emb-ai/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── server.py
├── test_emotion_detection.py
├── requirements.txt
└── README.md
```

## Setup & Usage (IBM Skills Network Cloud IDE)

> **Note:** The Watson NLP `EmotionPredict` endpoint (`https://sn-watson-emotion.labs.skills.network/v1/watson.runtime.nlp.v1/NlpService/EmotionPredict`) is only reachable from inside the IBM Skills Network Cloud IDE lab environment.

1. Install dependencies (if not already installed in your environment):
   ```bash
   pip install -r requirements.txt
   ```
2. Run unit tests:
   ```bash
   python3.11 test_emotion_detection.py
   ```
3. Run static code analysis (PyLint):
   ```bash
   pylint server.py
   ```
4. Start the Flask web server:
   ```bash
   python3.11 server.py
   ```
   Open `http://localhost:5000` in your browser to use the Emotion Detection interface.
