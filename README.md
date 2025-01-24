### **🌌 Digit Recognition with Convolutional Neural Networks (CNNs) 🚀**

A simple project that demonstrates the power of **Convolutional Neural Networks (CNNs)** to recognize handwritten digits from the **MNIST dataset** using **TensorFlow**. This model can classify digits (0-9) with impressive accuracy!

### **📚 Steps Taken:**
- **Dataset**: 
  - Loaded the **MNIST dataset** of handwritten digits 🪐.
  - Preprocessed the data: normalized pixel values, reshaped images, and one-hot encoded labels.
  
- **Model Architecture**: 
  - Built a **Sequential CNN model** with **Conv2D**, **MaxPooling2D**, and **Dense** layers. 🌠
  - The final layer uses **softmax activation** to classify digits from 0 to 9.

- **Model Training**: 
  - Compiled the model using the **Adam optimizer** and **categorical crossentropy** loss. 🚀
  - Evaluated model accuracy on test data 🌝.

- **Prediction on New Images**:
  - The model predicts digits from **new user images** (28x28 pixels). 🌙
  - Supports single or batch image predictions with preprocessing steps applied automatically. 🌜

### **⚙️ Technologies Used:**
- **TensorFlow**: For building, training, and evaluating the CNN model 🚀
- **Keras**: High-level API for building model layers 🌙
- **OpenCV**: Image processing and handling 🪐
- **Matplotlib**: Visualizing images and results 🌟

### **🚀 How to Use:**
1. **Upload** your own 28x28 pixel images of handwritten digits. 🌍
2. The model will **predict the digit** in the image. 🌠
3. View the prediction result directly in the console. 🌝
