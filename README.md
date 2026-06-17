📌 Project Overview

The Sign Language Detection System is a computer vision and machine learning-based application that recognizes hand gestures in real time and converts them into readable text. The system aims to bridge the communication gap between hearing/speech-impaired individuals and people who do not understand sign language.

Using a webcam, the system detects hand landmarks through Mediapipe, extracts relevant features, and classifies gestures using machine learning models such as K-Nearest Neighbors (KNN) or Support Vector Machines (SVM). The detected signs are then displayed as text on the screen.

The project is designed with future integration in mind and can be developed into a browser extension or desktop application that provides live subtitles during video calls, online meetings, and educational sessions.

🎯 Objectives
Detect sign language gestures in real time.
Convert gestures into readable text.
Improve communication accessibility.
Generate subtitles from detected signs.
Support emergency communication scenarios.
Provide a scalable and modular architecture for future enhancements.
✨ Features
Real-Time Video Capture using webcam
Hand Landmark Detection using Mediapipe
Gesture Feature Extraction and Normalization
Machine Learning-Based Sign Classification
Sign-to-Text Conversion
Live Subtitle Generation
Video Call Accessibility Support
Emergency Gesture Recognition
Custom Dataset Training
Voice Output Support (Future Scope)
Multilingual Extension Support
Modular and Scalable Architecture
🏗️ System Architecture

The system consists of the following modules:

1. Video Capture Module

Captures live video frames from the webcam.

2. Hand Detection Module

Detects hand landmarks using Mediapipe.

3. Feature Extraction Module

Extracts landmark coordinates and converts them into feature vectors.

4. Classification Module

Uses machine learning models to classify gestures.

5. Text Generation Module

Converts classified signs into readable text.

6. Subtitle Generation Module

Displays recognized signs as subtitles on screen.

7. Emergency Alert Module

Detects emergency gestures and triggers alerts.

🛠️ Technologies Used
Technology	Purpose
Python	Core Programming
OpenCV	Video Processing
Mediapipe	Hand Tracking
NumPy	Numerical Operations
Scikit-learn	Machine Learning
Pickle	Model Storage
Tkinter (Optional)	GUI Development
📂 Project Structure
Sign-Language-Detection/
│
├── data/
│   ├── collect_imgs.py
│   ├── create_dataset.py
│
├── models/
│   ├── model.p
│
├── src/
│   ├── inference_classifier.py
│   ├── train_classifier.py
│
├── README.md
├── requirements.txt
└── LICENSE
🚀 Future Enhancements
Live Subtitle Extension

The system can be integrated with:

Google Meet
Zoom
Microsoft Teams
YouTube Live

to provide real-time subtitles generated from sign language.

Emergency Communication System

Special emergency signs such as:

HELP
DANGER
CALL
MEDICAL EMERGENCY

can trigger:

SMS alerts
Email notifications
Emergency pop-ups
Audible alarms
