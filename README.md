---
TITLE: Hand-Gesture-Classifier
AUTHOR: Priyanka Rajeev Hichkad
---

# Hand Gesture Recognition Using Google Teachable Machine

## Overview
This project focuses on building a hand gesture recognition system using Google Teachable Machine. The model is trained to classify different hand gestures using image data and can be used for real-time gesture detection.

The goal of this project is to demonstrate how machine learning models can be created without extensive coding by using an easy-to-use platform like Teachable Machine.

---

# Introduction
Hand gesture recognition is an important application of computer vision and machine learning. It is widely used in areas such as human-computer interaction, sign language recognition, gaming, and virtual reality.

In this project, I built a gesture recognition model using Google Teachable Machine, which allows users to train machine learning models using images, sounds, or poses. The platform simplifies the process of model training and deployment.

The objective of this project is to classify different hand gestures accurately and understand the impact of training parameters such as epochs, model complexity, and dataset size.

---

# Live Model

You can try the trained model here:

🔗 **Live Model Link:**  
https://teachablemachine.withgoogle.com/models/KtGrlPKhY/

---

# Workflow

![korean heart](https://github.com/PriyankaHichkad/Hand-Gesture-Classifier/blob/main/images/korean%20heart.jpeg)

The workflow begins by creating multiple gesture classes in Google Teachable Machine, such as Korean Heart, Thumbs-Up, Peace Sign, Closed Fist, and Open Palm. For each class, image samples are collected using the webcam to build a dataset. After collecting sufficient data, the model is trained using the built-in training feature, where it learns to differentiate between the gestures. Once the training is complete, the model is tested in real time using the preview section, where the webcam input is analyzed and predictions are displayed with confidence scores. This step-by-step process of class creation, data collection, training, and testing ensures that the model can accurately recognize different hand gestures.

![Closed Fist](https://github.com/PriyankaHichkad/Hand-Gesture-Classifier/blob/main/images/closed%20fist.jpeg)

---

# Objectives

- To build a hand gesture classification model  
- To understand the training process in Teachable Machine  
- To experiment with different parameters like epochs and model settings  
- To analyze model performance based on different configurations  

---

# Tools and Technologies Used

- Google Teachable Machine – Model training platform  
- Machine Learning – Image classification  
- Computer Vision – Gesture recognition  
- Webcam – Data collection for gestures  

---

# Methodology

### 1. Data Collection
Images of different hand gestures were collected using a webcam. Multiple samples were captured for each gesture class to ensure better model performance.

### 2. Model Training
The dataset was uploaded to Google Teachable Machine, where a classification model was trained.

Different experiments were performed by changing:
- Number of epochs  
- Number of classes  
- Training samples  
- Model settings  

### 3. Testing and Evaluation
The trained model was tested in real-time using the webcam. Predictions were observed and accuracy was analyzed based on different configurations.

---

# Experiments

Several experiments were conducted to improve model performance:

- Started with 2 gesture classes and trained a basic model  
- Increased the number of classes to 4 to make the model more complex  
- Adjusted the number of epochs to observe performance changes  
- Modified training data to improve accuracy  
- Tested different configurations to analyze model behavior  

These experiments helped in understanding how different parameters affect the model’s performance.

---

# Results

- The model was able to classify hand gestures with reasonable accuracy  
- Increasing the number of training samples improved performance  
- Higher epochs generally improved accuracy but required more training time  
- More classes made the classification task more challenging  

---

# Challenges Faced

### Limited Training Data
Initially, the model did not perform well due to limited data. This was improved by collecting more samples for each gesture.

### Model Accuracy
Accuracy varied based on the number of classes and epochs. Multiple experiments were required to find a balance.

### Lighting and Background Issues
Different lighting conditions and backgrounds affected predictions, requiring more consistent data collection.

---

# Future Improvements

- Increase dataset size for better accuracy  
- Use more advanced deep learning models  
- Deploy the model in a real-world application  
- Integrate with a web or mobile interface  

---

# Conclusion

This project demonstrates how machine learning can be applied to recognize hand gestures using a simple and accessible platform like Google Teachable Machine.

It highlights the importance of data quality, parameter tuning, and experimentation in building effective machine learning models. The project also shows how beginners can build practical AI applications without extensive coding.
