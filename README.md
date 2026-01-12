# 🎅 Santa Object Detection Project

This repository focuses on detecting Santa Claus in various festive environments using the **YOLOv8** architecture. The project involves a specialized training pipeline designed to stabilize recall, precision and reduce localization errors on a small dataset.

## 📊 Dataset: Santa-10

The project utilizes the **Santa-10** dataset, which consists of annotated images of Santa Claus.

* **Task**: Single-class object detection (Santa).
* **Labels**: Bounding boxes localized around Santa.
* **Challenges**: The dataset is small, requiring regularization to prevent overfitting (memorization) and finetuning to tackle precision cliffs at high recall.

---

## 🚀 Model Tuning & Performance


The model was refined through manual grid searches and fine-tuning to address higher than desired **DFL (Distribution Focal Loss)** and stabilization issues.

---

## 📂 Repository Contents

Training data and model weights are stored externally at GDrive, for which you should have received and invite.
This repository serves as a documentation and analysis hub with:
* **`*.html`**: Static versions of the notebooks, preserving the training logs, loss curves, and visual predictions for quick review without needing a GPU environment.
* **Report**: overview of our work, methods and results. In `/documentation`

---

## 🛠️ Instructions for Use

### **1. Accessing the Training Environment**

The full training environment, including the large dataset and model checkpoints, is hosted on **Google Drive**.

