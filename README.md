# Image-Recognition-with-Animals

This project involves building a Convolutional Neural Network (CNN) to classify images of different animals. The dataset is split into training and testing sets, and data augmentation techniques are used to improve model performance.

## Project Overview

The goal of this project is to recognize and classify images of animals into various categories. The project follows the standard steps for image classification:
1. **Image Preprocessing**: Resizing and normalizing images.
2. **Data Augmentation**: Applying random transformations to images to increase the dataset size and improve model generalization.
3. **Model Training**: Designing and training a CNN to classify images.
4. **Model Evaluation**: Evaluating the model's performance on the test set using metrics like accuracy, precision, recall, and F1-score.
5. **Visualization**: Displaying images before and after preprocessing, as well as the results of model evaluation.

## Dataset

The dataset consists of images from different animal categories. The images are split into training (80%) and testing (20%) sets. Data augmentation techniques such as rotation, width/height shifts, zoom, and horizontal flipping are applied to the training data.

## Requirements

- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Pillow
