# COVID-19 Radiography Classification

This project aims to classify chest X-ray images into four categories: Normal, Lung Opacity, COVID-19, and Viral Pneumonia. It utilizes a Convolutional Neural Network (CNN) model trained on the COVID-19 Radiography Dataset.

## Requirements

- Python 3.x
- Libraries: numpy, pandas, matplotlib, seaborn, opencv-python-headless, tensorflow, scikit-learn, keras, tabulate

## Installation

1. Install the required libraries:
2. Download the dataset from Kaggle:
3. Unzip the dataset:

## Usage

1. Open the Jupyter Notebook `COVID-19_Classification.ipynb`.

2. Run the notebook cells to:
    - Load and preprocess the dataset.
    - Define and train the CNN model.
    - Evaluate the model on a test set.
    - Visualize training and validation metrics.
    - Generate a classification report.

## Model Architecture

The CNN model consists of three convolutional layers with batch normalization, max pooling, and dropout for regularization. It is followed by fully connected layers and a softmax activation for multi-class classification.

## Results

The model achieves [82%] on the test set and with test loss of 1.004. A detailed classification report is provided in the notebook.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests.
