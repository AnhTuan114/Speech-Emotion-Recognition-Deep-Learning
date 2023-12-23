# Speech_Emotion_Recognition_Deep_Learning
dataset, Project report 
https://drive.google.com/drive/folders/1JxAC8Pdo7Mo_3eO9wexB_xzXjDTqHvO5?usp=sharing

Project Objective:
The project aims to deploy a machine learning model for emotion classification through audio. The goal is to analyze emotions corresponding to audio inputs, such as sound-based recognition projects for speech, singing, and more.

Project Description:
Data: The dataset consists of 200 samples, extracted from two actresses (26 years old and 64 years old), mentioning the phrase "let's say the word_". The recordings created from this set are annotated for seven emotions (anger, disgust, fear, happiness, interesting surprise, sadness, neutrality). In total, there are 2800 data points (audio files).

Algorithms used:
Long short-term memory (LSTM),
K-Nearest Neighbors (KNN)

Key Points of Focus:
Data processing pipeline: Data is extracted from each audio file, standardized, and features are extracted.

Selected features, such as Energy-Root Mean Square (RMS), Zero Cross Rate (ZCR), and Mel Frequency Cepstral Coefficient (MFCC) (frame_length = 2048, hop_length = 512), are extracted using Librosa for the audio emotional recognition model. All features are combined into a single "x" variable.

Technologies Used:
Python, TensorFlow
