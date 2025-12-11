# 🩷 Breast Cancer Classification Neural Network

## 📓 Overview
This project examines the construction of a deep neural network with Pytorch to classify cancer cells as either benign or malignant. This project leverages the `Breast Cancer Wisconsin (Diagnostic) Dataset`, which has 30 features and 569 samples.

## 📘 Getting Started

1. Install VS Code and Anaconda Navigator
2. Create a virtual environment with Conda to hold dependencies
3. Install the Jupyter Extension from Microsoft on VS Code
- The ipykernel package requires a conda environment to run, and it will prompt the user for installation when attempting to run a code cell in an .ipynb file  
4. Install dependencies
- Select the Conda environment as the kernel. Run this line in a notebook cell (can delete afterwards)
  
```
##capture
!pip install pandas==2.3.3
!pip install numpy==2.3.5
!pip install scikit-learn==1.8.0
!pip install matplotlib==3.10.7
!pip install torch==2.9.1
!pip install ucimlrepo
```

## 🗒️ Lab Notebook
The `bc_classification.ipynb` notebook contains the full lab data.

### First Neural Network Model
The first neural network uses CrossEntropyLoss as the loss function and Adam as the optimizer.  

### Second Neural Network Model
The second model changes the optimizer to Stochastic Gradient Descent (SGD). The loss functions for both the training and test data were constant, so this optimizer was not used in future training.

### Third Neural Network Model
The third model opts to increase the number of neurons in the input and hidden layers. This increase led to a greater decrease in the loss functions for the training and testing datasets.


## 📁 Files Included
- `bc_classification.ipynb`: Jupyter notebook containing neural network classification model
