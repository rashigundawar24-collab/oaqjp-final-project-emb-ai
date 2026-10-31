# Final Project

## AI-Based Emotion Detection Web Application

An AI-powered web application built using Python, Flask, and embedded Watson NLP libraries to analyze customer feedback and extract fine-grained emotional sentiment.

---

### Features
* **Emotion Detection**: Predicts scores for 5 primary emotions:
  * Joy
  * Anger
  * Disgust
  * Sadness
  * Fear
* **Dominant Emotion Identification**: Automatically determines the prevailing emotion from the text statement.
* **Flask Web Interface**: A responsive web frontend allowing users to input customer reviews and view detailed emotional analytics.
* **Robust Error Handling**: Gracefully handles blank or invalid inputs with informative feedback.
* **Tested & Formatted**: Includes full unit tests (`unittest`) and PEP 8 compliant code scoring **10.00/10** on `pylint`.

---

### Project Structure
```text
oaqjp-final-project-emb-ai/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   ├── mywebscript.js
│   └── style.css
├── templates/
│   └── index.html
├── test_emotion_detection.py
├── server.py
└── README.md
```

---

### Setup and Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rashigunadawar24/oaqjp-final-project-emb-ai.git
   cd oaqjp-final-project-emb-ai
   ```

2. **Install required dependencies:**
   ```bash
   python3 -m pip install requests flask pylint
   ```

3. **Run Unit Tests:**
   ```bash
   python3 test_emotion_detection.py
   ```

4. **Start the Flask Application:**
   ```bash
   python3 server.py
   ```
   Open your browser and navigate to `http://localhost:5000` to interact with the application.

---

### Static Code Analysis
Run `pylint` to check code quality:
```bash
pylint server.py
```
*Current Rating: **10.00/10***
