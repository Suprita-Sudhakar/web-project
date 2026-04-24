# web-project
# EduHealth-AI
## AI-Based Multi-Domain Prediction and Classification System Using Django
# Description
This project is a web-based application developed using Django and Machine Learning. 
It includes three main modules: Placement Prediction, Migraine Prediction, and Music Instrument Classification. 
The system helps users predict outcomes based on input data and provides intelligent results using trained ML models.

# Technologies Used
- Python
- Django
- HTML, CSS
- Machine Learning (Scikit-learn)
- Deep Learning (TensorFlow/Keras)
- SQLite Database

# Features
- User Login & Signup System
- Placement Prediction Module
- Migraine Prediction Module
- Music Instrument Classification using CNN
- Simple and user-friendly interface

# 📂 Project Structure

project/
│── manage.py  
│── db.sqlite3 
│── GUI/                     # Main Django project
│   │── settings.py  
│   │── urls.py  
│── basics/                  # Application module
│   │── models.py  
│   │── views.py  n
│   │── urls.py  
│   │── tests.py  
│── templates/               # HTML templates  
│── static/                  # CSS, JS, Images  
│── media/                   # Uploaded files  
│── dataset/                 # Machine learning datasets  
│── models/                  # Saved ML models  


### 1. Placement Prediction
This module predicts whether a student will be placed or not. If placed, it estimates salary; if not, it gives improvement suggestions based on performance.
### 2. Migraine Prediction
Analyzes user health-related data to predict the possibility of migraine.

### 3. Music Instruments Classification
Uses a Convolutional Neural Network (CNN) to classify different musical instruments from images.

## 📸 Screenshots
<img width="1366" height="768" alt="Screenshot (49)" src="https://github.com/user-attachments/assets/6cdcbcd6-4a8b-418f-ad82-28235ac86fe0" />


