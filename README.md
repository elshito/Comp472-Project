# Comp472-Project
Steven Zrihen - 40174529


This repository contains the code for evaluating different machine learning models => Naive Bayes, Decision Tree, Multilayer Perceptron (MLP), and VGG11 on the CIFAR-10 dataset. The code demonstrates how each model performs on the dataset, with specific focus on classification accuracy, precision, recall, and F1-score.

Contents of the Repository
Files:
Naive_+DecisionTree+_MLP.ipynb

This Jupyter notebook contains the implementation and evaluation of the Naive Bayes, Decision Tree, and MLP models. It handles data preprocessing, model training, and evaluation on the CIFAR-10 dataset. The notebook is meant to be run on Google Colab.
README.md

This file provides an overview of the repository contents, the purpose of each file, and instructions for running the code.
Folder: VGG11
vg11_exp3_larger.py

A Python script that runs an experiment with a larger version of the VGG11 model to analyze its performance on CIFAR-10.
vg11_exp3_smaller.py

A Python script for running an experiment with a smaller version of the VGG11 model on the CIFAR-10 dataset.
vg11_experiment2_RemovingLayer.py

This script runs an experiment where layers are removed from the VGG11 model to study the impact on performance.
vg11_experiment2_adding_layers.py

A Python script for running an experiment where additional layers are added to the VGG11 model to examine the effect on performance.
vg11_main.py

The main Python script that runs the VGG11 model on CIFAR-10 for training and evaluation.
Steps to Execute the Code
1. Data Pre-processing
First, the CIFAR-10 dataset must be prepared for use with the models. This is handled within the notebooks and Python scripts.
The Naive_+DecisionTree+_MLP.ipynb notebook includes the necessary data preprocessing steps, including loading the dataset, resizing the images (if needed), and converting the data into a suitable format for each model.
Ensure that any necessary Python libraries (like NumPy, Pandas, and Scikit-learn) are installed in your environment.
2. Running the Models
Google Colab:
Naive Bayes, Decision Tree, and MLP Models:

Open Google Colab.
Create a new notebook or open an existing one.
Upload the file Naive_+DecisionTree+_MLP.ipynb from this repository.
Run each section of the notebook sequentially. Google Colab allows you to run code in sections, which is helpful for large projects like this.
Steps:

Open Google Colab and create a new notebook.
Upload the notebook from this repository.
Follow the instructions in the notebook to preprocess the CIFAR-10 data, train the models, and evaluate their performance.
Local Python Environment:
VGG11 Model:

The VGG11 model requires more computational power and is therefore run locally.
Download and extract the VGG11 folder, containing the relevant scripts for training and evaluation.
Steps:

Ensure that Python is installed on your local system. If not, install the latest version of Python from the official Python website.
Install the necessary dependencies for the VGG11 scripts. You can do this by running the following command:
bash
Copy code
pip install -r requirements.txt
Run the desired script (e.g., vg11_exp3_larger.py, vg11_exp3_smaller.py) by executing the Python file:
bash
Copy code
python vg11_exp3_larger.py
Replace with the appropriate script you wish to run.
Key Considerations
Google Colab is ideal for quick prototyping and running smaller models like Naive Bayes, Decision Tree, and MLP. However, keep in mind that Colab depends on an internet connection and may not be reliable for long-running tasks.

Python Local Execution is more suited for running larger models like VGG11 that require substantial computational power. This avoids issues with connection drops and provides better control over the environment.
