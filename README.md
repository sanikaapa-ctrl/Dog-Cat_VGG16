# 🐶 Dog and Cat Image Classification Using VGG16

## 📌 Project Overview
This project focuses on classifying images of dogs and cats using Deep Learning and Transfer Learning with the VGG16 Convolutional Neural Network (CNN) architecture.

The pretrained VGG16 model is used to extract image features and classify input images into two categories: Dog and Cat.

## 🎯 Project Objectives
- To classify images into Dog and Cat categories.
- To understand Transfer Learning using VGG16.
- To apply image preprocessing and data augmentation.
- To evaluate model performance using accuracy and loss graphs.

## 🛠️ Technologies Used
- Python
- Google Colab
- TensorFlow
- Keras
- NumPy
- Matplotlib
- VGG16 (CNN)

## 📂 Dataset
The project uses a Dog and Cat image dataset.

The dataset contains two categories:
- Cats
- Dogs

**Image Size:** 150 × 150 pixels

**Batch Size:** 32

**Training and Validation Split:** 80% Training and 20% Validation

## ⚙️ Data Preprocessing
- Image resizing
- Image normalization
- Rotation
- Width and height shifting
- Zooming
- Horizontal flipping
- Data augmentation

## 🧠 Model Architecture
The VGG16 pretrained model is used with ImageNet weights.

The model consists of:
- VGG16 Base Model (Pretrained)
- Flatten Layer
- Dense Layer (256 neurons, ReLU activation)
- Dropout Layer (0.5)
- Output Layer (1 neuron, Sigmoid activation)

## 🔧 Model Compilation
- Optimizer: Adam
- Learning Rate: 0.0001
- Loss Function: Binary Crossentropy
- Evaluation Metric: Accuracy
- Epochs: 15

## 📊 Model Evaluation
The model performance is visualized using:
- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss

The project also displays predictions on new images and validation images.

## 🔍 Prediction
The trained model predicts whether an input image belongs to the Dog or Cat category using a sigmoid output and a 0.5 threshold.

## 🏁 Conclusion
This project demonstrates the use of Transfer Learning and VGG16 for image classification. It provides practical experience in CNN architecture, image preprocessing, data augmentation, model training, and image prediction.
## 👩‍💻 Author
**Sanika Babaso Patil**
