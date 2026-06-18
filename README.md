# Plant Diseases in Smart Agriculture

This project focuses on automatically diagnosing diseases in tomato leaves using deep learning and computer vision techniques. It serves as an initial hands-on framework to handle cloud-based dataset pipelines and train Convolutional Neural Networks (CNNs).

## Key Features & Workflow
- **Automated Data Pipeline:** Integrated with Google Drive API via `PyDrive2` to dynamically authenticate, fetch, and extract zipped image datasets inside cloud environments.
- **Image Preprocessing:** Utilized OpenCV and NumPy for preparing image matrices and handling file structures for training/validation splits.
- **Deep Learning Architecture:** Implemented an end-to-end training pipeline using TensorFlow and Keras framework.

## Project Status & Key Insights
As a foundational baseline project, the initial model training demonstrated a classic case of high bias/overfitting. While the training loss stabilized, the validation accuracy resulted in 10% with a cross-entropy loss of 2.30. This baseline highlighted the critical importance of data augmentation, learning rate scheduling, and the necessity of leveraging Transfer Learning (e.g., MobileNetV2 or ResNet) for complex botanical image tasks, which are set as the immediate next steps for this repository.
