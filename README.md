# Image Recognition Model Task

This project is a Deep Learning task designed to classify images into two main categories: **Linear** and **Circular**. Using a pre-trained Keras/TensorFlow model, the script processes an input image and determines which category it belongs to with a high level of confidence.

## 🚀 Features
- **Binary Classification:** Accurately distinguishes between **Linear** and **Circular** shapes in images.
- **Fast Preprocessing:** Image resizing and center-cropping using `Pillow`.
- **Confidence Scoring:** Displays the predicted class along with the model's prediction confidence score.

## 📋 Requirements
Before running the script, make sure you install the required dependencies:
```bash
pip install tensorflow tf_keras pillow numpy
