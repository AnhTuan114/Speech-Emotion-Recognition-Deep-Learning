# Speech_Emotion_Recognition_Deep_Learning
dataset, Project report 
link: https://drive.google.com/drive/folders/1F4l5zzya4kFfOSAfZ-lgZAoyO7wCGHtN

Project Description:
Data: The dataset consists of 200 samples, extracted from two actresses (26 years old and 64 years old), mentioning the word "let's say the word_" in the phrase "言う_". The recordings created from this set are annotated for seven emotions (anger, disgust, fear, happiness, interesting surprise, sadness, neutrality). A total of 2800 data points (audio files).

Algorithms used:
Long short-term memory (LSTM)
K-Nearest Neighbors (KNN)

Key Points of Focus:
Data Processing Pipeline: Data is extracted from each audio file, standardized, and features are extracted. The selected features, such as Energy-Root Mean Square (RMS), Zero Cross Rate (ZCR), and Mel Frequency Cepstral Coefficient (MFCC) (frame_length = 2048, hop_length = 512), are extracted using Librosa for the audio emotional recognition model. All features are combined into a single "x" variable.

Technologies Used:
Python, Windows, TensorFlow

Team Size:
3 members
