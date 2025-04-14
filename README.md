# Facial Expression Classifier - Happy vs Sad

This project is a Convolutional Neural Network (CNN) built using TensorFlow and Keras to classify facial expressions into two categories: **Happy** and **Sad**. It utilizes data augmentation and transfer learning techniques for better performance and generalization.

## Project Overview

Facial emotion recognition is a key component in human-computer interaction. This project demonstrates how deep learning can be used to distinguish between happy and sad faces by training a CNN model on a custom dataset.

The goal is to build a model that:
- Accepts facial images as input
- Classifies them as **Happy** or **Sad**
- Achieves high accuracy using real-world-like data and basic data augmentation

## Techniques Used

- Image preprocessing using `ImageDataGenerator`
- CNN architecture with Conv2D, MaxPooling, Flatten, Dense layers
- Model checkpointing to save the best version
- Early stopping to prevent overfitting
- Visualization of training and validation performance


## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/image-Classifier.git
cd image-Classifier




