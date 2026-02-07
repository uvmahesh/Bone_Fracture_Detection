 Bone Fracture Detection using Deep Learning

Project Overview :-

This project focuses on automatic bone fracture detection from X-ray images using Deep Learning techniques. The goal is to assist doctors and radiologists by providing a fast and accurate preliminary diagnosis.

A Convolutional Neural Network (CNN) model is trained to classify X-ray images as fractured or normal, and the system supports real-time predictions after deployment.

Features :-

Detects bone fractures from X-ray images

Image preprocessing and augmentation

Deep learning–based classification

Model evaluation using multiple metrics

Real-time image prediction

Easy-to-use and deployable system

Technologies Used :-

Python

TensorFlow / Keras

NumPy

Pandas

Matplotlib & Seaborn

OpenCV

FastAPI (for backend API)

GitHub (version control)

Dataset :-

Publicly available Kaggle bone fracture dataset

Contains labeled X-ray images:

Fractured

Normal

Dataset is preprocessed using resizing, normalization, and augmentation techniques

Model Architecture :-

Custom Convolutional Neural Network (CNN)

Layers include:

Convolutional layers

MaxPooling layers

Dropout for regularization

Fully connected dense layers

Optimizer: Adam

Loss function: Binary Crossentropy

Model Evaluation :-

The model is evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

The trained model shows good generalization performance on unseen test data.

Sample Output :-

Input: X-ray image

Output:

Fractured / Normal

Prediction confidence score

Installation & Setup (code):-

git clone https://github.com/your-username/bone-fracture-detection.git
cd bone-fracture-detection
pip install -r requirements.txt
