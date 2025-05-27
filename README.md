# 🔍 X-Ray Prohibited Item Detection

## 📌 Project Overview

This project aims to develop a **deep learning-based detection system** for identifying prohibited items—specifically **cutters**—in X-ray scanned luggage images. With increasing crowd density in public transportation hubs, the need for **accurate, fast, and robust security inspection tools** has become critical. Traditional manual inspection struggles with occlusion and clutter, so this project leverages **convolutional neural networks (CNNs)** to automate and enhance threat detection in complex X-ray imagery.

## 🎯 Objectives

- Build a **neural architecture** that can detect prohibited items in occluded and cluttered luggage.
- Output both **class predictions** and **bounding boxes** for detected items.
- Achieve **high accuracy and real-time performance**, even under challenging visual conditions.
- Evaluate the model using standard detection metrics and visualize results for performance analysis.

## 🧠 Methods

The project explores several model development strategies:

- **CNN-based detection models** (e.g., Faster R-CNN, YOLO, RetinaNet)
- **Attention mechanisms** to improve performance under heavy occlusion
- Data preprocessing and **augmentation techniques** to improve generalizability
- **Bounding box regression** and **classification heads** trained jointly

Advanced extensions may include:
- De-occlusion attention modules
- Domain adaptation using multi-dataset learning
- XAI techniques (e.g., Grad-CAM) for interpretability

## 🗃 Dataset

We use the **OPIXray-v2** dataset, a publicly available benchmark for prohibited item detection in X-ray security inspections.

📎 Dataset URL: [OPIXray GitHub Repository](https://github.com/OPIXray-author/OPIXray/)

- Contains **8885 X-ray images**
- 5 classes of **cutter-type prohibited items**
- Images contain various **levels of occlusion and stacking**

## 📊 Evaluation Metrics

- **Precision, Recall, F1-score**
- **IoU (Intersection over Union)**
- **mAP (mean Average Precision)**
