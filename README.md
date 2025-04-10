# ADA-GAN

## Overview

**ADA-GAN** (Adaptive Discriminator Augmentation for Generative Adversarial Networks) is a deep learning project designed to stabilize GAN training on limited datasets. It implements augmentation strategies that dynamically adjust during training to prevent discriminator overfitting and improve the quality of generated data.

## Features

- ✅ Adaptive Discriminator Augmentation (ADA) mechanism.
- ✅ Multiple architectures: Inception, ResNet50, MobileNet, 3D-CNN, Basic CNN.
- ✅ Dataset support: Bangla characters, numerals, and MNIST.
- ✅ Transfer learning and embedding exploration.

## Repository Structure

```
ADA-GAN/
├── images/                     # Model diagrams (Inception, 3D-CNN, etc.)
├── notebooks/                  # Main notebooks
│   ├── ADAGAN.ipynb
│   ├── ADAGAN - CONSONANT.ipynb
│   ├── ADAGAN - NUMERALS.ipynb
│   ├── AUGMENT GAN.ipynb
│   ├── BANGLA ISOLATED INCEPTION.ipynb
│   ├── BASIC CNN.ipynb
│   ├── MNIST GAN.ipynb
│   ├── MOBILENET.ipynb
│   ├── RESNET50.ipynb
│   ├── TOTAL DATA.ipynb
│   └── TRANSFER LEARNING.ipynb
```

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/CopotronicRifat/ADA-GAN.git
cd ADA-GAN
```

### 2. Install Requirements

Make sure Python 3.x is installed, then install:

```bash
pip install jupyter tensorflow keras numpy matplotlib opencv-python
```

### 3. Run Notebooks

```bash
jupyter notebook
```

Open any notebook in the `notebooks/` directory to explore ADA-GAN implementations.

## Demonstration

Includes visual output of GANs trained on Bangla character/numeral datasets with ADA applied. Results are visualized with:
- TensorBoard Embedding Projector (for image clustering)
- Model-specific outputs showing improvements from augmentation

## Citation

If you use this work, please cite:

```
S. M. Rafiuddin. "High Cursive Complex Character Recognition using GAN External Classifier." 
In ICCA '22: Proceedings of the 2nd International Conference on Computing Advancements, 2022.
```

## Acknowledgements

This project is inspired by NVIDIA’s [StyleGAN2-ADA](https://github.com/NVlabs/stylegan2-ada-pytorch).

## License

This repository is open-sourced under the MIT License.
