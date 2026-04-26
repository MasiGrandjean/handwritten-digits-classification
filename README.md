
# Handwritten Digits Classification

This project uses the **Digits dataset** from Scikit-learn to classify handwritten numbers from **0 to 9** using machine learning algorithms.

## Project Overview

The dataset contains small grayscale images of handwritten digits.  
The goal is to train a model that can recognize and predict the correct digit from image data.

## Dataset Information

- Source: Scikit-learn
- Total Samples: 1797
- Number of Classes: 10
- Digits: 0 to 9
- Image Size: 8 × 8 pixels
- Features per Sample: 64 pixel values

## Import Dataset

```python
from sklearn.datasets import load_digits
Example Usage
from sklearn.datasets import load_digits

digits = load_digits()

X = digits.data
y = digits.target

print(X.shape)
print(y.shape)
Machine Learning Applications

This dataset is commonly used for:

Classification Models
Support Vector Machine (SVM)
Logistic Regression
Random Forest
Neural Networks
Model Evaluation
Requirements

Install required libraries:

pip install scikit-learn pandas numpy matplotlib seaborn
Project Goal

Build a model that can accurately recognize handwritten digits and evaluate its performance using standard metrics.

License

This dataset is publicly available through Scikit-learn.
