# MNIST Digit Classification: Perceptron vs ANN vs CNN

## 📌 Project Overview

This project presents a comparative analysis of three machine learning and deep learning approaches for handwritten digit classification using the MNIST dataset:

* Perceptron
* Artificial Neural Network (ANN)
* Convolutional Neural Network (CNN)

All three models are trained and evaluated on the same MNIST dataset to compare their classification performance.

## 🎯 Objective

The main objective of this project is to understand how different neural network architectures perform on image classification and why CNNs are generally more effective for image-based tasks.

## 📊 Dataset

The project uses the **MNIST handwritten digit dataset**.

* Training images: 60,000
* Testing images: 10,000
* Image size: 28 × 28 pixels
* Classes: 10 (digits 0–9)
* Image type: Grayscale

## 🧠 Models Used

### 1. Perceptron

A basic linear classification model used as a baseline.

### 2. Artificial Neural Network (ANN)

A fully connected neural network that learns patterns from flattened image pixels.

### 3. Convolutional Neural Network (CNN)

A deep learning model designed for image classification. CNN uses convolution and pooling layers to learn spatial features from images.

## 🔬 Comparison

The models will be compared using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Training Time

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* TensorFlow / Keras
* Jupyter Notebook

## 📁 Project Structure

```text
MNIST-Perceptron-ANN-CNN/
│
├── notebooks/
│   └── MNIST_Comparison.ipynb
│
├── models/
│
├── results/
│
├── README.md
├── requirements.txt
└── .gitignore
```

## 🚀 Workflow

```text
MNIST Dataset
      ↓
Data Preprocessing
      ↓
 ┌──────────────┬──────────────┬──────────────┐
 ↓              ↓              ↓
Perceptron      ANN            CNN
 ↓              ↓              ↓
Evaluation      Evaluation     Evaluation
 └──────────────┼──────────────┘
                ↓
         Model Comparison
```

## 📈 Results

The final results will be added after training and evaluating all three models.

| Model      | Accuracy | Training Time |
| ---------- | -------: | ------------: |
| Perceptron |      TBD |           TBD |
| ANN        |      TBD |           TBD |
| CNN        |      TBD |           TBD |

## 💡 Conclusion

This project demonstrates the difference between a basic linear classifier, a fully connected neural network, and a convolutional neural network for image classification.

The final comparison will help explain the advantages of CNNs for extracting spatial features from images.

## 👨‍💻 Author

**Harshit Mehra**

GitHub: `harshmehra001-hub`
