# ♻️ Waste Image Classification with CNN and Transformer  
### *Deep Learning Assignment 2 - 2025*

## 📌 Project Overview  
This project implements an **image-based waste-type classifier** using a **hybrid CNN–Transformer architecture**.  
Given an input image depicting a waste object, the model predicts its category among **nine different waste classes**.

The architecture combines a **ResNet-18 convolutional backbone** for visual feature extraction with a **Transformer encoder** to model global relationships between spatial features.

## 📁 Dataset  
The dataset consists of images organized into folders, one for each class:

- Cardboard  
- Food Organics  
- Glass  
- Metal  
- Miscellaneous Trash  
- Paper  
- Plastic  
- Textile Trash  
- Vegetation  

The provided dataset includes **only training data**, which is internally split into **training and validation sets** for hyperparameter tuning.  
The **test set is unseen** and evaluated through a separate evaluation pipeline.

## 🚀 Project Goals  
- Implement a hybrid **CNN + Transformer** image classification model  
- Leverage a **pretrained ResNet-18** as a frozen (or partially unfrozen) feature extractor  
- Experiment with Transformer configurations and training strategies  
- Select the best model through validation performance  
- Evaluate generalization on an unseen test set  

## 🐍 Code Structure  
The project is implemented using **Python** and **Jupyter Notebook**.

| File | Description |
|------|------------|
| `assignment.ipynb` | Model implementation, training, validation, and hyperparameter exploration |
| `evaluation.ipynb` | Evaluation pipeline for the unseen test set |
| `report.pdf` | Technical report describing architecture choices, experiments, and results |

## 👨‍💻 Team Members  
| Name | Student ID |
|------|-----------|
| *Daniele Gotti* | *1079011* |
