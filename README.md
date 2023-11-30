# AI-Genomics: Genetics with Artificial Intelligence Project

## Description
Welcome to the AI-Genomics repository, a project utilizing artificial intelligence for genetic analysis. This project focuses on leverage artificial intelligence to analyze DNA sequences and classify them based on discernible motifs..

## Requirements
- Python 3
- Jupyter Notebook (recommended for running in Google Colab)

## Instructions to Run the Code
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/anjimenezp/AI-Genetics.git
   cd AI-Genetics

## Project Overview
This repository contains code for a genomics project utilizing artificial intelligence for the classification of DNA sequences. The code includes the following components:

Data Extraction:

Gene sequence data is extracted from a CSV file using Pandas.
Simulated Sequence Generation (commented out):

The code provides functionality for generating simulated DNA sequences, but it is not used in the main code.
Label Quantification:

Sequence labels are encoded using scikit-learn's LabelEncoder.
One-Hot Encoding:

DNA sequences are cleaned and converted to one-hot encoding using PyTorch.
Training Splits:

The data is split into training, validation, and test sets for model training and evaluation.
DataLoader Preparation:

PyTorch DataLoaders are prepared for efficient batch processing during training.
CNN Model Definition:

A Convolutional Neural Network (CNN) is defined for classifying DNA sequences.
Training Loop Functions:

Functions for training and validation loops are defined.
Model Evaluation:

The trained model is evaluated on a test set, and performance metrics are displayed.
Plotting:

Matplotlib is used to plot training and validation loss curves.
Example Prediction:

An example DNA sequence is provided, and the trained model predicts its class.
Feel free to explore the code and adapt it to your genomics classification tasks. If you have any questions or suggestions, please open an issue.

Note: The code assumes the availability of PyTorch, scikit-learn, pandas, and matplotlib libraries. Make sure to install these dependencies before running the code.
