# Handwritten Digit Classifier

A complete, beginner-friendly TensorFlow project that learns to recognize the digits `0` through `9` from the MNIST dataset.

## What you will learn

- How image data is stored as pixel values
- Why pixels are scaled before training
- How to build and train a simple neural network
- How to check accuracy and read a confusion matrix
- How to make a prediction for one image

## Run it

Open [`handwritten_digit_classifier.ipynb`](handwritten_digit_classifier.ipynb) from the repository root and choose **Run all**. The notebook downloads MNIST automatically via TensorFlow/Keras on first run.

Colab already includes the required libraries. For a local Jupyter setup, install:

```bash
pip install tensorflow numpy matplotlib jupyter
```

The default run uses five epochs. The last notebook section contains optional additional training if you want to experiment further.

## Dataset

The MNIST dataset contains 28 × 28 grayscale images of handwritten digits, with 60,000 training images and 10,000 test images.

## Attribution

The full dataset, code, and explanations are included in this repository.
