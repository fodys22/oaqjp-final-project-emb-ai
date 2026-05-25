# Emotion Detector project

An AI-based web application that leverages the Watson NLP library and Flask framework to analyze the emotional tone of text statements. The application detects multiple emotional vectors including anger, disgust, fear, joy, and sadness, and highlights the dominant emotion

## Project Structure is

- `EmotionDetection/`: Python package containing the core logic.
  - `__init__.py`: Initializes the package and handles module imports
  - `emotion_detection.py`: Interacts with the Watson NLP API and formats responses.
- `server.py`: Flask application hosting the web interface and routing API endpoints.
- `test_emotion_detection.py`: Unit tests using the `unittest` framework to validate engine accuracy.
- `templates/`: Contains HTML files for the front-end user interface.
- `static/`: Contains CSS and JavaScript static assets for formatting.

## Features are

- **Watson NLP Integration:** Real-time emotion prediction from user-submitted text inputs.
- **RESTful API Endpoint:** Accessible data metrics routed through the `/emotionDetector` query string.
- **Error Handling:** Built-in robustness that intercepts blank entries or status code 400 errors safely
- **PEP8 Compliant:** Structured and linted utilizing static code analysis to maintain 10.00/10 code quality ratings.

## How to Run it

1. Clone the repository to your environment.
2. Ensure required dependencies (`flask`, `requests`, `pylint`) are installed.
3. Run the application controller:
   ```bash
   python3 server.py