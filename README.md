# VanGoghCycleGAN

This project implements a CycleGAN model for unpaired image-to-image translation. The goal is to transform real landscape images into Van Gogh-inspired landscape paintings.

## Features

- Converts landscape images into Van Gogh inspired artwork.
- Utilizes PyTorch for model training and evaluation.
- Employs a CycleGAN architecture with two generators and two discriminators.

## Example Outputs
examples

## Dataset

- Van Gogh landscape paintings selected from https://www.kaggle.com/datasets/ipythonx/van-gogh-paintings
- Real-life landscape images selected from https://www.kaggle.com/datasets/arnaud58/landscape-pictures

## Requirements

- Python 3.10 or later
- conda (for virtual environment)

## Setup Guide

### 1. Clone the Repository

```bash
git clone https://github.com/MSan35/VanGoghCycleGAN.git
cd VanGoghCycleGAN
```

### 2. Set Up the Environment
This project uses a conda environment to manage dependencies.

```bash
# Create environment
conda create --name cyclegan python=3.10 -y

# Activate environment
conda activate cyclegan

# Install required packages
conda install pytorch torchvision torchaudio import-ipynb
```

### 3. Train the Model
Open jupyter notebook, navigate to the VanGoghCycleGAN directory and run train.ipynb.

```bash
# Open jupyter notebook
jupyter notebook
```

## More Information on CycleGAN

### Reference to the original paper
[1] J.-Y. Zhu, T. Park, P. Isola, and A. A. Efros, “Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks.” arXiv, Aug. 24, 2020. doi: 10.48550/arXiv.1703.10593. Available: http://arxiv.org/abs/1703.10593.
