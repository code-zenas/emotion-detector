# Emotion Detector Application

## Project Overview

This project is an AI-based Emotion Detection web application developed using the Watson NLP library and Flask framework.

The application analyzes the emotion expressed in a text statement and detects the dominant emotion among:

- Joy
- Anger
- Disgust
- Fear
- Sadness

The project includes:

- Emotion detection using Watson NLP
- Flask web deployment
- Error handling
- Unit testing
- Static code analysis using pylint

---

## Technologies Used

- Python
- Flask
- Watson NLP
- Requests
- unittest
- pylint

---

## Project Structure

```bash
emotion-detector/
│
├── README.md
├── server.py
├── requirements.txt
├── test_emotion_detection.py
│
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
│
├── screenshots/
│   ├── 6b_deployment_test.png
│   └── 7c_error_handling_interface.png
```

---

## Features

- Detects emotions from user input
- Returns dominant emotion
- Handles invalid input errors
- Includes unit testing
- Achieves 10/10 pylint score

---

## Running the Application

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Flask server:

```bash
python3 server.py
```

Open browser:

```bash
http://localhost:5000
```

---

## Example Output

Input:

```text
I am very happy today
```

Output:

```text
The dominant emotion is joy.
```

---

## Author

Geenesh Acharya
