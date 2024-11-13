# Speech-Command-Recognition-using-ANNs
## Project Objective

The objective of this project is to build a model that recognizes spoken digit commands (from 0 to 9) using MFCC features extracted from audio clips. The project explores Artificial Neural Network (ANN) architecture to achieve high accuracy, aiming for over 85% accuracy on the test set.

## Dataset Information and Preprocessing Steps

Dataset: The project uses the Google Speech Commands Dataset hosted on Kaggle, which contains short audio clips of spoken commands.
Categories Used: Only the digits from "zero" to "nine" are used for this classification task.
### Preprocessing:
MFCC Extraction: For each audio file, Mel Frequency Cepstral Coefficients (MFCC) are extracted with 60 coefficients.

Resizing: The MFCC spectrograms are resized to 64x64 to ensure consistency.

Normalization: Each spectrogram is normalized to have pixel values between 0 and 1 to improve model training stability.

## Instructions for Running the Code
#### 1.Download the Repository
#### 2.Download the Dataset
#### 3.Run the Code:
Load and explore the dataset
Preprocess the data
Build and train the models (ANN and CNN)
Evaluate model performance with metrics and visualizations
#### 4.Results

## Dependencies and Installation Instructions
### 1.Set up the Environment:
Python 3.8+ installed.

### 2. Install Dependencies:
tensorflow 
librosa 
scikit-learn
matplotlib

### Main Dependencies:
#### TensorFlow:
For building and training the neural networks.
#### Librosa:
For audio processing and feature extraction.
#### scikit-learn: 
For label encoding, train-test splitting, and evaluation metrics.
#### Matplotlib: 
For visualizing training and validation curves.

## About This Code
This project code provides a complete workflow for training and evaluating models on spoken digit commands. Key elements include:
#### Data Exploration and Loading:
Visualizes and verifies dataset paths and contents.
#### Feature Extraction: 
Extracts MFCC features and applies normalization to make the audio data suitable for neural network input.
#### ANN Model: 
Implements a dense ANN model as a baseline approach.
#### Evaluation and Visualization: 
Evaluates both models using metrics like accuracy, precision, recall, and F1-score. Plots show training/validation accuracy and loss trends over epochs, providing insights into model performance and potential overfitting or underfitting.

