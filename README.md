# Dog-Breed-Classifier

This repository contains a Convolutional Neural Network (CNN) model designed to classify different dog breeds using TensorFlow. The project is implemented in Python using a Jupyter Notebook in Google Colab.

## Introduction

The "Dog Vision" project leverages a CNN model to accurately identify the breed of a given dog from an image. This model can be used in various applications such as dog breed recognition in veterinary practices, animal shelters, or for pet owners who want to know more about their furry friends.

## Problem Statement

Identifying the breed of a dog given an image of the dog.

## Dataset

The data we're using is from Kaggle's Dog Breed Identification competition.

Dataset link: [Kaggle Dog Breed Identification](https://www.kaggle.com/c/dog-breed-identification/data)

## Evaluation

The evaluation is based on a file with prediction probabilities for each dog breed for each test image.

Evaluation link: [Kaggle Dog Breed Identification Evaluation](https://www.kaggle.com/c/dog-breed-identification/overview/evaluation)

## Features

Some information about the data:

- We are dealing with images (unstructured data), so it's probably best to use deep learning/transfer learning.
- There are 120 breeds of dogs (this means there are 120 different classes).
- There are around 10,000+ images in the training set (with labels).
- There are around 10,000+ images in the test set (without labels).

## Installation

To run the code in this repository, you need to have the following dependencies installed:

- Python 3.x
- Jupyter Notebook
- TensorFlow
- TensorFlow Hub
- NumPy
- pandas

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Dog-Breed-Classifier.git
```

2. Upload the notebook to Google Colab:
     - Go to Google Colab.
     - Click on "File" > "Upload notebook".
     -Select the `Dog Vision.ipynb` file from your cloned repository.
