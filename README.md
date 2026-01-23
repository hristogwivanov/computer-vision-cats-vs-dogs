# Cats vs Dogs Image Classification (PyTorch)

This repository contains a PyTorch implementation of a **simple Convolutional Neural Network (CNN)** for binary image classification (cats vs dogs), trained on a subset of the Dogs vs Cats dataset from Kaggle.  
The project is implemented and executed in **Google Colab** with GPU acceleration.

## Contents
- `Task1_01_dogs_vs_cats.ipynb` – Jupyter Notebook containing dataset preparation, model definition, training, and validation.

## Dataset Access
The dataset is downloaded from Kaggle using the Kaggle API.  
When running the notebook in **Google Colab**, the Kaggle credentials (`KAGGLE_USERNAME` and `KAGGLE_KEY`) must be provided as **private Colab Secrets**.  
Alternatively, the dataset can be downloaded manually from Kaggle and placed in the working directory.

## Results
The model achieves approximately **70–75% validation accuracy**, which is expected for a shallow CNN trained on a limited dataset.

## Technologies
- Python  
- PyTorch  
- Torchvision  
- Google Colab
