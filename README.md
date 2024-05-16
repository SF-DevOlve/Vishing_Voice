# Voicebot for testing vishing
![Voicebot Icon]([https://cdn-icons-png.flaticon.com/512/8090/8090687.png](https://nordvpn.com/wp-content/uploads/blog-social-what-is-vishing-1200x628-1.png))
## Overview
This project aims to develop a voice-based interaction system (voicebot) using Python, Flask, and various other libraries for handling audio processing, speech recognition, and database operations. The voicebot is designed to recognize spoken commands in multiple languages (English, French, Arabic) and perform corresponding actions based on the detected commands.

## Features
- Recognize spoken commands in multiple languages: English, French, Arabic.
- Perform actions based on recognized commands, such as retrieving information from a database or executing specific tasks.
- Utilize different speech recognition providers (e.g., Google Speech Recognition, Vosk) for improved accuracy and flexibility.
- Support for handling audio data in Base64 format, enabling integration with various platforms and applications.

## Technologies Used
- **Python**: Programming language used for the backend development.
- **Flask**: Web framework used for building the RESTful API.
- **SpeechRecognition**: Python library for speech recognition.
- **Pyttsx3**: Python library for text-to-speech conversion.
- **PyMySQL**: Python library for MySQL database operations.
- **Flask-CORS**: Flask extension for handling Cross-Origin Resource Sharing (CORS).
- **Base64**: Python library for encoding and decoding Base64 data.
- **Pydub**: Python library for audio processing and manipulation.

## Usage
1. Install the required Python libraries listed in the `requirements.txt` file.
2. Ensure that you have a MySQL database set up with appropriate tables for storing commands and categories.
3. Run the Flask application (`app.py`).
4. Send POST requests to the `/voicebot` endpoint with JSON data containing the Base64-encoded audio data, provider information, and language settings.

## Contributors
- [itsmeismaill] - [oukhauar@gmail.com]
