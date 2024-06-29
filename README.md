# Pomegranate Disease Detector

Pomegranate Disease Detector is a web application that utilizes deep learning to detect diseases in pomegranate fruit from images. The application is built with Flask and uses a Convolutional Neural Network (CNN) model to classify images of pomegranates into different disease categories.

## Features

- **Image Upload**: Users can upload images of pomegranates.
- **Disease Detection**: The model predicts the disease present in the uploaded image.
- **Interactive UI**: Displays the uploaded image and the predicted disease.

## Tech Stack

- **Backend**: Flask
- **Machine Learning**: TensorFlow, Keras
- **Image Processing**: OpenCV
- **Frontend**: HTML, CSS, JavaScript (jQuery)
- **Supporting Libraries**: NumPy, Matplotlib, Pandas

## Model Details

The model used in this project is an InceptionV3 CNN, fine-tuned to classify pomegranate diseases. The diseases detected by the model include:
- Anthracnose
- Healthy
- Heartrot
- Sample

## Setup Instructions

1. **Clone the repository:**
   ```sh
   git clone (https://github.com/competitiveblood/PomegranateGuard.git)
   cd pomegranate_disease_detection-main

2. **Create and activate a virtual environment:**
```
 python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

3. **Install the dependencies:**
```
pip install -r requirements.txt
```

4. **Run the Flask application:**
```
export FLASK_APP=app.py
export FLASK_ENV=development
flask run
```
**The application will be running at http://127.0.0.1:5000.**
