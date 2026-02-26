# 🚀 Age & Gender Detection AI — Deep Learning Web App

An end-to-end deep learning system that predicts **age and gender from facial images** using CNN and computer vision, deployed as a live web application.

This project demonstrates a real-world AI pipeline from training to deployment.

---

## 🌐 Live Demo  
**Web App:**  
https://supereligible-katina-inattentively.ngrok-free.dev/

Upload any face image → model predicts:
- Age  
- Gender  

---

## 🧠 Project Highlights
- Built and trained custom CNN on UTKFace dataset (20k+ images)  
- Multi-output model (age regression + gender classification)  
- Real-time face detection using OpenCV  
- Streamlit web app deployment  
- End-to-end deep learning pipeline  

---

## ⚙️ Tech Stack
**Deep Learning:** TensorFlow, Keras  
**Computer Vision:** OpenCV  
**Frontend/Web:** Streamlit  
**Language:** Python  
**Environment:** Google Colab  

---

## 🏗 Model Details
Multi-output CNN architecture:

- Convolution + MaxPooling layers  
- Dense layers  
- Two outputs:
  - Age prediction (Regression — MAE loss)
  - Gender prediction (Binary classification)

Dataset: **UTKFace Dataset (20k+ images)**

---

## 🧪 How It Works
1. User uploads image  
2. Face detected using OpenCV  
3. Image preprocessed (resize + normalize)  
4. CNN predicts age & gender  
5. Result displayed on web UI  

---

## 💻 Run Locally

Clone repository:
```bash
git clone https://github.com/Harsh28-raj/dl_projects.git
cd "Age & Gender Detection AI"
```

Install requirements:
```bash
pip install -r requirements.txt
```

Run app:
```bash
streamlit run app.py
```

---

## 📊 Current Limitations
- Age prediction not perfectly accurate (complex problem)  
- Single face detection  
- Basic CNN architecture  

---

## 🔥 Future Improvements
- Use pretrained models (MobileNet/EfficientNet)
- Improve age accuracy
- Multi-face detection
- Better UI/UX
- Permanent cloud deployment

---

## 👨‍💻 Author
**Harsh Raj**  
AI & Deep Learning Enthusiast  

GitHub:  
https://github.com/Harsh28-raj

---

## ⭐ Support
If you like this project, consider starring the repository.
