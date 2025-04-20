# Adversarial Training on CIFAR-10 with FGSM Attacks

This project explores adversarial training techniques to improve the robustness of a ResNet-18 model on the CIFAR-10 dataset. The core objective is to mitigate adversarial vulnerability using FGSM (Fast Gradient Sign Method) attacks and advanced loss functions.

## Overview

- **Model**: ResNet-18
- **Dataset**: CIFAR-10
- **Adversarial Method**: FGSM (Fast Gradient Sign Method)
- **Loss Function**: Circle Loss [[1]](#references)
- **Data Split**: 80% for training, 20% for testing

## Key Features

- Implements FGSM adversarial attack to generate adversarial examples.
- Trains the model using adversarial training to enhance robustness.
- Integrates the Circle Loss function for improved similarity learning.

## Requirements

Make sure you have the following packages installed:

- `torch`
- `torchvision`
- `numpy`
- `matplotlib`
- `sklearn`
- `tqdm`

(Use `pip install -r requirements.txt` if a requirements file is created.)

## How to Run

1. Clone this repository.
2. Open `FGSM.ipynb` in Jupyter Notebook or any compatible editor.
3. Run the cells step by step to train the model and evaluate adversarial robustness.

## References

[1] Yifan Sun, Changmao Cheng, Yuhan Zhang, Chi Zhang, Liang Zheng, Zhongdao Wang, and Yichen Wei.  
*Circle Loss: A Unified Perspective of Pair Similarity Optimization.* CVPR 2020, pp. 6398–6407.
