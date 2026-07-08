# Image Recognition Model Task

This project is a Deep Learning task designed to classify images into two main categories: **Linear** and **Circular**. 

## 🛣️ Project Workflow
The project was developed through the following steps:
1. **Data Collection & Training:** The pipeline started on **Teachable Machine**, where a custom dataset was gathered and structured into two classes: `Linear` and `Circular`. A collection of sample images was uploaded for each class to train the vision model.
2. **Model Export:** Once trained, the trained weights were exported as a Keras model (`keras_model.h5`) along with its respective `labels.txt`.
3. **Inference & Testing:** A Python script was developed using `tf_keras` and `Pillow` to load the trained model, preprocess new test images, and validate the prediction accuracy locally.

## 🚀 Features
- **Binary Classification:** Accurately distinguishes between **Linear** and **Circular** shapes in images.
- **Data-Driven:** Trained on a dedicated dataset compiled specifically for this task.
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
