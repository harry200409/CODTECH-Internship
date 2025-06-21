# Convolutional Neural Network (CNN) for Image Classification

This project is part of the **CODTECH Machine Learning Internship – Task 3**. It involves building and training a **Convolutional Neural Network (CNN)** using **TensorFlow/Keras** for image classification on the **CIFAR-10 dataset**.

---

## Task Objective

> Build a CNN for image classification using **TensorFlow** or **PyTorch** and evaluate its performance on a test dataset.

---

## Project Structure

```text
├── cnn_image_classification.ipynb # Main Jupyter Notebook with code and results
├── README.md # Project documentation
```


---

## Dataset: CIFAR-10

- **Total Samples**: 60,000
- **Image Size**: 32x32 pixels, RGB
- **Classes**: 
  - airplane
  - automobile
  - bird
  - cat
  - deer
  - dog
  - frog
  - horse
  - ship
  - truck

---

## Libraries Used

```bash
tensorflow
matplotlib
numpy
```

### You can install them using:

```bash
pip install tensorflow matplotlib numpy
```

## Steps Implemented

- Load CIFAR-10 dataset from tensorflow.keras.datasets

- Normalize pixel values for faster convergence

- Visualize sample images and class labels

- Build a CNN using Keras Sequential API

- Compile the model with:

    Optimizer: Adam

    Loss: Sparse Categorical Crossentropy

- Train the model over 10 epochs

- Evaluate the model on test data

- Plot training vs validation accuracy and loss

- Predict and visualize test results


## Model Architecture

- Conv2D → ReLU → MaxPooling

- Conv2D → ReLU → MaxPooling

- Conv2D → Flatten → Dense → Output Layer

## Evaluation Metrics

- Test Accuracy: ~70–75% (varies by run)

- Loss Curve: Displayed using Matplotlib

- Accuracy Curve: Training vs Validation

## How to Run

1. Clone this repository

2. Install dependencies

3. Launch the notebook:

```bash

jupyter notebook cnn_image_classification.ipynb

```


