# Modular PyTorch
## Overview
This project consists of several files that are used for implementing a custom deep learning model and performing various tasks related to data loading, training, testing and visualization. The main files in this project are:

- **`model.py`**: This file contains the implementation of the custom neural network. It includes functions for training and testing. The details of the model's architecture and algorithms can be found within this file.

- **`utils.py`**: This file contains utility functions that support different operations within the project. It include functions for plotting samples as a part of data visualization, or any other common tasks that are not directly related to the model implementation.

- **`requirements.txt`**: This file lists all the necessary dependencies and their versions required to run the project successfully. It ensures that the correct versions of the libraries and packages are installed.

- **`S5.ipynb`**: This Jupyter Notebook demonstrates how to import the necessary pytorch modules, perform custom model training and testing using PyTorch, and plot the results using Matplotlib.

## Prerequisites
Before running the code in this project, make sure the following dependencies are installed:

Python (version 3.10.10)

#### Install virtualenv
`$> python3 -m pip install virtualenv`

#### setup a new virtual environment
`$> python3 -m virtualenv <venv_name>`

#### activate
Windows:

`$> <venv_name>\Scripts\activate.bat`

macOS and Linux: 

`$> source <venv_name>/bin/activate`

Any other libraries or packages mentioned in the **`requirements.txt`** file.

## Getting Started
To get started with this project, follow these steps:

Clone the repository to your local machine.
Install the required dependencies by running **`pip install -r requirements.txt`**.
Open the **`S5.ipynb`** notebook using Jupyter Notebook or any compatible environment.
Follow the instructions and code examples provided in the notebook to train the custom model and visualize the results.

## Usage
Refer to the S5.ipynb notebook for detailed usage instructions, code snippets, and examples. It provides step-by-step guidance on how to train the model, test it using PyTorch, and visualize the results using Matplotlib.