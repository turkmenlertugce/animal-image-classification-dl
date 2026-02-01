# Animal Image Classification (CNN & Transfer Learning)

This project focuses on building and optimizing a deep learning pipeline to classify animal images into four categories: **Bear, Elephant, Leopard, and Zebra**. The core objective is to demonstrate the transition from a custom-built baseline model to advanced techniques like **Transfer Learning** and **Data Augmentation**.

## Project Overview
The project is structured as a series of controlled experiments to observe the impact of different deep learning strategies on model performance and generalization.

### Workflow & Experiments
- **Baseline Model:** A custom Convolutional Neural Network (CNN) architecture built from scratch. It served as the starting point for performance comparison.
- **Transfer Learning (MobileNetV2):** Leveraged the pre-trained MobileNetV2 architecture to significantly boost accuracy and reduce training time.
- **Data Augmentation:** Applied random rotations, flips, and zooms to the training set to improve model robustness against overfitting.
- **Optimization:** Utilized Dropout layers and Batch Normalization to stabilize the learning process.

## Technical Stack
- **Framework:** TensorFlow / Keras
- **Library:** NumPy, Matplotlib, OS
- **Environment:** Developed and tested on Google Colab with T4 GPU support.

## Final Evaluation & Results
Based on the experiments conducted in the notebook:

- **Baseline Model:** Showed initial learning but suffered from overfitting as the gap between training and validation accuracy widened.
- **Transfer Learning Model:** After fine-tuning **MobileNetV2**, the model reached a much higher validation accuracy (approaching **96-98%**) with significantly lower loss.
- **Conclusion:** The combination of Transfer Learning and Data Augmentation proved to be the most effective strategy, providing a stable and highly accurate classifier.

## Dataset
The model is trained on a specific animal dataset consisting of 4 classes (Bear, Elephant, Leopard, Zebra). The data was preprocessed and resized to **224x224** to match the input requirements of the pre-trained architectures.
