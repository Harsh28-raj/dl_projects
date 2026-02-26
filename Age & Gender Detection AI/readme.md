🚀 Age & Gender Detection AI (Deep Learning Project)

A deep learning–based web application that predicts age and gender from a human face image using Convolutional Neural Networks (CNN) and Computer Vision.

This project demonstrates an end-to-end AI pipeline:

Dataset → Model Training → Face Detection → Prediction → Web App Deployment

🌐 Live Demo

Deployed App:
https://supereligible-katina-inattentively.ngrok-free.dev/

Upload a face image and the model predicts:

🎂 Age

🧑 Gender

📌 Project Overview

This project uses deep learning and computer vision to build a real-time AI system that detects age and gender from facial images.

The system:

Takes an input image

Detects face using OpenCV

Processes image

Predicts age and gender using CNN

Displays result via web app

🧠 Tech Stack

Python

TensorFlow / Keras

OpenCV

Streamlit (Web App)

NumPy

Google Colab

📂 Dataset Used

UTKFace Dataset
Contains 20k+ face images labeled with:

Age

Gender

Ethnicity

Dataset format:

age_gender_race_date.jpg

Example:

25_0_2_201701161745.jpg
🏗 Model Architecture

Custom CNN model with:

Convolution layers

MaxPooling

Dense layers

Multi-output prediction:

Age (Regression)

Gender (Binary classification)

Outputs:

Age → numerical value

Gender → Male/Female

Loss functions:

Age → MAE

Gender → Binary Crossentropy

⚙️ Features

✔ Upload image
✔ Automatic face detection
✔ Age prediction
✔ Gender prediction
✔ Web-based UI
✔ End-to-end deep learning pipeline

🖥 How to Run Locally
1️⃣ Clone repo
git clone https://github.com/Harsh28-raj/dl_projects.git
cd Age & Gender Detection AI
2️⃣ Install requirements
pip install -r requirements.txt
3️⃣ Run app
streamlit run app.py
📸 Demo Screenshot

(You can add screenshot here later)

📊 Future Improvements

Improve age prediction accuracy

Use pretrained models (MobileNet/EfficientNet)

Better UI

Multiple face detection

Deploy permanently on cloud

Model optimization

🎯 Learning Outcomes

From this project I learned:

CNN model building

Multi-output neural networks

Image preprocessing

Face detection using OpenCV

Model deployment using Streamlit

Real-world AI pipeline

👨‍💻 Author

Harsh Raj
AI/ML & Deep Learning Enthusiast

GitHub:
https://github.com/Harsh28-raj

⭐ If you like this project

Star the repo and connect with me.
