# Handwritten Numbers Classification

This project builds a neural network using PyTorch to classify handwritten digits from the MNIST dataset. It's a simple example to practice machine learning skills.

## Project Structure

- `main.ipynb`: Jupyter Notebook containing the code for data loading, preprocessing, model definition, training, and evaluation.
- `README.md`: This file.
- `data/`: Directory where the MNIST dataset will be stored.

## Setup Instructions

1. **Install dependencies**:
    ```bash
    pip install torch torchvision
    ```

2. **Run the Jupyter Notebook**:
    Open `main.ipynb` in Jupyter Notebook and execute the cells step by step.

## Model Overview

- **Input**: 28x28 grayscale images of handwritten digits.
- **Output**: Predicted digit (0-9).
- **Architecture**:
    - Fully connected layer (28*28 -> 128)
    - ReLU activation
    - Fully connected layer (128 -> 64)
    - ReLU activation
    - Fully connected layer (64 -> 10)

## License

This project is licensed under the MIT License.
