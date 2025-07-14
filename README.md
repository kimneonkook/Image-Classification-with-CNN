# ASL Sign Language Classifier

A basic CNN image classifier that recognizes 27 American Sign Language (ASL) hand signs.

## Dataset

- [ASL 27-Class Dataset](https://www.kaggle.com/datasets/ardamavi/27-class-sign-language-dataset)

## Tools

- Python
- TensorFlow / Keras
- NumPy, Matplotlib

## What it does

- Trains a CNN to classify images into 27 ASL categories
- Uses normalized image data and custom input shape
- Uses integer labels (no one-hot encoding)
- Applies `class_weight` to handle class imbalance
- Includes `EarlyStopping` and `ReduceLROnPlateau` during training