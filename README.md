# SimCLRv2 [Paper Implementation]

This project implements the methodology proposed in the paper "Big Self-Supervised Models are Strong Semi-Supervised Learners" [link to paper](https://arxiv.org/abs/2006.10029).

## Overview

The goal of this project is to explore and implement the self-supervised learning approach outlined in the mentioned paper. The model is trained initially on the STL-10 dataset [link to dataset](https://cs.stanford.edu/~acoates/stl10/) and subsequently on a medical dataset for diabetic retinopathy detection [link to dataset](https://www.kaggle.com/competitions/diabetic-retinopathy-detection/data).

The model utilizes ResNet50 as the backbone for feature extraction and representation learning.

There are two separate notebooks, each dedicated to training the model on one of the datasets.

## Notebooks

1. **STL-10 Dataset Notebook:**
   - File: `SimCLR_ResNet50.ipynb`
   - This notebook contains the implementation and training process on the STL-10 dataset.

2. **Retinopathy Dataset Notebook:**
   - File: `DR_SimCLR_ResNet50.ipynb`
   - This notebook contains the implementation and training process on the medical dataset for diabetic retinopathy detection.

## Acknowledgments

This project drew inspiration from the original paper "Big Self-Supervised Models are Strong Semi-Supervised Learners" and the book "Deep Learning with PyTorch Lightning: Swiftly build high-performance Artificial Intelligence (AI) models using Python" by Kunal Sawarkar [link to book](https://www.amazon.com/Deep-Learning-PyTorch-Lightning-high-performance/dp/180056161X).

## Dependencies

- Python 3.x
- PyTorch
- PyTorch Lightning



