# Heart-Attack-Prediction-using-Retinal-Eye-Image

# Overview
This project aims to predict the risk of heart attacks using retinal fundus images by applying deep learning techniques. Retinal images offer valuable insights into cardiovascular health, enabling non-invasive, early-stage risk prediction.

# Problem Statement
Early detection of heart attack risk is crucial but traditional diagnostic approaches can be expensive or invasive. This project explores how retinal images — commonly used for eye examinations — can be leveraged to assess potential cardiovascular risks using machine learning.

# Features

Predicts heart attack risk level based on retinal images.
Risk categories:

1) High Risk

2) Moderate Risk

3) Mild Risk

4) Not at Risk

Trained using labeled medical image datasets.

Uses image preprocessing techniques to enhance model accuracy.

# Technologies Used

Python

TensorFlow / Keras

OpenCV

NumPy

Matplotlib

Scikit-learn

# System Architecture

Image Input: Retinal images (fundus photographs).

Image Preprocessing: Resizing, normalization, augmentation.

Model Training: CNN-based architecture.

Prediction: Outputs the heart attack risk category.

# Dataset

Medical retinal images dataset with annotated risk categories.(from Kaggle)

Data split into:

Training Set

Validation Set

Test Set

# How to Run

Clone the repo:

git clone https://github.com/yourusername/heart-attack-risk-prediction.git

Install dependencies:

pip install -r requirements.txt

Run the prediction:

python predict.py --image path_to_retinal_image.jpg

# Results

Achieved good accuracy on test images.

Model demonstrated the ability to classify risk levels effectively from unseen retinal images.

# Future Improvements

Integration with real-time diagnostic systems.

Improved dataset variety and balance.

Deployment as a web app or mobile health assistant.
