# 🕳️ Pothole Detection using ResNet-50 (PyTorch)

This Google Colab notebook implements a **binary image classification model** to detect **potholes vs normal roads** using **transfer learning with ResNet-50**.

## 📌 Overview
- Task: Image classification (pothole detection)
- Model: ResNet-50 (pretrained on ImageNet)
- Framework: PyTorch
- Environment: Google Colab

## 🏷️ Classes
- **0** → Normal road  
- **1** → Pothole

## 🔧 What this notebook includes
- Dataset loading and preprocessing
- Train / validation split
- Data augmentation
- ResNet-50 fine-tuning
- Training and validation metrics
- Model saving and export

## 📁 Generated outputs
- `pothole_classifier_resnet50.pt` (PyTorch model)
- `pothole_resnet50_ts.pt` (TorchScript)
- `pothole_resnet50.onnx` (ONNX)


This notebook is self-contained and designed to run end-to-end on Google Colab.

