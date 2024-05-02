[![fr](https://img.shields.io/badge/lang-fr-red.svg)](https://github.com/Gjeffroy/mnist-keras-tuner/blob/main/README_fr.md)

# Exploring Keras Tuner on the MNIST Dataset

This repository contains Jupyter notebooks developed on Google Colab for exploring the efficacy of Keras Tuner in optimizing neural network architecture (NAS) and hyperparameters tuning for maximizing validation accuracy on the MNIST dataset.

## Overview

The MNIST dataset is a classic benchmark dataset in the field of machine learning, consisting of 28x28 pixel grayscale images of handwritten digits (0-9). In this project, we aim to utilize Keras Tuner, a hyperparameter tuning library for Keras, to optimize both the architecture of neural networks and their hyperparameters for achieving the highest validation accuracy on the MNIST dataset.

## Contents

- `MNIST_NN_hyperparameter_tuning_with_keras_tuner.ipynb`: This notebook demonstrates how to use Keras Tuner to perform hyperparameter tuning for optimizing neural network architectures (without convolutional layers) on the MNIST dataset.
- `MNIST_CNN_hyperparameter_tuning_with_keras_tuner.ipynb`: This notebook demonstrates how to use Keras Tuner to perform hyperparameter tuning for optimizing convolutional neural network architectures on the MNIST dataset.

## Getting Started

To run these notebooks, you can either clone this repository and run them locally in your Jupyter environment or open them directly in Google Colab.

### Prerequisites

- Python 3.8
- Jupyter Notebook or Google Colab
- Keras Tuner (`pip install keras-tuner`)

## Usage

1. Clone the repository:

    ```
    git clone https://github.com/your-username/mnist-keras-tuner.git
    ```

2. Navigate to the repository directory:

    ```
    cd mnist-keras-tuner
    ```

3. Open the desired notebook in your Jupyter environment or Google Colab and execute the cells sequentially.

## Results

By the end of these notebooks, you should gain insights into how Keras Tuner can be effectively utilized for hyperparameter tuning and Neural Architecture Search (NAS) to optimize neural network performance on the MNIST dataset.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Gjeffroy/mnist-keras-tuner/blob/main/LICENSE.md) file for details.

## Acknowledgments

- The MNIST dataset: http://yann.lecun.com/exdb/mnist/
- Keras Tuner: https://keras-team.github.io/keras-tuner/
