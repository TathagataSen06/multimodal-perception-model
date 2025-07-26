# Ultimate Multimodal Perception System
A sophisticated, browser-based AI application that uses real-time data from your webcam and microphone to perceive, understand, and interact with its environment. This project demonstrates a powerful fusion of computer vision, speech recognition, and voice synthesis in a futuristic, command-center-style interface.

✨ Features
This application is packed with advanced features that showcase a wide range of modern web and AI capabilities:

Real-Time Object Detection: Identifies 80 common objects from the COCO dataset directly in the live video feed using TensorFlow.js.

Multiple Vision Modes: Cycle through three distinct visual filters for the video feed:

Normal: Unaltered video.

Night Vision: A green monochrome filter that enhances brightness and contrast for low-light conditions.

Thermal Vision: A false-color filter that mimics a thermal imaging camera.

Motion Heatmap: A visual layer that leaves a fading "heat" trail where object motion is detected, providing a history of movement.

Multilingual Speech Recognition: Recognizes voice commands in multiple languages, including English, Hindi, Spanish, and French.

Voice Command Control: Control the application hands-free. Commands include:

start system / stop system

night vision on / thermal vision on / normal vision on

take photo / snapshot

clear logs

Voice Synthesis Feedback: The system speaks back to you, announcing detected objects and confirming executed commands.

Text Command Console: A terminal-style input for typing commands as an alternative to voice.

Snapshot Functionality: Instantly capture and download a PNG image of the current video frame via a button or voice command.

Enhanced Real-Time Logging: Two separate, categorized logs for Vision and Audio/System events, providing clear, timestamped feedback.

UI Personalization: The system remembers your last-used language and vision mode settings in your browser's local storage.

🛠️ Tech Stack
This project is built entirely with front-end technologies, running locally in your browser without needing a backend server.

Core: HTML5, CSS3, JavaScript (ES6+)

Styling: Tailwind CSS

AI / Machine Learning: TensorFlow.js

Object Detection Model: COCO-SSD

Browser APIs:

Web Speech API (SpeechRecognition)

Web SpeechSynthesis API (Voice Feedback)

MediaDevices/getUserMedia (Camera/Microphone Access)

🚀 Getting Started
Prerequisites
A modern web browser. Google Chrome is highly recommended for the best performance and full support of the Web Speech API.

A working webcam and microphone.

Installation & Usage
Save the Code: Save the complete application code as a single index.html file.

Open in Browser: Open the index.html file directly in Google Chrome.

Grant Permissions: When prompted by the browser, you must allow access to your camera and microphone for the application to function.

Start the System:

Wait for the AI model to load (the "Vision" status will turn green).

Click the "Start System" button, or use the voice command "start system".

Interact:

Use the dropdowns to change the language or vision mode.

Use voice commands or the text console to control the application.

Click the "Snapshot" button to save an image.

This project was developed to showcase advanced browser-based AI capabilities.
