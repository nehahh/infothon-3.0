# infothon-3.0

#Overview
This project is a web-based application that predicts diseases based on user-entered symptoms. The system uses a machine learning model (Support Vector Classifier) trained on a dataset of symptoms and diseases. It also provides additional information such as precautions, medications, workouts, and diets for the predicted disease.

#Features
Predict diseases based on user symptoms.
Display disease description.
Provide precautions, medications, workouts, and diets for the predicted disease.
Technologies Used
Python
Flask
Streamlit
Pandas
Scikit-learn
HTML/CSS (for web templates)

├── dataset
│   ├── Training.csv
│   ├── precautions_df.csv
│   ├── workout_df.csv
│   ├── description.csv
│   ├── medications.csv
│   ├── diets.csv
├── models
│   └── svc.pkl
├── templates
│   ├── index.html
│   ├── about.html
│   ├── contact.html
│   ├── developer.html
│   ├── blog.html
├── app.py
├── train_model.py
├── requirements.txt
└── README.md

This README file should provide a good starting point for understanding, setting up, and running your disease prediction system.
