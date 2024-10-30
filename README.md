# Brain Tumor Detection

This project is aimed at detecting brain tumors using a convolutional neural network (CNN) based on the VGG19 architecture. The model is integrated into a Flask web application to provide a user-friendly interface for uploading and analyzing MRI images.
![alt text](https://github.com/shikharrajat/BrainTumor-Detection/blob/main/demo_image%20.png)
## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Setup](#setup)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Brain tumor detection is a critical task in the medical field. This project utilizes deep learning techniques to classify MRI images as either "Brain Tumor" or "No Brain Tumor". The trained model is deployed in a Flask web application for easy accessibility and use.

## Dataset

The dataset used for this project consists of MRI images categorized into two classes: "Yes" for images with brain tumors and "No" for images without brain tumors. The dataset is preprocessed and augmented to ensure robust model training.

## Model Architecture

The model is based on the VGG19 architecture, a popular deep learning model known for its effectiveness in image classification tasks. The base model is fine-tuned with additional dense layers to improve performance for this specific task.

## Setup

### Prerequisites

- Python 3.7+
- TensorFlow 2.x
- Flask
- OpenCV
- NumPy
- PIL

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/shikharrajat/BrainTumor-Detection.git
    cd BrainTumor-Detection
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the dataset and place it in the appropriate directory.

4. Ensure the model weights file `vgg_unfrozen.h5` is in the project directory.

## Usage

1. Run the Flask application:
    ```bash
    python app.py
    ```

2. Open your web browser and go to `http://127.0.0.1:5000/`.

3. Upload an MRI image to get the prediction result.

## Results

The model achieves high accuracy in detecting brain tumors from MRI images. Example results and performance metrics will be provided here.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

