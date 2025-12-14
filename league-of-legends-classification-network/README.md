# 🎮 League of Legends Classification Neural Network

## 📓 Overview
This project examines the construction of a neural network with Pytorch to classify either or not a League of Legends match was won based on culminative player statistics.

## 📘 Getting Started 
1. Install VS Code and Anaconda Navigator
2. Create a virtual environment with Conda to hold dependencies
3. Install the Jupyter Extension from Microsoft on VS Code

- The ipykernel package requires a conda environment to run, and it will prompt the user for installation when attempting to run a code cell in an .ipynb file

4. Install dependencies

- Select the Conda environment as the kernel. Run this line in a notebook cell (can delete afterwards)
'''
##capture
!pip install pandas==2.3.3
!pip install numpy==2.3.5
!pip install matplotlib==3.10.7
!pip install scikit-learn==1.8.0
!pip install seaborn==0.13.2
!pip install torch==2.9.1
'''

## 🗒️ Lab Notebook
The `lol_predictor.ipynb` notebook contains the full lab.

## 📁 Files Included
- `lol_predictor.ipynb`: Jupyter notebook containing a neural network model workflow.
- `league_of_legends_data_large.csv`: .csv file of Legend of Legends match data provided by IBM.
