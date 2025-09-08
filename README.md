🧠 Image Classification using TensorFlow (MNIST Dataset)
📌 Project Overview

This project demonstrates an image classification model built using TensorFlow and Keras.
The model is trained on the MNIST dataset, which consists of 70,000 grayscale images of handwritten digits (0–9).
The goal is to correctly classify the handwritten digits into their respective categories.

🚀 Features

Uses TensorFlow & Keras for deep learning.

Implements a Neural Network for classification.

Trained on the MNIST dataset (60,000 training, 10,000 testing images).

Achieves high accuracy in recognizing handwritten digits.

Visualization of sample images and training progress.

📂 Project Structure
📁 Tensorflow_project
 ├── Tensorflow_project_Image_Classification.ipynb   # Jupyter notebook with code
 ├── requirements.txt                                # Dependencies
 └── README.md                                       # Project documentation

📊 Dataset Information

Name: MNIST Handwritten Digit Dataset

Size: 70,000 images (28x28 pixels, grayscale)

Classes: 10 (digits from 0 to 9)

Source: Yann LeCun’s MNIST database

⚙️ Installation & Setup

Clone this repository:

git clone https://github.com/Sameer060405/Image_Classification_TensorFlow.git
cd Image_Classification_TensorFlow


Install dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook:

jupyter notebook Tensorflow_project_Image_Classification.ipynb

📈 Model Pipeline

Import Libraries → TensorFlow, NumPy, Matplotlib

Load Dataset → tensorflow.keras.datasets.mnist

Preprocess Data → Normalize pixel values (0–255 → 0–1)

Build Model → Neural Network with Keras Sequential API

Compile Model → Optimizer (Adam), Loss (Sparse Categorical Crossentropy), Metric (Accuracy)

Train Model → Fit on training set with validation

Evaluate Model → Test on unseen data

Visualize Results → Plot predictions and training history

📷 Sample Output

Training accuracy/loss plots

Predicted vs actual digit examples

📌 Requirements

The project requires:

tensorflow>=2.0.0

numpy

matplotlib

(Already listed in requirements.txt)
