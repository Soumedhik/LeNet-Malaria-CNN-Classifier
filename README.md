# LeNet-Malaria-CNN-Classifier

# Malaria Detection using TensorFlow

A machine learning project for detecting malaria parasites in blood smear images using TensorFlow and the LeNet model.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Data](#data)
- [Usage](#usage)
- [Model](#model)
- [Training](#training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Malaria is a life-threatening disease caused by parasites that are transmitted to people through the bites of infected female Anopheles mosquitoes. Early diagnosis and treatment are crucial for effective malaria management. This project aims to automatically detect malaria parasites in blood smear images using machine learning.

## Features

- Data preprocessing and augmentation.
- LeNet model for image classification.
- Training and evaluation of the model.
- Visualization of results.

## Getting Started

### Prerequisites

- Python 3.7+
- TensorFlow 2.0+
- matplotlib
- tensorflow_datasets

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/malaria-detection.git
   ```

2. Change to the project directory:

   ```bash
   cd malaria-detection
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Data

The dataset used for this project is the [Malaria dataset](https://www.tensorflow.org/datasets/catalog/malaria) from TensorFlow Datasets. It contains blood smear images with labels indicating whether they are infected (parasitized) or not infected (uninfected).

## Usage

To run the project, use the following command:

```bash
python main.py
```

This will start the training process, and you will be able to see the progress and results.

## Model

The model used for this project is a modified LeNet model, which is a classic convolutional neural network architecture for image classification. The model architecture is defined in `main.py`.

## Training

The model is trained using the `Adam` optimizer and the `BinaryCrossentropy` loss function. The training process can be configured in the `main.py` script.

## Results

After training, you can evaluate the model's performance on the test dataset. You can also visualize the results, including sample images and predictions.

## Contributing

If you'd like to contribute to this project, please follow our [contribution guidelines](CONTRIBUTING.md) and our [code of conduct](CODE_OF_CONDUCT.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, feel free to reach out to soumedhikbharati@gmail.com or create an issue on GitHub.
