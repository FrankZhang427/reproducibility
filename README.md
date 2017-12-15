Reproduce Machine Learning
=====================================

Code for reproducing experiments in ["Improved Training of Wasserstein GANs"](https://arxiv.org/abs/1704.00028)

and ["Improving the Improved Training of Wasserstein GANs"](https://openreview.net/pdf?id=SJx9GQb0-)



## Prerequisites

- Python, NumPy, TensorFlow(1.2.1), SciPy, Matplotlib
- A recent NVIDIA GPU

## Models

Configuration for all models is specified in a list of constants at the top of
the file, type of WGAN also needs to be specified. To run generative model for CT-WGAN and GP-WGAN on MNIST

- `python gan_mnist_testcode.py`

For the CIFAR10 dataset, edit the file to specify the path to the dataset in
`DATA_DIR` before running. CIFAR10 dataset is publicly available; the
download URL is in the file.

- `python gan_cifar_testcode.py`: CIFAR-10