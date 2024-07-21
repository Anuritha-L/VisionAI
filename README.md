# VisionAI: Enhancing Situational Awareness for Visually Impaired Individuals

VisionAI is an advanced assistive system designed to help visually impaired individuals navigate and understand their surroundings with greater independence and safety. This system leverages state-of-the-art artificial intelligence technologies to provide real-time environmental awareness and interaction.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Hardware Setup](#hardware-setup)
- [Software Setup](#software-setup)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Visually impaired individuals face significant challenges in navigating and understanding their surroundings, which impacts their independence and quality of life. Traditional aids like white canes and guide dogs offer limited assistance and lack real-time environmental awareness. VisionAI addresses these challenges with a sophisticated system comprising a wearable camera, a Bluetooth-connected mobile app, and advanced AI models for object detection, depth estimation, image captioning, and Optical Character Recognition (OCR).

## Features
- **Real-time Object Detection**: Identifies and labels objects and obstacles in the user's path.
- **Depth Estimation**: Measures the distance to objects, providing essential spatial information.
- **Image Captioning**: Generates descriptive text for each frame.
- **Optical Character Recognition (OCR)**: Extracts text from the environment.
- **Voice Interaction**: Provides audio feedback and supports voice commands.
- **Interactive Environment Querying**: Uses Visual Question Answering (VQA) techniques for context-specific responses.

## Installation

### Prerequisites
- Python 3.7+
- TensorFlow
- Keras
- OpenCV
- PyTorch
- MongoDB
- Bluetooth API for Python
- Text-to-Speech (TTS) engine
- Speech-to-Text (STT) engine

### Clone the Repository
```bash
git clone https://github.com/your-username/VisionAI.git
cd VisionAI
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

## Usage

### Hardware Setup
1. **Wearable Camera**: Mount a high-resolution camera on eyeglasses to capture real-time video data.
2. **Smartphone/Tablet**: Use a device running the VisionAI app, connected to the camera via Bluetooth.

### Software Setup
1. **Start the MongoDB Server**: Ensure your MongoDB server is running.
2. **Run the Application**:
    ```bash
    python main.py
    ```
3. **Connect the Wearable Camera**: Pair your wearable camera with your smartphone or tablet via Bluetooth.

### Configuration
Modify the `config.json` file to set up the paths and parameters for different modules (object detection, image captioning, OCR, etc.).

## Results

### Performance Analysis
VisionAI's performance is evaluated based on the speed and accuracy of different tasks such as image captioning, object detection, depth estimation, OCR, and speech recognition. Detailed performance metrics are available in the results section of the documentation.

