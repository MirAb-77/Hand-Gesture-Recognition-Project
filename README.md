# 🖐️ **Hand Gesture Recognition Project**

Welcome to the **Hand Gesture Recognition** project! This repository features an advanced system designed to classify hand gestures from grayscale images using Convolutional Neural Networks (CNNs). Explore how this project leverages deep learning to recognize and interpret hand gestures effectively.

## 🚀 **Project Overview**

This project focuses on building a model to classify hand gestures from grayscale images of size 240x640. The trained CNN model can be deployed on various web platforms for real-time gesture recognition.

### 📂 **Project Structure**

- **`model.py`**: Defines and compiles the CNN model architecture.
- **`train_model.py`**: Manages the training process, including techniques like early stopping to enhance model performance.
- **`predict.py`**: Provides functions for image preprocessing and making predictions.
- **`deploy.py`**: Contains code for deploying the model using web technologies.
- **`data/`**: Includes sample images for testing and validation.
- **`my_model.h5`**: The saved model in HDF5 format for later use.

## 🔍 **Model Architecture**

The CNN model is structured to effectively learn from and classify grayscale images:
- **Convolutional Layers**: Extract features from the images.
- **MaxPooling Layers**: Reduce dimensionality while maintaining critical information.
- **Dropout Layers**: Prevent overfitting by dropping units during training.
- **Fully Connected Layers**: Perform classification based on learned features.

## 📊 **Training and Evaluation**

- **Training**: The model is trained with a focus on accuracy and robustness. Techniques like early stopping are used to prevent overfitting and ensure optimal performance.
- **Evaluation**: The model is evaluated using metrics such as accuracy and loss on both training and validation datasets. Key results include:
  - **Training Accuracy**: 	99%
  - **Validation Accuracy**: 100%
  - **Training Loss**: 0.002064%
  - **Validation Loss**: 0.000502%
  - 
 <img width="899" alt="h3" src="https://github.com/user-attachments/assets/7085d51d-2090-4ae7-bdd7-61fad8a2fc48">

  - 
- **Performance**: The model shows strong performance in recognizing hand gestures, with high accuracy on unseen data, demonstrating its generalization capabilities.

## 🌐 **Deployment**

- **Web Interface**: The model can be deployed using different web technologies:
  - **Streamlit**: Provides a simple interface to upload and classify hand gesture images interactively.
  - **Flask**: Enables creating a REST API for model inference and integration with web applications.
  - **Dash**: Offers an interactive web dashboard for visualization and interaction with the model.

## 📜 **How to Use**

1. **Clone the Repository**: Obtain a local copy of the project by cloning this repository.
2. **Set Up Environment**: Ensure all necessary dependencies (e.g., TensorFlow, Streamlit) are installed.
3. **Train the Model**: Follow the instructions in `train_model.py` to train the model on your data.
4. **Make Predictions**: Use `predict.py` to preprocess images and get predictions from the trained model.
5. **Deploy**: Utilize `deploy.py` to create a web-based application for gesture classification using Streamlit, Flask, or Dash.

## 🔮 **Prediction Examples**

**1. Thumbs Up Gesture**
- **Input Image**:
- <img width="859" alt="Thumbs Up Prediction" src="https://github.com/user-attachments/assets/946a817a-cb82-40d4-9bcc-128e69114753">

- **Prediction**: Thumbs Up 👍 (Correct!)

**2. Victory Sign Gesture**

- **Input Image**:
- <img width="869" alt="Victory Sign Prediction" src="https://github.com/user-attachments/assets/83f7e367-ddf9-48a8-a147-10969171fbcf">
- **Prediction**: Victory Sign ✌️ (Correct!)

## 💬 **Contribute**

Contributions are welcome! Feel free to submit issues, suggest enhancements, or add new features. Your input helps make this project better!

---

Feel free to adjust any details or add more information to tailor it further to your specific project!
