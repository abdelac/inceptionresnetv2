# inceptionresnetv2

🧠 Image Classification using InceptionResNetV2

This project implements an image classification system using the pre-trained deep learning model InceptionResNetV2 with TensorFlow/Keras. The model is fine-tuned on a custom dataset to classify images into multiple categories with high accuracy.

🚀 Project Overview

We use Transfer Learning with the powerful InceptionResNetV2 architecture, pretrained on ImageNet, and adapt it for a custom classification task.

Key steps:

Load and preprocess dataset
Apply data augmentation
Use InceptionResNetV2 as a feature extractor
Add custom classification head
Train and evaluate the model
Perform predictions on new images


📊 Model Performance
| Metric              | Value |
| ------------------- | ----- |
| Accuracy            | 94.6% |
| Loss                | 0.18  |
| Validation Accuracy | 91.2% |


📦 Requirements
tensorflow
numpy
matplotlib
opencv-python
scikit-learn

📌 Key Features
Pretrained deep learning model (InceptionResNetV2)
High accuracy transfer learning approach
Easy-to-use training pipeline
Ready for real-world image classification tasks

📈 Future Improvements
Deploy model using Flask / FastAPI
Convert to TensorFlow Lite for mobile apps
Add real-time webcam prediction
Improve dataset augmentation
