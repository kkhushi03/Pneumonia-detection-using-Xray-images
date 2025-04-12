# Pneumonia Detection 🫁

This project implements a Convolutional Neural Network (CNN) for detecting pneumonia in chest X-ray images. It is deployed on Hugging Face using Gradio, offering a simple interface for users to upload X-ray images and receive predictions in real time.

## Key Features
- Real-time Prediction: Upload chest X-ray images to instantly receive predictions on whether pneumonia is detected or not.

- User-friendly Interface: The model is integrated with Gradio, making it easy to interact with and test the model via a web interface.

- Pretrained CNN Model: The model is trained on a large dataset of X-ray images, providing robust performance for pneumonia detection.

## Model Overview
- Model Type: Convolutional Neural Network (CNN)

-Input: Grayscale images of size (299, 299, 1)

- Output: Binary classification - "Pneumonia Detected" (1) or "No Pneumonia Detected" (0)

- Framework: TensorFlow/Keras
