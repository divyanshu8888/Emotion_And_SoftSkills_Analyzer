# Emotion & Soft Skills Analyzer

## Overview
The **Emotion & Soft Skills Analyzer** is a real-time bot designed to track and analyze emotions, soft skills, and speech. Using webcam and microphone input, this bot provides valuable feedback about an individual's emotional state, soft skills, and confidence. The application is useful for both **mental health assessments** and **recruitment processes**. It leverages computer vision, speech recognition, and sentiment analysis to offer real-time feedback on mental health and soft skills.

## Features
- **Emotion Detection**: Tracks dominant emotions in real-time using DeepFace’s emotion analysis and displays them on the webcam feed.
- **Soft Skills Analysis**: Uses sentiment analysis to evaluate speech and provide insights into soft skills.
- **Confidence Detection**: Assesses if the user is looking straight into the camera, indicating confidence.
- **Real-Time Feedback**: Offers continuous feedback on emotions, speech, and soft skills during the interaction.
- **Recording & Sharing**: Allows users to start and stop video recording, and capture emotions and speech data that can be shared for mental health consultation or recruitment evaluations.

## Tech Stack
- **DeepFace**: For emotion detection using facial analysis.
- **SpeechRecognition**: For transcribing audio to text in real-time.
- **Transformers (HuggingFace)**: For sentiment analysis to track soft skills.
- **OpenCV**: For video capture, face detection, and real-time display.
- **Python**: The primary programming language used for implementation.
- **Threading**: For simultaneous video capture and audio transcription.

## Installation

To run the bot, ensure you have the following libraries installed:

1. Clone the repository:
    ```bash
    git clone https://github.com/divyanshu8888/Emotion_And_SoftSkills_Analyzer.git
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

2. **Controls**:
    - Press `s` to start the video recording.
    - Press `q` to stop the video recording.
    - Press `c` to capture emotion analysis from the video.

## Future Plans
- **NGO Integration**: Connect with mental health NGOs for real-time emotional support and consultation.
- **Healing Bot**: Add a healing bot feature for providing real-time emotional support.
- **Emotion Analysis Enhancement**: Implement multiple emotion detection models for better accuracy and feedback.
- **Expand Soft Skills Analysis**: Improve soft skills analysis with more sophisticated models for evaluating communication, confidence, and leadership.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [DeepFace](https://github.com/serengil/deepface) - Facial recognition and emotion detection library.
- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/) - Speech-to-text library.
- [Transformers by HuggingFace](https://huggingface.co/) - Pre-trained sentiment analysis models.
- [OpenCV](https://opencv.org/) - Open-source computer vision library.
