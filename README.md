# Emotion & Soft Skills Tracker Bot

## Overview
This project involves a real-time bot that tracks and analyzes emotions, soft skills, and speech using webcam and microphone input. It leverages computer vision, speech recognition, and sentiment analysis to provide feedback on mental health and soft skills. The bot can be used for mental health assessment and improvement, as well as for recruitment processes to evaluate candidates' soft skills.

## Features
- **Emotion Detection**: Tracks dominant emotions using DeepFace's emotion analysis and displays them on the webcam feed.
- **Soft Skills Analysis**: Uses sentiment analysis to evaluate speech and provide insights into soft skills.
- **Confidence Detection**: Assesses if the user is looking straight into the camera, indicating confidence.
- **Real-Time Feedback**: Provides real-time feedback on emotions, speech, and soft skills during the interaction.
- **Recording & Sharing**: Allows the user to start and stop video recording and capture emotions and speech data.

## Tech Stack
- **DeepFace**: For emotion detection using facial analysis.
- **SpeechRecognition**: For transcribing audio to text in real-time.
- **Transformers (HuggingFace)**: For sentiment analysis to track soft skills.
- **OpenCV**: For video capture, face detection, and real-time display.
- **Python**: The main programming language used for implementation.
- **Threading**: For simultaneous video capture and audio transcription.

## Installation

To run the bot, ensure you have the following libraries installed:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/emotion-soft-skills-tracker.git
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Make sure you have OpenCV, DeepFace, and HuggingFace libraries installed:
    ```bash
    pip install opencv-python deepface transformers speechrecognition
    ```

## Usage

1. Run the bot using:
    ```bash
    python main.py
    ```

2. Press `s` to start the video recording.
3. Press `q` to stop the video recording.
4. Press `c` to capture emotion analysis from the video.

## Future Plans
- Integration with NGOs for mental health tracking and providing necessary support.
- Addition of a **Healing Bot** for real-time emotional support.
- Improvement of emotion analysis with multiple models and expanded feedback mechanisms.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [DeepFace](https://github.com/serengil/deepface)
- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/)
- [Transformers by HuggingFace](https://huggingface.co/)
- [OpenCV](https://opencv.org/)
