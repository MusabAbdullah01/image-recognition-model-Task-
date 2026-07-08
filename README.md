# Image Recognition Model Task

This project is a Deep Learning task designed to classify images into two main categories: **Linear** and **Circular**. Using a pre-trained Keras/TensorFlow model, the script processes an input image and determines which category it belongs to with a high level of confidence.

## 🚀 Features
- **Binary Classification:** Accurately distinguishes between **Linear** and **Circular** shapes in images.
- **Fast Preprocessing:** Image resizing and center-cropping using `Pillow`.
- **Confidence Scoring:** Displays the predicted class along with the model's prediction confidence score.

## 📋 Requirements
Before running the script, make sure you install the required dependencies:
`pip install tensorflow tf_keras pillow numpy `

## 🛠️ How to Use
Clone or download this repository.

Make sure keras_model.h5, labels.txt, and your test image (test_image.png) are in the same folder.

Run the prediction script.

## 📊 Sample Output
When feeding a circular shape image, the expected output structure is:
Class: circular
Confidence Score: 0.9967167
