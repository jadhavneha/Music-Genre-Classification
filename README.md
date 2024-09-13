# Music-Genre-Classification
Digital Signal Processing Project

## Role of DSP in Music Genre Classification:
Feature Extraction: DSP extracts relevant features from audio signals, such as Mel-frequency cepstral coefficients (MFCCs), spectrograms, rhythm patterns.
Preprocessing: DSP processes audio data for effective classification by reducing noise, resampling, equalization, etc.
Feature Representation: DSP converts audio signals into feature vectors. Features are inputs to machine learning models for genre classification.

## DSP Techniques for Music Genre Classification:
Spectral Analysis: Analyzing frequency content using Fourier transforms and extracting information about pitch, timbre, and harmonics.
Filtering: Removing noise and enhancing relevant signal components. This improves accuracy by focusing on important features.
Temporal Analysis: Studying signal changes over time by capturing rhythm, tempo, and dynamics of music.

## Neural Network Architechture
We designed neural networks to classify audio files based on the extracted MFCC features. 
The models with the best results are present in the code. We used multiple dense layers, the “relu” activation function, and finally the “softmax” activation function at the final layer to get our output. This facilitates the learning of complex relationships between input features and music genres.
Input to the neural network consisted of the scaled MFCC features extracted from the audio files, while the output layer predicted the probability distribution over different music genres.
