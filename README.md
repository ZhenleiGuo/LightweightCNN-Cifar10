# Lightweight CNNs for CIFAR-10: Code, Model, and data
**Authors: Zhenlei Guo, Xiaolin Lu.**
Under the supervision of **Prof.Dijana Petrovska**

This repository contains the source code, data, and models for our project on designing lightweight CNN architectures for CIFAR-10 image classification. The project includes implementations for multiple model variants, including:

- **Lite01** – A lightweight CNN using depthwise separable convolutions.
- **Lite02** – A CNN with enhanced regularization (batch normalization and dropout) for improved generalization.
- **ResNet20 Variants (V1, V2, V3)** – Several versions of a 20-layer ResNet model with different dropout configurations. *ResNet20 V1 is the best variant.*
- **MobileNetV2** – An implementation of MobileNetV2 using inverted residual blocks and depthwise separable convolutions.
- **Confusion Matrix** - A code that generates the confusion matrix for a given model using the Cifar-10 dataset, 10 Class.

## Repository Structure

- **Models Folder**:  Contains the final saved model files (`.h5`) for all implemented architectures (e.g., Lite01, Lite02, ResNet20V1/V2/V3, MobileNetV2).

- **Training History Folder**:  Includes the training logs exported after training each model. These logs document key metrics such as training loss, validation loss, training accuracy, testing accuracy, and learning rate schedules.

- **Confusion Matrix Folder**:  Contains the generated confusion matrix images for all models.

- **Result Graph Folder**:  Contains graphs for each model, including training accuracy/test accuracy curves and combined Test/Training Accuracy & Training/Test Loss curves for different models.


## Requirements

- Python 3.7+
- TensorFlow 2.x
- Keras (included with TensorFlow 2.x)
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

You can install the required packages using:

```bash
pip install -r requirements.txt
