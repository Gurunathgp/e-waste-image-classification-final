# 🗂️ E-Waste Image Classification using EfficientNetV2B0 and V2B1

This project implements an **image classification system for e-waste categorisation** using transfer learning with EfficientNetV2 architectures in TensorFlow. The goal is to build an efficient model to automate e-waste sorting and management.

---

## 📌 **Project Overview**

- **Problem Statement:**  
  To classify e-waste images into their respective categories to aid efficient waste management systems.

- **Solution:**  
  - Implemented **EfficientNetV2B0** for baseline classification.  
  - Added **EfficientNetV2B1** implementation to test improvements from deeper architecture.  
  - Evaluated models using **classification reports, confusion matrices, and accuracy metrics**.  
  - Built a **Gradio interface** for real-time predictions.

---

## 🚀 **Tools and Technologies Used**

- **Platform:** Google Colab  
- **Programming Language:** Python 3  
- **Deep Learning Frameworks:** TensorFlow, Keras  
- **Pretrained Models:** EfficientNetV2B0, EfficientNetV2B1  
- **Libraries:** NumPy, Matplotlib, Seaborn, scikit-learn  
- **Deployment Interface:** Gradio  
- **Utilities:** zipfile, os, glob

---

## 📂 **Dataset**

- **Source:** Kaggle (or mention exact dataset link here)  
- **Description:** Contains images of different e-waste categories used for training, validation, and testing.

---

## ⚙️ **Implementation Steps**

1. **Import required libraries and set up environment.**  
2. **Load and preprocess dataset images** into train, validation, and test splits.  
3. **Build EfficientNetV2B0 model** with custom dense layers for classification.  
4. **Train and evaluate model performance** using accuracy, classification reports, and confusion matrix heatmaps.  
5. **Implement EfficientNetV2B1** to compare results with a deeper model variant.  
6. **Deploy a Gradio interface** for real-time image classification testing.

---

## 📊 **Results**

- Generated **classification reports** detailing precision, recall, and F1-score per category.  
- Created **confusion matrices** to visualise true vs. predicted class performance.  
- Tested models using **Gradio interface** to classify new images interactively.

---

## 🔭 **Future Work**

- Add **data augmentation** to improve generalisation.  
- Extend to **more e-waste categories**.  
- Deploy as a **web or mobile application** for use in waste management systems.  
- Implement **hyperparameter tuning** for further performance optimisation.

---

## 💡 **Key Learnings**

- Transfer learning with EfficientNetV2 architectures  
- Dataset preprocessing and pipeline management  
- Model evaluation with classification metrics and confusion matrices  
- Deployment using **Gradio for real-time applications**

---
