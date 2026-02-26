🚀 Age & Gender Detection AI (Deep Learning Project)

A deep learning–based web application that predicts age and gender from a human face image using CNN and Computer Vision.

This project demonstrates a complete AI pipeline:
Dataset → Training → Face Detection → Prediction → Web Deployment

🌐 Live Demo

Deployed App:
https://supereligible-katina-inattentively.ngrok-free.dev/

Upload any face image and the model predicts:

🎂 Age

🧑 Gender

📌 Project Overview

This project uses deep learning and computer vision to build a real-time AI system that detects age and gender from facial images.

Pipeline:

Upload image

Detect face using OpenCV

Preprocess image

CNN predicts age & gender

Result shown in web app

🧠 Tech Stack

Python

TensorFlow / Keras

OpenCV

Streamlit

NumPy

Google Colab

📂 Dataset Used

UTKFace Dataset (20k+ images)

Each image contains:

Age

Gender

Ethnicity

Example filename format:
25_0_2_201701161745.jpg

🏗 Model Architecture

Custom CNN with multi-output prediction:

Convolution layers

MaxPooling layers

Dense layers

Two outputs:

Age (Regression)

Gender (Binary classification)

Loss Functions

Age → MAE

Gender → Binary Crossentropy

⚙️ Features

✔ Upload image
✔ Face detection (OpenCV)
✔ Age prediction
✔ Gender prediction
✔ Streamlit web interface
✔ End-to-end deep learning project

🖥 Run Locally
1. Clone Repository

git clone https://github.com/Harsh28-raj/dl_projects.git

cd "Age & Gender Detection AI"

2. Install Requirements

pip install -r requirements.txt

3. Run App

streamlit run app.py

📊 Future Improvements

Improve age prediction accuracy

Use pretrained models (MobileNet/EfficientNet)

Multi-face detection

Better UI

Deploy permanently on cloud

Model optimization

🎯 Learning Outcomes

CNN model building

Multi-output neural networks

Image preprocessing

Face detection using OpenCV

Model deployment with Streamlit

Real-world AI pipeline

👨‍💻 Author

Harsh Raj
AI/ML & Deep Learning Enthusiast

GitHub:
https://github.com/Harsh28-raj

⭐ Support

If you like this project, star the repo and connect with me.
