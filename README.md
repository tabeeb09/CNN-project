**Convolutional Neural Network (CNN) From Scratch**
This project is a custom implementation of a Convolutional Neural Network (CNN) using CPU-based operations. It includes essential components such as backpropagation, tensor operations, and supports variable kernel sizes and quantities. The network is designed for image classification tasks, using the MNIST dataset for training and testing.

**Features:**
- Custom Tensors and Backpropagation: Built from the ground up with CPU-based backpropagation for training.
- Hinge Squared Loss Function: Employed for better classification performance.
- Neural Network Weight Storage: A JSON-based storage system ensures efficient saving and loading of neural network weights.
- Variable Size Kernels: Support for different numbers and sizes of kernels, making the model highly customizable.
- Tracking System: Classification accuracy and loss are tracked across training epochs.
- Inference on CPU: Inference is performed on the CPU, allowing the model to work on machines without specialized hardware.

**Future Improvements:**
- Hardware Acceleration: Plans to integrate GPU support for faster training and inference.
- Parallel Computing: Enabling multi-threaded operations to speed up both training and inference.
- Kernel Visualization: Graphical representations of kernel transformations.
- Training Metrics: Charts to visualize model performance and efficiency during training.

**Dataset:**
- MNIST: The project uses the MNIST dataset to train and validate the neural network. This dataset includes 60,000 training images and 10,000 testing images of handwritten digits.

**Getting Started:**
To run the project, ensure that you have the following dependencies installed:
- Python 3.x
- NumPy

**Usage:**
- Clone the repository.
- Load the MNIST dataset.
- Train the model using the provided Python Code.
