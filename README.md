# 🧠 Brain Tumor Classification using Custom - CNN

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

- `brain_tumour_code_file.ipynb` This is the main Jupyter Notebook.
- `Brain_Tumour_Dataset` It is the dataset folder containing MRI Scans iof healthy and tumourous brain.
- `Split_Brain_Tumour_Dataset` Train and validation split folders for model training and evaluation.
- `test_code.ipynb` Notebook file to check Model Accuracy on random MRI Scans.
- `Test_Images` This folder contains Random MRI scans downloaded from Google.

## 🔍 Future Work

- Integrate segmentation models (e.g., U-Net, DeepLabV3+).
- Extend to multi-class classification or 3D MRI volumes.
- Deploy model as a web application for clinical use.
 
## 👨‍💻 Author

- Developed by Dixit Rikhari
Feel free to connect or collaborate!
