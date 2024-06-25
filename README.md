# AI-Driven-Dog-Breed-Classifier

This repository contains an end-to-end machine learning project for classifying dog breeds from images using a Convolutional Neural Network (CNN). The project is implemented in Python, using TensorFlow and Keras, and is presented as a Jupyter Notebook.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to build an end-to-end deep learning model that can classify images of dogs into different breeds. The model is trained on a dataset of labeled dog images and leverages transfer learning to improve accuracy and efficiency.

## Installation

To run this project locally, you will need to have Python and Jupyter Notebook installed. Additionally, you will need to install the required libraries listed in the `requirements.txt` file.

1. Clone this repository:
    ```bash
    git clone https://github.com/mrdbourke/zero-to-mastery-ml.git
    cd zero-to-mastery-ml/section-4-unstructured-data-projects
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the project, open the Jupyter Notebook `end-to-end-dog-vision-video.ipynb` and follow the steps outlined in the notebook. The notebook includes data preprocessing, model training, evaluation, and visualization of results.

1. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

2. Open the `end-to-end-dog-vision-video.ipynb` file and run the cells sequentially.

## Dataset

The dataset used in this project consists of labeled images of dogs. The dataset is split into training, validation, and test sets. The images are preprocessed to a consistent size and normalized before being fed into the model.

## Model Architecture

The model used in this project is a Convolutional Neural Network (CNN) built with TensorFlow and Keras. The architecture includes:

- Input layer for image data.
- Several convolutional and pooling layers for feature extraction.
- Dense layers for classification.
- Transfer learning using a pre-trained model (e.g., InceptionV3, ResNet50).

## Results

The performance of the model is evaluated using metrics such as accuracy, precision, recall, and F1-score. Visualizations of the results, including confusion matrices and sample predictions, are provided in the notebook.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or improvements, feel free to create an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-name
    ```
3. Commit your changes:
    ```bash
    git commit -m "Description of feature"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-name
    ```
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

