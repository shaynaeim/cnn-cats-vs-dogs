# 🐱🐶 CNN on Custom Images of Cats and Dogs

This project demonstrates how to **train a Convolutional Neural Network (CNN)** from scratch using a **custom dataset of cats and dogs**.  
It’s designed as a **code-along exercise** to show how to handle your own image data — from organizing directories and applying transformations, to training, validating, and testing a model built in **PyTorch**.

---

## 📘 Project Overview

In this project, we:
- Load and preprocess a custom dataset of cat and dog images  
- Build a CNN architecture from scratch using `torch.nn`  
- Train and validate the model on labeled images  
- Evaluate its performance and visualize predictions  

This hands-on example demonstrates how to manage **custom image data** and apply deep learning techniques for binary image classification.

---

## 🧩 Technologies Used

- **Python 3.10+**  
- **PyTorch**  
- **torchvision**  
- **NumPy**  
- **Matplotlib**  
- **Jupyter Notebook**  

---

## 🚀 Project Workflow

1. **Dataset Preparation**  
   - Organize the dataset into `train/`, `val/`, and `test/` directories.  
   - Each subfolder contains two classes: `cats/` and `dogs/`.  

2. **Data Preprocessing**  
   - Apply transformations with `torchvision.transforms`:
     - Resize and crop images  
     - Convert to tensors  
     - Normalize pixel values  

3. **Model Architecture**  
   - Build a simple CNN with convolutional, pooling, and fully connected layers.  
   - Use ReLU activations and softmax/sigmoid output for binary classification.

4. **Model Training**  
   - Use `Binary CrossEntropy` or `CrossEntropyLoss` as the loss function.  
   - Optimize using `Adam` or `SGD`.  
   - Monitor training and validation accuracy per epoch.

5. **Model Evaluation & Testing**  
   - Evaluate model performance on unseen test data.  
   - Visualize sample predictions and confusion matrix.

---
