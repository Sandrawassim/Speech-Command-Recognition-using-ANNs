# Speech-Command-Recognition-using-ANNs
## Project Objective

The objective of this project is to build a model that recognizes spoken digit commands (from 0 to 9) using MFCC features extracted from audio clips. The project explores both Artificial Neural Network (ANN) and Convolutional Neural Network (CNN) architectures to achieve high accuracy, aiming for over 85% accuracy on the test set.

## Dataset Information and Preprocessing Steps

Dataset: The project uses the Google Speech Commands Dataset hosted on Kaggle, which contains short audio clips of spoken commands.
Categories Used: Only the digits from "zero" to "nine" are used for this classification task.
### Preprocessing:
MFCC Extraction: For each audio file, Mel Frequency Cepstral Coefficients (MFCC) are extracted with 60 coefficients.

Resizing: The MFCC spectrograms are resized to 64x64 to ensure consistency.

Normalization: Each spectrogram is normalized to have pixel values between 0 and 1 to improve model training stability.
