# GUI-for-Handwritten-Digit-Recognition
This repository contains a simple Graphical User Interface (GUI) for handwritten digit recognition using a neural network. The GUI is built with Tkinter for the interface, and the neural network model is implemented using the Keras library.

## Features
<br> -Drawing Canvas: Users can draw digits on a canvas using the left mouse button.
<br> -Training the Model: Train the neural network model using the MNIST dataset by specifying the number of epochs, batch size, and learning rate.
<br> -Prediction: After drawing a digit, users can predict the digit using the trained model.
<br> -Clear Canvas: Clear the drawing canvas to start fresh.

## Prerequisites
Before running the application, ensure you have the required dependencies installed. You can install them using the following command:

```bash
pip install numpy keras Pillow
```
## Customization
Feel free to customize the neural network architecture in the 'create_model' method within the 'DigitRecognitionGUI' class. You can experiment with different layers, units, and activation functions to improve the model's performance.

## Issues and Contributions
If you encounter any issues or have suggestions for improvement, please feel free to open an issue or create a pull request. Your contributions are highly appreciated.

## Credits
<br>-The neural network model is built using the Keras library.
<br>-The GUI is created with Tkinter.
<br>-The MNIST dataset is used for training and testing the model.
