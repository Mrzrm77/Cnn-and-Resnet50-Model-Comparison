# Cnn-and-Resnet50-Model-Comparison
Image Classification with Deep Learning (Intel Image Dataset)

This project implements and compares various deep learning approaches for image classification on the 'Intel Image Classification' dataset. The primary goal is to accurately classify images into one of six categories: buildings, forest, glacier, mountain, sea, and street.

Key Features:

Data Acquisition & Exploration: Downloads the dataset from Kaggle and performs exploratory data analysis to understand class distribution.
Data Preprocessing & Augmentation: Utilizes ImageDataGenerator for real-time image augmentation and scaling, splitting data into training, validation, and test sets.

Custom CNN Model: Development and training of a Convolutional Neural Network (CNN) from scratch.
Transfer Learning with ResNet50: Implementation of the ResNet50 architecture as a feature extractor, leveraging pre-trained weights from ImageNet.

Fine-tuning ResNet50: Advanced transfer learning technique where top layers of the pre-trained ResNet50 model are unfrozen and trained alongside a custom classification head for optimal performance.
Comprehensive Model Evaluation: Detailed assessment of each model's performance using accuracy, loss plots, classification reports, and confusion matrices.

Model Prediction & Visualization: Demonstrates how to make predictions on new images and visualizes sample predictions.
Model Persistence: Saves trained models (CNN, ResNet50 Feature Extractor, Fine-tuned ResNet50) for future deployment or analysis.
Technologies Used:

- Python

- TensorFlow / Keras

- Pandas

- Matplotlib

- Seaborn

- Scikit-learn

This project serves as a practical example of applying deep learning, particularly transfer learning and fine-tuning, to solve a multi-class image classification problem.
