### About the MNIST Dataset
The MNIST (Modified National Institute of Standards and Technology) dataset is one of the most well-known datasets in the field of machine learning and computer vision. It is widely used for training various image processing systems and is considered the "Hello World" of machine learning.

### Dataset Description
The MNIST dataset consists of 70,000 grayscale images of handwritten digits, each of size 28x28 pixels. These images are divided into two subsets:

- Training Set: 60,000 images
- Test Set: 10,000 images
Each image corresponds to a digit from 0 to 9. The goal is to classify each image into one of these 10 digit categories.

### Features
- Grayscale Images: Each image is a 28x28 pixel grayscale image, meaning it has a single color channel.
- Labelled Data: Each image comes with a label, which is an integer representing the digit (0-9) in the image.
- Simple Preprocessing: The images are already centered and size-normalized, which simplifies preprocessing.

### Data Format
- Images: The images are stored as numpy arrays with shape (28, 28).
- Labels: The labels are stored as integers.

### Usage
The MNIST dataset is used for a variety of purposes, including:

- Image Classification: Training and testing image classification algorithms.
- Benchmarking: Comparing the performance of different machine learning models.
- Educational Purposes: Serving as an introductory dataset for beginners in machine learning.
- Experimentation
Numerous architectures were tried to judge the model prediction. The MNIST dataset was used extensively for training, and various models were tested to evaluate their performance.

- Custom Input Handling
In addition to using the MNIST dataset for training, custom inputs were also evaluated using TensorFlow and OpenCV (cv2) to judge the models' performance on real-world data. This approach helps in understanding how well the trained models can generalize to new, unseen inputs.
