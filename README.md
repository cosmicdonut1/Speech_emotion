# Emotion Recognition from Audio Recordings

## Overview

This project focuses on recognizing emotions from audio recordings using deep learning techniques. The model is trained on over 20,000 clean audio samples of emotional speech, with an average length of 2 seconds per recording. The features are extracted using MFCC (Mel-Frequency Cepstral Coefficients).

## Features

- **Emotion Recognition**: The model can classify emotions such as angry, happy, neutral, sad, and surprised.
- **Deep Learning**: Utilizes a three-layer LSTM (Long Short-Term Memory) network.
- **Data Preprocessing**: Audio features are preprocessed using MFCC.
- **Training and Evaluation**: Includes scripts for training and evaluating the model.

## Dataset

The dataset used for this project includes over 20,000 audio recordings, with each recording being approximately 2 seconds long. The audio files are not included in this repository due to copyright restrictions. The features and labels are also protected and cannot be shared.

## Model Architecture

The model is built using TensorFlow and Keras and consists of the following layers:
- Three LSTM layers with 128 units each
- Dropout layers to prevent overfitting
- A Dense layer with softmax activation for the output
