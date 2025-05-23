model2
This Jupyter Notebook contains the code for a deep learning project focused on classifying crop health conditions such as diseases, pests, weeds, and healthy states using a Deep Learning Model.

Project Overview
This project aims to assist farmers and agricultural professionals in identifying plant health conditions through image classification. It uses a custom dataset organized in the ImageFolder format and applies a Deep Learning Model architecture, likely fine-tuned for better performance.

Setup Instructions
Ensure the following Python packages are installed:

• pip install numpy pandas torch torchvision matplotlib scikit-learn

Or use a requirements file if provided:

• pip install -r requirements.txt

Contents
Data loading and preprocessing using transforms and datasets

Model architecture setup and loading

Training with validation and testing loops

Performance visualization and metrics

Model saving/loading for inference

Dataset
The dataset used is a custom ImageFolder dataset of plant health (pests, diseases, weeds, healthy crops), structured in class-wise folders suitable for PyTorch’s ImageFolder.

Libraries Used

• matplotlib

• numpy

• pandas

• sklearn

• torch

• torchvision

Results
The notebook includes accuracy metrics, loss curves, and visual outputs of model predictions. Performance metrics indicate the model is suitable for real-time mobile deployment.

Author
Shane Steve A – Final Year Project

Team Members:

• Shane Steve A

• Nafees Ahamed A

• Sri Sabari I.T
