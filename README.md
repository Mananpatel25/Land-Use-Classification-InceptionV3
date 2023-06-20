# Land Use Scene Classification using InceptionV3

This repository contains code for land use scene classification using the InceptionV3 deep learning model. The project aims to accurately classify images into different land use categories.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Dataset](#Dataset)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)

## Introduction

The land use scene classification project leverages the InceptionV3 model, pre-trained on the ImageNet dataset, and fine-tuned on a custom dataset consisting of 21 land use classes. The code provided includes model implementation, training, evaluation metrics, and prediction examples.

## Installation

To run the code locally, you need to have the following dependencies installed:

- Python (version 3.12)
- TensorFlow (version 2.12)
- Numpy (version 1.25.0)
- Scikit-Learn (version 1.2.2)
  

You can install the required packages by running the following command:

  ```shell
  pip install tensorflow numpy pillow scikit-learn
  ```


## Dataset 

You can access and download the dataset in `.zip` format from __https://www.kaggle.com/datasets/apollo2506/landuse-scene-classification__ and unzip it. 

## Usage 

**Prepare your dataset:**

  Organize your dataset into separate directories based on class labels.
  Ensure that the images are properly labeled and in a compatible format.

**Train the model:**

  Adjust the hyperparameters and settings in the train.py file to suit your needs.

  Run the following command to start the training process:

  ```shell
  python train.py
  ```

**Evaluate the model:**

  Run the evaluation script to measure the performance of the trained model:

  ```shell
  python evaluate.py
  ```

**Make predictions:**

  Use the trained model to predict the class of new, unseen images:
  ```shell
  python predict.py --image <path_to_image>
  ```

## Contributing
  Contributions are welcome! If you find any issues or have suggestions for improvement, please submit a pull request or open an issue.

## Contact
  If you have any questions or inquiries, please feel free to contact [Shreedhar Purohit] at [shreedhar2.purohit@gmail.com].
