# face-rec-voting-system
FYP- Facial Recognition System in Voting System

# Face Recognition Voting System 🗳️🤖

## 📌 Project Overview
This project is a **facial recognition-based voting system** using **YOLOv8n** for face detection and **FaceNet** for face recognition. It ensures secure and unique voting by identifying registered users via face ID.

## 🚀 Features
- ✅ Real-time face detection using YOLOv8n  
- ✅ Face recognition using FaceNet embeddings  
- ✅ Secure voting system with one-person-one-vote  
- ✅ Web-based interface (FastAPI/Django) for registration & voting  

## 🔧 Tech Stack
- **Backend**: Python, FastAPI/Django  
- **Face Detection**: YOLOv8n (Ultralytics)  
- **Face Recognition**: FaceNet (TensorFlow/PyTorch)   
- **Frontend (Optional)**: HTML + Bootstrap  

## 📂 Project Structure
📁 face-recognition-system
│── 📂 backend          # Django backend (handles face recognition logic)
│   │── 📂 face_recognition  # YOLOv8n & FaceNet processing
│   │   │── detector.py      # YOLOv8n face detection logic
│   │   │── recognizer.py    # FaceNet face recognition logic
│   │── 📂 users        # User authentication & face ID management
│   │   │── models.py   # User model (stores face embeddings)
│   │   │── views.py    # User authentication views (login/register)
│   │   │── models.py   # User model (stores face embeddings)
│   │   │── views.py    # User authentication views (login/register)
│   │── settings.py
│   │── manage.py       # Django project entry point
│   │── requirements.txt # Python dependencies
│
│── 📂 frontend         # Django + Bootstrap web UI
│   │── 📂 static       # CSS, JS, images
│   │   │── styles.css  # Custom styles (if needed)
│   │── 📂 templates    # HTML templates for web pages
│   │   │── base.html   # Main Bootstrap template
