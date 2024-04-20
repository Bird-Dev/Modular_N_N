# Modular_N_N
Basic neural network

---

# Neural Network for MNIST Classification

This repository contains a simple implementation of a neural network for classifying handwritten digits using the MNIST dataset. The neural network is implemented from scratch using Python and NumPy.

## Features

- **Data Loading**: Load the MNIST dataset from CSV files.
- **Data Preprocessing**: Normalize the pixel values to the range [0, 1].
- **Model Architecture**: Single hidden layer neural network with ReLU activation and softmax output layer.
- **Training**: Gradient descent optimization to train the model.
- **Evaluation**: Compute training and test accuracy during training.

## Requirements

- Python 3.x
- NumPy
- pandas
- matplotlib

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/your-username/neural-network-mnist.git
   ```

2. Navigate to the project directory:

   ```
   cd neural-network-mnist
   ```

3. Install the required packages:

   ```
   pip install -r requirements.txt
   ```

## Usage

1. Place your MNIST training and testing CSV files in the project directory.
2. Update the file paths in the `main` function of the `neural_network.py` file:

   ```python
   train_file_path = "/path/to/train/file.csv"
   test_file_path = "/path/to/test/file.csv"
   ```

3. Run the `neural_network.py` script:

   ```
   python neural_network.py
   ```

## Configuration

You can modify the following configuration parameters in the `neural_network.py` file:

- `LEARNING_RATE`: Learning rate for gradient descent.
- `NUM_ITERATIONS`: Number of iterations for training.
- `HIDDEN_UNITS`: Number of units in the hidden layer.
- `NUM_CLASSES`: Number of classes (e.g., 10 for MNIST).

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Feel free to modify the README file according to your needs and add any additional sections or details you find necessary.
