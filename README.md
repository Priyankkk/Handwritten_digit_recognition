
# Handwritten Digit Recognition using TensorFlow and OpenCV

## Overview
This project demonstrates a neural network-based handwritten digit recognition system using TensorFlow and OpenCV. It utilizes the MNIST dataset for training and testing. The project covers data preprocessing, model training, evaluation, and visualization.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Features
- Preprocessing of handwritten digit images using OpenCV.
- Building and training a neural network with TensorFlow.
- Evaluation of model performance on the MNIST dataset.
- Visualization of model accuracy and predictions with Matplotlib.

## Technologies Used
- **Python**: Core language used for the implementation.
- **TensorFlow**: For building and training the neural network.
- **OpenCV**: For image preprocessing and manipulation.
- **NumPy**: For handling numerical operations and data arrays.
- **Matplotlib**: For visualizing training results and predictions.

## Dataset
- The model is trained and tested on the **MNIST** dataset, a standard dataset in the field of computer vision that contains 60,000 training images and 10,000 test images of handwritten digits (0-9).

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd handwritten_digit_recognition-master
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   Ensure that TensorFlow, OpenCV, NumPy, and Matplotlib are installed.

## Usage
1. **Training the Model:**
   Run the `main.py` file to start training the model:
   ```bash
   python main.py
   ```
   The model will be trained using the MNIST dataset and saved as a `.model` file.

2. **Testing the Model:**
   Once trained, the model can be used to predict handwritten digits from new images. The script will load the saved model and perform inference.

3. **Visualizations:**
   After training, the script will display accuracy graphs and some example predictions using Matplotlib.

## Results
The model achieves a high accuracy on the MNIST test dataset. Visualization plots of accuracy and loss over the training epochs are generated.

## Contributing
Feel free to contribute to the project by creating a pull request or reporting issues. Any enhancements or bug fixes are welcome!

## License
This project is licensed under the MIT License.
