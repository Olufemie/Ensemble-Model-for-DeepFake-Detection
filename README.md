# Ensemble Model for DeepFake Detection

## Overview

This project presents an ensemble deep learning approach for detecting deepfake facial images. The model combines the strengths of three different architectures—CNN-LSTM, ResNet50, and InceptionV3—to improve detection accuracy and robustness through ensemble learning.

The system was developed as a final-year Computer Science research project to address the growing cybersecurity threat posed by AI-generated synthetic media.

## Features

- Deepfake image classification
- Ensemble learning using majority voting
- Custom CNN-LSTM architecture
- Transfer learning with ResNet50
- Transfer learning with InceptionV3
- Image preprocessing and augmentation
- Model evaluation using standard classification metrics

## Model Architecture

The ensemble consists of:

- CNN-LSTM
- ResNet50
- InceptionV3

Each model independently predicts whether an image is **Real** or **Fake**. The final prediction is obtained using majority voting among the three models.

## Dataset

The project was trained using publicly available deepfake datasets containing real and AI-generated facial images.

Dataset preprocessing includes:

- Image resizing
- Normalization
- Data augmentation
- Train/Validation/Test split

## Technologies Used

- Python
- TensorFlow/Keras
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn
- Google Colab
- 
## Evaluation

The ensemble model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

The ensemble approach achieved improved performance compared to individual models by leveraging the strengths of each architecture.

**Gboyega Oluwafemi**

B.Sc. Computer Science

Research Interest: Artificial Intelligence, Machine Learning, Computer Vision, and Cybersecurity.
## License

This project is intended for academic and research purposes.
