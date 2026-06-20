# Human Activity Recognition System

A deep learning–based Human Activity Recognition System that classifies human activities from video sequences using a hybrid CNN-LSTM architecture.


## Project Overview

This project implements a Human Activity Recognition (HAR) system capable of recognizing different human activities from videos. The model combines Convolutional Neural Networks (CNNs) for extracting spatial features from video frames and Long Short-Term Memory (LSTM) networks for learning temporal patterns across frame sequences.

The system is trained on the UCF50 dataset and can classify multiple human activities such as basketball, diving, golf swing, push-ups, pull-ups, walking with a dog, skateboarding, and more.


## Features

- Human activity recognition from video sequences
- Video frame extraction and preprocessing
- CNN-based spatial feature extraction
- LSTM-based temporal sequence learning
- Multi-class activity classification
- Model training and evaluation
- Performance visualization
- Prediction on unseen videos


## Dataset

This project uses the **UCF50 Human Activity Recognition Dataset**.

**Dataset Link:**

https://www.kaggle.com/datasets/matthewjansen/ucf50-action-recognition-dataset


## Selected Activities

The model is trained on the following activities:

- Basketball
- BenchPress
- Biking
- Diving
- GolfSwing
- HighJump
- HorseRace
- JumpRope
- Kayaking
- PullUps
- PushUps
- RopeClimbing
- SkateBoarding
- SoccerJuggling
- Swing
- TrampolineJumping
- VolleyballSpiking
- WalkingWithDog


## Model Architecture

The system follows the workflow below:

Video Input

↓

Frame Extraction

↓

Frame Preprocessing

↓

TimeDistributed CNN

↓

LSTM

↓

Dense Layer

↓

Softmax Classifier

↓

Predicted Human Activity


## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook


## Project Workflow

1. Load video dataset
2. Extract frames from videos
3. Resize and normalize frames
4. Create training and testing datasets
5. Build CNN-LSTM model
6. Train the model
7. Evaluate performance
8. Predict human activities on unseen videos


## Results

The notebook includes:

- Training Accuracy
- Validation Accuracy
- Loss Curves
- Activity Predictions
- Model Performance Evaluation


## Installation

Clone the repository:

```bash
git clone https://github.com/imanfatima885/Human-Activity-Recognition-System.git


## Future Improvements

- Train on all 50 classes of the UCF50 dataset
- Apply transfer learning using ResNet or EfficientNet
- Develop a real-time webcam-based activity recognition system
- Improve classification accuracy using Transformer-based architectures


## Skills Demonstrated

- Computer Vision
- Deep Learning
- Human Activity Recognition
- CNN
- LSTM
- Video Processing
- TensorFlow/Keras
- Data Preprocessing
- Model Evaluation


## License

This project is intended for educational and research purposes.
