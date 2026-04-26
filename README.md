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
- Machine Learning Algorithms
- Deep Learning (TensorFlow/Keras)
- SQLite Database

# Features
- User Login & Signup System
- Placement Prediction Module
- Migraine Prediction Module
- Music Instrument Classification using CNN
- Simple and user-friendly interface
- checks accuracy score compare with different algorithms

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
I used multiple algorithms like Random-Forest, KNN, and Naive-Bayes, compared their accuracy, and selected the best model. It predicts placement, salary if placed, and gives suggestions if not.
### 2. Migraine Prediction
Analyzes user health-related data to predict the possibility of migraine.
### 3. Music Instruments Classification
Uses a Convolutional Neural Network (CNN) to classify different musical instruments from images.

## Author
**Your Name**
SUPRITA SUDHAKAR
---

## Future Improvements
- Enhance UI/UX design  
- Add more prediction modules  
- Improve model accuracy  
- Deploy the application on cloud platforms (AWS/Heroku)  



