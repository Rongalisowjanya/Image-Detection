# MNIST Handwritten Digit Recognition

This project implements a simple neural network using TensorFlow and Keras to recognize handwritten digits from the MNIST dataset. Additionally, it allows the user to predict digits from custom images.

## Features
- **Loads and preprocesses the MNIST dataset**
- **Trains a neural network using TensorFlow/Keras**
- **Evaluates model performance**
- **Predicts handwritten digits from custom images**
- **Visualizes the results**

## Technologies Used
- **Python**
- **TensorFlow/Keras**
- **Matplotlib**
- **NumPy**
- **PIL (Pillow)**

## Installation
### Prerequisites
Make sure you have Python installed. Then, install the required dependencies:
```sh
pip install tensorflow numpy matplotlib pillow
```

## Usage
1. Clone the repository or download the script.
2. Run the script to train the model:
   ```sh
   python mnist_recognition.py
   ```
3. To predict a custom digit:
   - Place an image file (`digit.png`) in the working directory.
   - Ensure the image is a **grayscale** handwritten digit on a white background.
   - Run the script again to see the predicted digit.

## Code Overview
- **Loads the MNIST dataset** and normalizes pixel values.
- **Builds a simple neural network** with two dense layers.
- **Trains the model** for digit classification.
- **Evaluates the model** on the test dataset.
- **Processes custom images** and predicts their digit values.

## Example Prediction
The model can predict a custom handwritten digit from an image:
```sh
Predicted Digit: 7
```

## Future Enhancements
- Improve accuracy by using **Convolutional Neural Networks (CNNs)**.
- Implement **data augmentation** for better generalization.
- Allow users to input images dynamically through a GUI.

## License
This project is open-source and available under the **MIT License**.
