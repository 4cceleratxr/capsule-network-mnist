# capsule-network-mnist
Implemented a Capsule Network to improve image classification by preserving spatial hierarchies over traditional CNNs.
# Capsule Network for MNIST Classification

## Overview
This project implements a **Capsule Network (CapsNet)** to classify handwritten digits from the MNIST dataset. Unlike traditional CNNs, Capsule Networks preserve **spatial hierarchies** between features using dynamic routing, leading to better generalization.

## Problem Statement
Traditional Convolutional Neural Networks (CNNs) often lose spatial relationships due to pooling layers. This project addresses that limitation by using Capsule Networks to better capture positional and hierarchical information in images.

## Approach
- Implemented Capsule Network architecture
- Used **dynamic routing algorithm** between capsules
- Replaced pooling layers with capsule-based feature learning
- Trained on MNIST dataset
  
## Tech Stack
- Python
- TensorFlow / PyTorch
- NumPy
- Matplotlib
  
## Results
- Achieved ~99% accuracy on test dataset
- Improved feature representation compared to CNNs
- Better handling of rotated and distorted digits

## Output Samples
(Add confusion matrix / accuracy graphs here)

## How to Run
```bash
git clone https://github.com/your-username/capsule-network-mnist.git
cd capsule-network-mnist
pip install -r requirements.txt
python train.py
