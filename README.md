# 📈 Stock Chart Pattern Recognition: A Comparative Study of YOLO Architectures
**Computer Vision Applied to Technical Analysis (John Murphy’s Theory)**

---

## 📌 Project Overview
This research focuses on the automated detection and classification of classical financial chart patterns (e.g., Head and Shoulders, Double Tops/Bottoms, Triangles) based on the principles of **John Murphy’s Visual Analysis**. 

The core of this project is a comprehensive benchmark between three generations of the YOLO (You Only Look Once) framework: **v8n, v11n, and v26n**. We evaluate their performance in terms of Mean Average Precision (mAP) and real-time inference speed to determine the most reliable architecture for algorithmic trading environments.

---

## 🛠 Methodology & Technical Scope
* **Domain:** Quantitative Finance & Deep Learning (Computer Vision).
* **Core Task:** Object Detection on Candlestick Charts.
* **Model Benchmarking:**
    * **YOLOv8n:** The established baseline for speed and efficiency.
    * **YOLOv11n:** Enhanced feature extraction for micro-pattern recognition.
    * **YOLOv26n (Experimental):** Optimized for complex, high-volatility financial time-series data.

---

## 📊 Data & Model Weights
Due to GitHub's file size limitations, the full dataset (candlestick images) and pre-trained model weights (.pt files) for all three versions are hosted externally.

> **🔗 [Access Model Weights & Dataset on Google Drive](https://drive.google.com/drive/folders/1U6CrAU_sJ035r6KuFdDKZ6EI1rWCUYX2?usp=sharing)**

*The Drive folder includes:*
* `Best_Weights/`: Optimized weights for v8n, v11n, and v26n.
* `Dataset/`: Labeled candlestick charts used for training and validation.
* `Inference_Results/`: Visual samples of model predictions on real-world stock charts.

---
*© 2026 - Research Project for Financial Pattern Recognition*
