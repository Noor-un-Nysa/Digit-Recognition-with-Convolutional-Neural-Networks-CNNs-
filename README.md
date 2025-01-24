**Digit Recognition with Convolutional Neural Networks (CNNs)**
This project demonstrates the use of a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset using TensorFlow. The goal is to build a simple CNN model that can classify digits (0-9) with high accuracy.

**Steps Taken:**
Dataset: The MNIST dataset, containing images of handwritten digits, is loaded and preprocessed:

Images are normalized to pixel values between 0 and 1.
The data is reshaped to fit the input requirements of the model.
Labels (digit classes) are one-hot encoded.
**Model Architecture:**
A Sequential model is created using layers such as Conv2D, MaxPooling2D, and Dense to process and classify the images.
The final layer uses softmax activation to output predictions for the 10 digit classes.
Model Training:

The model is compiled with the Adam optimizer and trained using categorical crossentropy as the loss function.
The model is evaluated on the test set to calculate its accuracy.
Prediction on New Images:

The model can predict digits from new images provided by the user.
For single or multiple images, preprocessing steps like resizing, normalizing, and reshaping are applied before making predictions.
The predictions are then displayed alongside the input image.
Technologies Used:
TensorFlow (for model building and training)
Keras (high-level API for model layers and utilities)
OpenCV (for image preprocessing)
Matplotlib (for displaying images)
How to Use:
Upload your own images of handwritten digits (28x28 pixels).
The model will predict the digit from the image.
The prediction results will be displayed in the console.
