# Dementia-Stage-Prediction
This repository contains a machine learning model for predicting dementia stages using MRI scans.

# **Predicting Dementia Stages Using MRI Scans**
### A Comparative Analysis of Deep Learning Approaches with ResNet50 and DenseNet121

## **Project Overview**
This project explores deep learning techniques for classifying different stages of dementia using MRI scans. The study compares the performance of **ResNet50** and **DenseNet121** in detecting Alzheimer's Disease (AD) stages. The goal is to enhance early detection and improve diagnostic accuracy using **computer vision and deep learning techniques**.

## **Dataset**
The dataset used in this study is sourced from the **Open Access Series of Imaging Studies (OASIS)**, which contains MRI scans categorized into four dementia stages:
- **Non-Demented**
- **Very Mild Demented**
- **Mild Demented**
- **Moderate Demented**

### **Preprocessing Steps**
- Images were resized to **224x224 pixels** for input to CNN architectures.
- Data augmentation techniques were applied to improve model generalization.
- Class imbalance was addressed using oversampling to enhance model training.

## **Models Used**
- **Baseline CNN Model**: Developed as a reference for benchmarking performance.
- **ResNet50**: Achieved **92.29% accuracy**, performing well in feature extraction.
- **DenseNet121**: Achieved **90.32% accuracy**, showing competitive performance.

## **Project Structure**

📂 Dementia-Stage-Prediction │── 📁 notebooks/
│ ├── dementia_prediction.ipynb # Main notebook with model implementation │── 📁 reports/
│ ├── Dementia_Study_Report.pdf # Final dissertation report │── 📄 README.md


## **Results & Insights**
- **ResNet50 outperformed DenseNet121**, particularly in classifying Moderate Dementia cases.
- **Data augmentation significantly improved generalization**, reducing overfitting.
- **Transfer learning from ImageNet pre-trained models boosted performance**, making training more efficient.

## **Installation & Setup**
To run this project locally, follow these steps:

### **1. Clone the Repository**
git clone https://github.com/HerambJadhav604/Dementia Prediction.ipynb.zip

### **2. Navigate to the Project Directory
cd Dementia-Stage-Prediction

### **3. Open the Jupyter Notebook
jupyter notebook

Open the dementia_prediction.ipynb file and run the cells to execute the model pipeline.

## **Key Findings**
- **ResNet50 performed best** with an accuracy of **92.29%**, making it the most suitable model for dementia stage classification.
- **Grad-CAM visualization** was integrated to improve model interpretability, helping medical professionals understand model predictions.
- **Efficient data preprocessing and augmentation** enhanced overall model reliability and performance.

---

## **Future Improvements**
- **Incorporating 3D MRI scans** for better spatial analysis and improved model performance.
- **Fine-tuning hyperparameters** and exploring **ensemble models** for further accuracy improvements.
- **Deploying the model as a web-based application** to enable practical usability in medical settings.

---

## **Acknowledgements**
This project was conducted as part of an **MSc dissertation** at the **University of Surrey**, under the supervision of **Dr. Roman Bauer**. Special thanks to the research community for providing open-access datasets and resources that contributed to this study.

---

## **License**
This project is intended for **research and educational purposes only**. If you use this work, please provide appropriate citations.


