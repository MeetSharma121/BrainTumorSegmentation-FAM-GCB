# 🧠 BrainTumorSegmentation-FAM-GCB

This repository contains the implementation of our research on **early brain tumor detection and segmentation**. Our method integrates advanced deep learning techniques, including the **✨ Feature Alignment Module (FAM)** and **🌐 Global Correlation Block (GCB)**, to achieve **state-of-the-art segmentation accuracy**. By using *normal brain images as a reference*, the model significantly improves robustness and performance—an approach inspired by real-world radiological practices 🧑‍⚕️🧬.

---

## 🚀 Features

- 🎯 **High Accuracy**: Achieved **99.35% segmentation accuracy** using an enhanced U-Net architecture.
- 🧩 **Feature Alignment Module (FAM)**: Aligns features from tumor and normal brain images for precise segmentation.
- 🕸️ **Global Correlation Block (GCB)**: Captures global dependencies using self-attention mechanisms for multimodal fusion.
- 🧠 **Normal Brain Reference**: Integrates normal MRI scans to enhance anomaly detection.
- 📊 **Comprehensive Evaluation**: Validated on public datasets including **BraTS2022**.

---

## 🏗️ Architecture & View:
TheView:![image](https://github.com/user-attachments/assets/444434e6-3e45-4828-bb05-48e4d891a7a8)
The Architecture Used:!![image](https://github.com/user-attachments/assets/6f362958-d7ec-4f64-9bc8-e6759e315bd9)




The model consists of:

- 🧠 **Segmentation Backbone**: Modified U-Net with encoding, fusion, and decoding paths.
- 🔄 **FAM**: Ensures feature alignment between tumor and reference images.
- 🌐 **GCB**: Enables global feature fusion across modalities.
- 🧬 **Normal Appearance Network**: Generates normal brain representations for alignment.

---

## 📚 Dataset

- 🧪 **BraTS2022**: Benchmark dataset for brain tumor segmentation.
- 🧠 **Normal Brain MRI Dataset**: Public dataset for normal brain images.

---

## 📈 Results

Achieved **99.35% accuracy** on BraTS2022. Below is a comparison with other models:

| 🧪 Model                          | 🎯 Accuracy |
|----------------------------------|-------------|
| Logistic Regression              | 84.66%      |
| KNN                              | 90.68%      |
| VGG19                            | 92.17%      |
| VGG with augmentation            | 94.85%      |
| Inception V3                     | 91.56%      |
| Inception V3 with augmentation   | 95.43%      |
| U-Net (Proposed)                 | **99.35%**  |

---

## 🗂️ Project Structure

BrainTumorSegmentation-FAM-GCB/ 
├── assets/ # Diagrams, visuals, architecture images 
├── data/ # Processed datasets and loaders 
├── models/ # Model architecture (FAM, GCB, U-Net) 
├── notebooks/ # Jupyter notebooks for EDA and training 
├── scripts/ # Training and evaluation scripts 
├── utils/ # Helper functions and modules 
├── results/ # Evaluation metrics, logs, predictions 
├── README.md # Project documentation └── LICENSE # MIT License


---
## 📝 Citation



## 📜 License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

## 🙏 Acknowledgments
- 🧠 **BraTS2022 Dataset**
- 🔥 **PyTorch**
- 🌀 **IntroVAE for normal brain image generation**

---

## 💡 Happy Coding! ✨


