# Comparative-Analysis-of-Defenses-Against-FGSM-Attack
## Overview

This repository investigates the vulnerabilities of a Deep Neural Network (DNN) model trained on the MNIST dataset, emphasizing the impact of adversarial attacks and evaluating various defense mechanisms.

## Environment

- **Programming Language:** Python
- **Libraries:** TensorFlow, NumPy, Matplotlib
- **Framework:** Keras
- **Dataset:** MNIST

## Methodology

1. **Model Architecture:**
   - The DNN architecture consists of a flattening layer followed by a dense hidden layer with Rectified Linear Unit (ReLU) activation. A dropout layer is employed for regularization, and the final layer utilizes the softmax activation function. This architecture is implemented to classify images from the MNIST dataset.

2. **Training:**
   - Training the model involves loading the MNIST dataset, normalizing pixel values, and then training the model using the Adam optimizer with sparse categorical crossentropy as the loss function. The training process is conducted for a specified number of epochs.

3. **Adversarial Attacks:**
   - Implementations of adversarial attacks, such as the Fast Gradient Sign Method (FGSM), are included.

4. **Defense Mechanisms:**
   - Explore the effectiveness of the following defense mechanisms:
     - Adversarial Training
     - Adversarial Training with Gradient Masking
     - Label Smoothing
     - Distilled Neural Network

5. **Results Analysis:**
   - Visualize and analyze the impact of adversarial attacks on the model.
   - Evaluate the performance of each defense mechanism in mitigating adversarial perturbations.

## Results

### Adversarial Attack Impact

![image](https://github.com/poornikabonam/Comparative-Analysis-of-Defenses-Against-FGSM-Attack-/assets/97566249/52075ee9-7066-4738-b84f-e5f19606fa09)


### Defense Mechanism Evaluation

![image](https://github.com/poornikabonam/Comparative-Analysis-of-Defenses-Against-FGSM-Attack-/assets/97566249/d2f8506f-32ca-469f-81f8-e3639f6ebd07)

![image](https://github.com/poornikabonam/Comparative-Analysis-of-Defenses-Against-FGSM-Attack-/assets/97566249/ab4e65c6-2d41-4250-be9e-4706be495e9e)


## Usage
