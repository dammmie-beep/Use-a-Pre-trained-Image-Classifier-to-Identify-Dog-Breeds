# Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds
 ## Project Overview
Welcome to the "Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds" project! This repository is a Udacity Project AI/ML project that  contains a Python application that leverages a pre-trained image classifier to identify dog breeds in pictures. The goal is to create an accessible tool that allows users, even without a deep understanding of machine learning, to use state-of-the-art technology to classify dog breeds with a simple command.

## Features
1. Pre-Trained Models: Utilizes powerful pre-trained models such as ResNet, AlexNet, and VGG16 that have been trained on the ImageNet dataset to ensure high accuracy in breed identification.
2. Easy-to-Use: Designed with a user-friendly interface that requires minimal setup and can be used by simply passing an image through the command line.
3. Versatility: Ability to process a single image or multiple images in a directory.
4. Accuracy Report: Generates a detailed report on the classifier's predictions, including probabilities and potential mismatches.
5. Educational: Provides insights into the workings of image classifiers and the underlying technology for those who want to learn more.

## Technologies
Python 3.x
Pre-trained models from PyTorch or TensorFlow (depending on the chosen architecture)
Libraries: NumPy, PIL, argparse, and other supporting libraries

Getting Started
To get started with this project, you will need to have Python installed on your machine

Installation
Clone the repository to your local machine:

git clone (https://github.com/dammmie-beep/Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds)https://github.com/dammmie-beep/Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds

cd Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds

## Usage
To classify an image or a set of images, use the following command:

python classify.py --model <model_name> --path <path_to_image_or_directory>

Replace <model_name> with the model you want to use (resnet, alexnet, vgg16) and <path_to_image_or_directory> with the path to the image or the directory containing multiple images.
