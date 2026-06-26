# MNIST Handwritten Digit Recognition

A deep learning model that classifies handwritten digits (0–9) using the MNIST dataset, built with TensorFlow and Keras.

## Results
- **Test Accuracy: 97.51%**
- Dataset: 70,000 images (60,000 train / 10,000 test)

## What's in this Project
- Data exploration with sample digit visualizations
- Data preprocessing (normalization)
- Neural network model with Dropout regularization
- Training with validation split
- Accuracy and loss curves
- Confusion matrix to analyze errors
- Single image prediction demo

## Model Architecture
| Layer | Details |
|-------|---------|
| Flatten | Input: 28×28 → 784 |
| Dense | 128 neurons, ReLU activation |
| Dropout | Rate: 0.2 |
| Dense | 10 neurons, Softmax activation |

## Tech Stack
- Python 3.x
- TensorFlow / Keras
- Scikit-learn
- Matplotlib

## How to Run

1. Clone this repository
```
git clone https://github.com/YOUR_USERNAME/mnist-digit-recognition.git
cd mnist-digit-recognition
```

2. Install dependencies
```
pip install -r requirements.txt
```

3. Open the notebook
```
jupyter notebook MNIST_Handwritten_Digit_Recognition.ipynb
```

4. Click **Kernel → Restart & Run All**

## Project Structure
```
mnist-digit-recognition/
├── MNIST_Handwritten_Digit_Recognition.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```
