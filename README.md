ASR for Urdu Language Emotion Classification
Overview
This project focuses on developing an Automatic Speech Emotion Recognition (ASER) system for the Urdu language. The system leverages machine learning and deep neural networks to classify emotions from spoken Urdu. Given the limited resources available for Urdu speech emotion recognition, we augment our dataset and extract relevant features to train a robust emotion classification model.

Project Workflow
Data Augmentation
To address the limited availability of Urdu speech data, we augment our dataset using the following techniques:

Add Noise: Introduce Gaussian noise to the audio data.
Shifting: Perform time shifting on the audio data.
Pitching: Change the pitch of the audio data.
Stretching: Apply time stretching to the audio data.
Feature Extraction
We extract several features from the augmented audio data to train our emotion classification model:

MFCCs (Mel-frequency cepstral coefficients)
Chroma STFT (Short-time Fourier transform)
Spectral Centroid
Spectral Bandwidth
Spectral Rolloff
Zero Crossing Rate
Model Training
Using the extracted features, we train a two-layer neural network to classify emotions in Urdu speech. The model is evaluated for its accuracy, and we achieve an accuracy of 82.5%.
