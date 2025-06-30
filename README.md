# pehchan-ai-drdo
# Pehchan AI - Real-Time Age & Gender Prediction

**Pehchan AI** is a machine learning-based application that uses a webcam to detect faces and predict both **age categories** and **gender** in real-time. Built using Python, OpenCV, and TensorFlow, this project provides a simple and efficient way to perform live predictions using a pre-trained `.keras` model.
## 🎯 Project Objective
The goal of this project is to demonstrate a real-time AI system that:
- Detects faces from a live webcam feed
- Predicts the **gender** (Male/Female)
- Predicts the **age category** (e.g., Child, Teen, Adult, Senior)
- Displays results on the screen with smooth UI feedback

## 🚀 How to Run the Project

### 1. Clone the Repository
git clone https://github.com/yourusername/Pehchan-AI.git
make sure to unzip the pH(3)folder unzip it then start implementing

 Install Required Libraries
Make sure you have Python 3.7+ installed. Then install dependencies:
pip install opencv-python numpy tensorflow keras-core

we can also run:pip install -r ../requirements.txt

Run the Application
Use the following command to start the real-time prediction:
python -u enhanced_app.py
This will launch your system’s default webcam and start displaying the predictions on the video stream.

🧠 Model Details
Format: .keras
Framework: TensorFlow / Keras
Input: Detected face images from webcam frames

Output:
Gender: Binary classification - Male or Female
Age: Multi-class classification - Age groups (e.g., 0–12, 13–19, 20–40, 40+)
