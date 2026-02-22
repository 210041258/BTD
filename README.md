# Brain Tumour Detection System from MRI Input

## Project Overview
This project implements a **Brain Tumour Detection System** using MRI scans as input. The system is powered by a **Vision Transformer (ViT)** model and provides comprehensive analysis, including confidence scores and tumor type predictions.  

**ID:** 210041258  
**Branch:** part_ui_vit  

---

## My Contribution

As part of this machine learning project, I was responsible for:

1. Implementing the **core deep learning model** (Vision Transformer)  
2. Ensuring **rigorous dataset integrity** between training and testing phases  
3. Creating **visualizations and analysis tools** for model interpretation  

---

### ✅ Strict Dataset Separation
- Training and testing datasets were **collected from completely independent sources**.  
- **No data leakage** was allowed between datasets to maintain evaluation integrity.  

---

### 🧠 Vision Transformer (ViT)
- Implemented a **Vision Transformer (ViT)** model for brain tumour classification.  
- The ViT architecture provided strong performance and encouraged innovative model design.  

---

### 📈 Visualization & Evaluation
- Created visualizations to assess model performance:  
  - **Confusion Matrix**  
  - **Training & Loss Curves**  
- Enabled detailed insight into classification accuracy and model behavior during training.  

---

### 🧪 Sample Input Interface
- The notebook is structured in two parts:  
  1. **Training Section** – Full model training on MRI dataset  
  2. **Testing Section** – Quick evaluation by loading a trained model (**no retraining required**)  

> ⚠️ **Note:** Ensure all `.zip` files are properly uploaded to Google Drive.  
> Dataset download links (raw and preprocessed) are provided in `.txt` files.  
> A **localhost UI** is provided for quick demonstration and testing: accessible at `127.0.0.1` (root).  

---

## Android Deployment (Optional)
- The system can be packaged into an **APK** for Android deployment.  
- Includes Firebase integration for real-time storage of predictions.  
- Supports **image upload, tumor classification, and confidence score reporting**.  

---

## 🏁 Final Verdict

- The ViT model achieved **97% accuracy** on unseen splits from the same dataset.  
- Achieved **95%–96% accuracy** on completely independent datasets.  
- The model’s strong performance is due to:  
  - Pretrained **ViT backbone**  
  - Consistent preprocessing pipeline  
  - **Strict separation** of training and testing data  

> The UI provides a **comprehensive analysis report**, including:  
> - Brain tumor type  
> - Confidence percentage  
> - Predicted class  
> - Associated MRI image stored on the PC  

---

## Key Features
- **High-accuracy brain tumor detection**  
- **Independent dataset evaluation** for strong generalization  
- **Quick testing interface** with pretrained model loading  
- **Visualization tools** for confusion matrices and learning curves  
- Optional **Android APK deployment** with Firebase integration  

---

## References
- **Vision Transformer (ViT)** – Dosovitskiy et al., 2021  
- MRI dataset source details provided in `.txt` files  
