# cat-dog-classifier
this is a demo project for Cat vs Dog Image Classifier with Label Studio Integration
# 🐱🐶 Cat vs Dog Image Classifier

This project demonstrates an end-to-end machine learning workflow using Label Studio for annotation and PyTorch for training. It supports both Google Colab and local Python environments.

## 🔧 Features
- Image annotation via Label Studio
- Dual-mode execution (Colab + Local)
- CNN model for binary classification
- Visualization of predictions and training metrics

## 🚀 Getting Started

### Colab Version
1. Open `notebooks/colab_version.ipynb` in Google Colab.
2. Mount Google Drive and launch Label Studio via ngrok.
3. Annotate images and export labels.
4. Train and evaluate the model.

### Local Version
1. Clone the repo and install dependencies.
2. Run Label Studio locally (`label-studio start`).
3. Annotate and export to `data/labels.csv`.
4. Run `notebooks/local_version.ipynb` to train the model.

## 📁 Folder Structure
cat-dog-classifier/
├── data/
│   ├── images/
│   └── labels.csv
├── notebooks/
│   ├── colab_version.ipynb
│   └── local_version.ipynb
├── models/
│   └── saved_model.pth
├── utils/
│   └── preprocessing.py
├── README.md

## 🧠 Credits
Built by Charlie using:
- Label Studio
- PyTorch
- PIL, Pandas, Matplotlib
