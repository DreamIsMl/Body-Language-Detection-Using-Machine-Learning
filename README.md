# Body Language Detection

## Overview

This project focuses on detecting and classifying different body language expressions using computer vision techniques and machine learning. The system utilizes the OpenCV and MediaPipe libraries to track key points on the human body, and a machine learning model is trained to predict various body language expressions, such as happiness, sadness, smiling, surprise, and more.

## Dataset

The dataset used for training the model was created by capturing real-time video using OpenCV and MediaPipe. Various body language expressions were manually labeled, and the corresponding keypoint data was extracted for training purposes.

## Machine Learning Model

The machine learning model is based on a simple logistic regression algorithm. The model was trained on the labeled dataset to learn the patterns associated with different body language expressions. The goal is to accurately predict the body language category given a set of keypoints obtained from real-time video analysis.

## Real-time Prediction

The project includes a function that allows real-time prediction of body language using the trained model. The OpenCV library is used to capture video from a webcam, and the MediaPipe library is used for keypoint extraction. The trained logistic regression model then predicts the body language category based on the real-time keypoint data.

## Accuracy

On the test dataset, the model achieved an accuracy of 100% for body language prediction. Further improvements and optimizations can be explored to enhance the model's performance on a broader range of scenarios.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/DreamIsMl/body-language-detection.git
   cd body-language-detection
