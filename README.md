# FemAlert: AI-Powered Women Safety Analytics System
## Introduction
FemALert is an advanced real-time threat detection system designed to enhance women's safety using AI-driven analytics. It leverages computer vision, machine learning, and real-time alert mechanisms to identify potential threats and suspicious activities.

## Features
 Real-Time Anomaly Detection – Identifies unusual behavior to alert authorities.
🔹 **Person Detection & Gender Classification** – Counts and classifies individuals in an area.

🔹 **Lone Woman Detection at Night** – Detects women walking alone in unsafe conditions.

🔹 **Surrounding Threat Analysis** – Identifies when a woman is surrounded by a group of men.

🔹 **Gesture-Based SOS Recognition** – Recognizes emergency signals like hand gestures for distress.

## Tech Stack
**Machine Learning & Computer Vision**

**Object & Person Detection**:
YOLOv8 (Real-time person detection, gender classification)

**Gesture Recognition & SOS Detection**:
OpenPose (Pose estimation for distress gestures)
MediaPipe (Lightweight alternative for hand/face keypoint detection)

**Frameworks**: Scikit-Learn, TensorFlow, OpenCV

## How It Works
-Real-time video feed processing through an AI-powered surveillance system.

-Threat detection & anomaly analysis using trained ML models.

-Automated alerts & notifications sent to emergency contacts or authorities.

-Live data visualization to track unsafe areas.
