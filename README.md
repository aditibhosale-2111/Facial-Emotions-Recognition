# Facial-Emotions-Recognition
Facial Emotions Recognition is a real-time app that uses your webcam to detect faces and recognize emotions like happy, sad, or angry. It uses DeepFace for emotion analysis and OpenCV to show live video with emotion labels. Each face is highlighted with a box and its dominant emotion. Run the script and press 'q' to exit.

Real-Time Facial Emotion Recognition using DeepFace & OpenCV

# Overview:
This project is a real-time facial emotion recognition system that uses your webcam to detect faces and analyze emotions using the DeepFace library. 

It captures live video, detects faces, identifies emotions (like happy, sad, angry, etc.), and displays them directly on the screen — all in real time!

# Features:
•	Real-time face detection via webcam
•	Emotion analysis using DeepFace
•	Uses OpenCV for image processing
•	Efficient detection and emotion labeling
•	Simple, clean, and beginner-friendly Python code

# Technologies Used:
• OpenCV – Access webcam, image display & drawing
• DeepFace – Emotion recognition & face analysis
• NumPy – Image array manipulation

 # Getting Started:
1️⃣ Prerequisites: Make sure you have Python 3.7+ installed.
2️⃣ Install Dependencies: Run the following command in your terminal or command prompt.
3️⃣ Run the Script: Simply execute the Python file to start emotion recognition.

# How It Works:
1.	The webcam starts capturing video frames.
2.	Each frame is analyzed using DeepFace.analyze() to detect emotions.
3.	A bounding box is drawn around the detected face.
4.	The dominant emotion (like happy, sad, neutral, etc.) is displayed above the face.
5.	Press 'q' anytime to quit the application.

# Detected Emotions:
DeepFace can detect the following emotions:
😄 Happy | 😢 Sad | 😠 Angry | 😲 Surprise | 😐 Neutral | 😨 Fear | 🤢 Disgust

# Output Example:
Once the program runs, you’ll see a window displaying the video feed. Each detected face will be highlighted with a box and labeled with its corresponding emotion (e.g., 'Happy'). Press 'q' to exit.

# Cleanup:
The program safely releases the webcam and closes all OpenCV windows after you press 'q'.

# Author:
Aditi Bharat Bhosale
aditibhosale2111@gmail.com


