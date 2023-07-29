# Face-Detection-Recognition-using-OpenCV-and-K-Nearest-Neighbors-KNN-Classifier

## Abstract

This project aims to implement a face detection and recognition algorithm using the k-Nearest Neighbors (kNN) approach and OpenCV. The system separates image windows into two classes: faces and background, making it suitable for various applications such as security and device unlocking. The algorithm involves pre-processing, classification, and localization stages for accurate face detection.

## Methodology

- Pre-Processing: Input images are pre-processed to reduce variability in faces, including cropping frontal faces and applying standard light adjustment methods.

- Classification: Neural networks are trained on pre-processed instances to classify images as having faces or not, enhancing outcomes with different network configurations.

- Localization: The trained neural network is utilized to locate faces in images and place them into bounding boxes, considering facial features like position, scale, orientation, and illumination.

## Requirements

### Hardware

- Computer system with at least 2.5 GHz 64-bit Intel processor or AMD Opteron processor
- 4 GB RAM (Recommended: 6 GB or greater)
- 40 GB disk space

### Software

- Python 3
- TensorFlow
- OpenCV
- Scikit-Learn
