# 🐾 Pet Breed Classification via Architecture Fusion 🚀

This repository contains the implementation of a **Dual-Backbone Fusion Architecture** designed for fine-grained image classification using the Oxford-IIIT Pet Dataset.

Combining the structural depth of ResNet50 🏗️ with the textural efficiency of MobileNetV2 📱, this model achieves high accuracy in distinguishing between 37 different breeds of cats and dogs.

## ✨ Features

* 🧬 **Dual-Backbone Fusion**: Late feature concatenation of ResNet50 and MobileNetV2
* 🖼️ **Fine-Grained Accuracy**: Optimized for subtle differences between similar animal breeds
* ⚡ **Transfer Learning**: Leverages ImageNet pretrained weights for rapid convergence
* 📊 **Data-Driven Visuals**: Includes training loss/accuracy graphs and prediction galleries

## 🛠️ Prerequisites

* 🐍 Python 3.12 is recommended for compatibility and performance
* A system with a GPU (CUDA) is preferred for faster training, but CPU is supported

## 🏁 Getting Started

### 1. 📥 Clone the Repository

```bash
git clone https://github.com/mihkuno/IMPROCV.git
cd IMPROCV
```

### 2. 📦 Install Dependencies

Ensure you have your virtual environment activated, then install the necessary packages:

```bash
pip install -r requirements.txt
```

### 3. 📓 Run the Notebook

The entire pipeline—from data download to training and inference—is contained within the Jupyter Notebook:

```bash
jupyter notebook flower_fusion_case_study.ipynb
```

Once opened, select "Run All" to execute the data-driven analysis and view the visualizations. 💡

## 📂 Project Structure

* `flower_fusion_case_study.ipynb`: 📝 The main notebook containing the model logic and visualizations
* `case_study_report.md`: 📖 Formal LNCS-formatted report
* `data/`: 📁 (Generated automatically) Stores the Oxford-IIIT Pet Dataset

## 🎓 Academic Credit

**Author**: Joeniño D. Cainday  
**Institution**: University of Science and Technology of Southern Philippines  
**Course**: CS412 Final Requirement  
**Date**: December 17, 2025
