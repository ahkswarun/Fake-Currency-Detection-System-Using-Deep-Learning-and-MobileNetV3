# Fake-Currency-Detection-System-Using-Deep-Learning-and-MobileNetV3
This project focuses on identifying fake currency notes using a Convolutional Neural Network (CNN). Leveraging deep learning techniques, the model is trained to distinguish between real and counterfeit currency based on image data.

📁 Project Structure

Data Preprocessing: Images are loaded and resized using ImageDataGenerator, and then split into training and testing sets.

Model Architecture: A CNN is built using Keras' Sequential API with layers like Conv2D, MaxPooling2D, Dropout, and Dense.

Training: The model is trained over 10 epochs and evaluated using metrics like accuracy and loss.

Visualization: Training performance is visualized using matplotlib.

Prediction: The trained model is used to predict on unseen test data.

🚀 Technologies Used

Python

TensorFlow & Keras

NumPy

Matplotlib

OpenCV

ImageDataGenerator for data augmentation
