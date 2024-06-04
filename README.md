# CIFAR-10 CNN with TensorFlow

This repository contains a Convolutional Neural Network (CNN) implemented with TensorFlow to classify images from the CIFAR-10 dataset.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 different classes. This project demonstrates how to build and train a CNN to classify images into these categories using TensorFlow.

![download (4)](https://github.com/ozermehmett/Cifar-10-CNN-With-Tensorflow/assets/115498182/fdc8135c-3794-4641-a23a-3bcc06b336b3)


## Dataset

The CIFAR-10 dataset includes 10 classes: airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. Each class has 6,000 images.

- **Training set**: 50,000 images
- **Test set**: 10,000 images

## Model Architecture

The CNN model is built using TensorFlow and consists of the following layers:

1. Convolutional Layer 1
2. Max Pooling Layer 1
3. Convolutional Layer 2
4. Max Pooling Layer 2
5. Flatten Layer
6. Fully Connected Layer 1
7. Fully Connected Layer 2
8. Output Layer

## Installation

To get started, clone this repository and install the required packages:

```bash
git clone https://github.com/ozermehmett/Cifar-10-CNN-With-Tensorflow.git
cd your-repo-name
pip install -r requirements.txt
```

## Usage

To train and evaluate the model, run the following command:

```bash
jupyter notebook Cifar_10_CNN_With_Tensorflow.ipynb
```

Ensure you have Jupyter Notebook installed or use any other compatible environment to execute the notebook.

## Results

After training the model, the following results were achieved on the test set:

- **Accuracy**: %79.54
- **Loss**: 0.64

![download (5)](https://github.com/ozermehmett/Cifar-10-CNN-With-Tensorflow/assets/115498182/afde0411-7f5c-425b-9e79-cc7fb3fcfcd5)


You can visualize the training and validation accuracy and loss by running the provided notebook.

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests with your changes. Ensure your code follows the existing style and passes all tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
