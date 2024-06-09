# Chessboard FEN Prediction Using Convolutional Neural Networks (CNNs)

## Overview

This project presents a novel method for predicting Forsyth-Edwards Notation (FEN) scores from digital chessboard images using Convolutional Neural Networks (CNNs). By leveraging advanced deep learning techniques and Exploratory Data Analysis (EDA), our model accurately converts chessboard configurations into FEN scores.

## Features

- **High Precision**: Achieves 98.6% training accuracy and 98.4% testing accuracy.
- **Robust Preprocessing**: Includes labeling, resizing, cleaning, augmenting, and splitting data to ensure a high-quality dataset.
- **Advanced Techniques**: Utilizes Principal Component Analysis (PCA) and feature engineering to enhance feature extraction and spatial correlations.
- **Real-World Applicability**: Suitable for real-time analysis of online matches and automated chess game record-keeping.

## Dataset Preparation

1. **Labeling**: Accurate labeling of chessboard configurations.
2. **Resizing**: Standardizing image dimensions for consistent input.
3. **Cleaning**: Removing noise and artifacts from images.
4. **Augmenting**: Generating additional data through transformations.
5. **Splitting**: Dividing the dataset into training and testing sets to evaluate model performance.

## Model Architecture

Our CNN architecture consists of convolutional layers and loss layers that enable precise feature extraction and classification:

- **Convolutional Layers**: Extract spatial features from chessboard images.
- **Loss Layers**: Optimize the model through backpropagation.

## Training and Evaluation

The model demonstrates exceptional performance:

- **Training Accuracy**: 98.6%
- **Testing Accuracy**: 98.4%

The model's learning process and development over epochs are validated by loss and accuracy trends, confirming its reliability and effectiveness.

## Applications

- **Real-Time Analysis**: Analyze online chess matches in real-time.
- **Automated Record-Keeping**: Automatically generate FEN scores from chess game screenshots.
- **Strategic Analysis**: Assist users in strategic analysis and decision-making in chess.

## Conclusion

This project opens new avenues for research and development in computer vision-based chess analysis. By enabling accurate FEN score computation from chessboard images, it enhances strategic insights and decision-making in chess.

## Future Work

- **Enhanced Models**: Explore other deep learning architectures to further improve accuracy.
- **Larger Datasets**: Incorporate larger and more diverse datasets.
- **Additional Features**: Implement more advanced features such as move prediction and game outcome analysis.
