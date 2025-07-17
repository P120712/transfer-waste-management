# Transforming Waste Management with Transfer Learning

## 🚀 Project Overview
This project applies **Transfer Learning (MobileNetV2)** to classify waste images into categories such as plastic, metal, paper, etc., enabling smarter waste segregation systems.

## 🧠 Objectives
- Automate waste classification
- Reduce human labor and improve accuracy in waste sorting

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- OpenCV, NumPy, Pandas
- Jupyter Notebook

## 📁 Dataset
Used the TrashNet dataset with the following categories:
- Cardboard
- Glass
- Metal
- Paper
- Plastic
- Trash

## 🔧 Model Architecture
- Pretrained MobileNetV2 without top layers
- Added custom Dense layers for classification
- Used softmax for multi-class prediction

## 🎯 Performance
- Achieved 90%+ accuracy
- Trained on augmented image dataset

## ▶️ How to Run
```bash
git clone https://github.com/your-username/transforming-waste-management-tl.git
cd transforming-waste-management-tl
pip install -r requirements.txt
jupyter notebook
