# Handwritten Digit Recognition with `my_model`

This repository contains the implementation of a neural network model for handwritten digit recognition. The model architecture includes three dense layers and is designed to classify handwritten digits from the MNIST dataset.

## Model Architecture

The architecture of the `my_model` is as follows:

| Layer       | Output Shape | Parameters |
|-------------|--------------|------------|
| Dense (25)  | (None, 25)   | 10,025     |
| Dense (15)  | (None, 15)   | 390        |
| Dense (10)  | (None, 10)   | 160        |

Total parameters: 10,575 (41.31 KB)  
Trainable parameters: 10,575 (41.31 KB)  
Non-trainable parameters: 0 (0.00 Byte)

## Dataset

The model is trained on the MNIST dataset, which consists of 60,000 training images and 10,000 testing images of handwritten digits from 0 to 9. Each image is 28x28 pixels.

## Requirements

To run this project, you need the following libraries:

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib

## License
This project is licensed under the MIT License.

## Acknowledgements
The MNIST dataset is provided by Yann LeCun, Corinna Cortes, and Christopher J.C. Burges.
TensorFlow for providing the deep learning framework used in this project.

