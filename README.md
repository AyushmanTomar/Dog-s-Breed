# Dog's Breed Classification

This project is designed to classify dogs based on their breeds using machine learning techniques. The model is trained on a dataset of dog images and can predict the breed of a dog given its image.

## Repository

GitHub Repository: Dog-s-Breed

## Features

- Image preprocessing and augmentation
- Convolutional Neural Network (CNN) for image classification
- Training and evaluation scripts
- Pre-trained model for quick predictions

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/AyushmanTomar/Dog-s-Breed.git
    cd Dog-s-Breed
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\\Scripts\\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. To train the model, run:
    ```bash
    python train.py
    ```

2. To evaluate the model, run:
    ```bash
    python evaluate.py
    ```

3. To make predictions on new images, run:
    ```bash
    python predict.py --image_path path_to_your_image
    ```

## Dataset

The dataset used for training and evaluation is on kaggle

