# 🧠 Brain Tumor Classification using Deep Learning

This project focuses on classifying brain MRI images as **tumorous** or **healthy** using a deep learning pipeline built with **PyTorch**. It includes data preprocessing, augmentation, training a CNN model, and performance evaluation.

## 📁 Dataset

The dataset used consists of MRI images categorized into:
- `Brain_Tumour`
- `Healthy`

Images are organized in a folder structure compatible with PyTorch’s `ImageFolder`, and are split into training and validation sets.

## ✅ Features

- Reproducible results via fixed random seed
- Train/Validation split with organized directories
- Data augmentation using `torchvision.transforms`
- Class imbalance handled using computed class weights
- Custom CNN architecture for classification
- Learning rate scheduling via `ReduceLROnPlateau`
- Real-time training feedback using `tqdm`

## 🛠️ Project Structure
/brain_tumour_code_file.ipynb       # Main Jupyter Notebook
/Brain_Tumour_Dataset              # Original dataset folder
/Split_Brain_Tumour_Dataset        # Train and validation split folders
