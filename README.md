# 📌 histopath-dl-oc : Deep Learning for Oral Cancer Prediction from Histopathology Data

## 📝 Description
This repository contains code and resources for **oral cancer prediction** using **deep learning** on **histopathology image datasets**.  
The project leverages **Convolutional Neural Networks (CNNs)** and **pre-trained architectures** (AlexNet, VGG16, ResNet101, DenseNet169, HRNet-W18) for classifying images into:
- Normal Mucosa
- Aphthous Ulcer
- Low-risk OPMD
- High-risk OPMD
- Oral Cancer

By applying **transfer learning**, **fine-tuning**, and advanced **image preprocessing techniques** such as Gaussian filtering, Laplace filtering, normalization, contrast enhancement, and data augmentation, the project improves prediction accuracy for early diagnosis.

---

## 📂 Repository Structure
histopath-dl-oc/
│
├── data/ # Dataset folder (or link to dataset)
├── notebooks/ # Jupyter Notebooks for experiments
├── models/ # Saved trained models
├── src/ # Python source code
│ ├── preprocessing.py # Preprocessing functions
│ ├── train.py # Training script
│ ├── evaluate.py # Evaluation metrics
│ ├── utils.py # Helper functions
│
├── results/ # Training curves, graphs, and predictions
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── LICENSE # License file
