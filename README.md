# Neural Network for Letter Recognition (A, B, C)

## Overview
This project implements a simple **neural network from scratch using NumPy** to recognize the letters **A, B, and C** from binary images.  
Each letter is represented as a **5×6 pixel grid (30 inputs)**. No external machine learning libraries are used.

---

## Approach
A basic **feedforward neural network** is used to classify the input images.  
The network learns by adjusting its weights using **backpropagation and gradient descent** until it can correctly identify each letter.

---

## Methodology
- Binary pixel patterns are manually defined for letters A, B, and C  
- Labels are encoded using one-hot vectors  
- Network structure:
  - Input layer: 30 neurons  
  - One hidden layer with sigmoid activation  
  - Output layer with 3 neurons (A, B, C)  
- Training is done for multiple epochs using **Mean Squared Error (MSE)** as the loss function

---

## Analysis
- Loss and accuracy are tracked during training  
- Graphs are plotted to observe learning progress  
- After training, the model predicts the correct letter and displays the input image using matplotlib

---

## Key Findings
- The model successfully learns to classify all three letters  
- Loss decreases steadily, showing proper learning  
- The project demonstrates core neural network concepts clearly without using ML frameworks

---

## Tools Used
- Python  
- NumPy  
- Matplotlib  

---
