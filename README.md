NAME: SIVA SATHYA VARA PRASAD RAJU GADIRAJU
ID.NO: 700756448



# README

## Convolution Operations with Different Parameters
This section implements convolution operations using a 5x5 input matrix and a 3x3 kernel with different stride and padding configurations:
- **Stride = 1, Padding = 'VALID'**
- **Stride = 1, Padding = 'SAME'**
- **Stride = 2, Padding = 'VALID'**
- **Stride = 2, Padding = 'SAME'**

### Implementation Details
- Used NumPy and TensorFlow/Keras to perform the convolutions.
- Printed the output feature maps for each case.

## CNN Feature Extraction with Filters and Pooling
### Task 1: Edge Detection Using Sobel Filter
- Loaded a grayscale image using OpenCV.
- Applied Sobel filters in the x-direction and y-direction.
- Displayed the original image and filtered images.

### Task 2: Max Pooling and Average Pooling
- Created a random 4x4 matrix as an input image.
- Applied 2x2 max pooling and average pooling using TensorFlow/Keras.
- Printed the original matrix, max-pooled matrix, and average-pooled matrix.

## Implementing and Comparing CNN Architectures
### Task 1: Implementing AlexNet
- Built a simplified AlexNet model using TensorFlow/Keras with the following layers:
  - Multiple Conv2D layers with different filter sizes and activation functions.
  - MaxPooling layers for dimensionality reduction.
  - Fully connected layers with Dropout.
  - Output layer with 10 neurons and softmax activation.
- Printed the model summary.

### Task 2: Implementing a Residual Block and ResNet
- Defined a **residual_block** function with two Conv2D layers and a skip connection.
- Built a simple ResNet-like model with:
  - Initial Conv2D layer.
  - Two residual blocks.
  - Flatten and Dense layers.
- Printed the model summary.

### Expected Output
- Feature maps for different convolution settings.
- Sobel edge-detection results (original, Sobel-X, and Sobel-Y images).
- Pooling operation results (original, max-pooled, and average-pooled matrices).
- Model summaries for both AlexNet and the ResNet-like model.

