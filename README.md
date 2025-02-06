# 🦴 Lumbar Spine Degenerative Condition Classification (Ongoing Project)

## 📌 Project Overview
This project aims to classify **lumbar spine degenerative conditions** using deep learning, leveraging an **ensemble model combining YOLO, 3D Vision Transformers (ViT), and LDSC models**. The goal is to **improve diagnosis accuracy in medical imaging**.

### **🚀 Current Status**
✅ Initial ensemble model trained and submitted on **Kaggle**.  
✅ **YOLO + 3D ViT + LDSC** approach implemented.  
🔄 **Ongoing Improvements:**
- Exploring **MONAI & MedicalNet** for enhanced medical imaging capabilities.
- Converting dataset to **NIfTI format** for compatibility with MONAI-based approaches.
- Computing power limitations for NIfTI processing—need better resources.

---

## **🗂️ Dataset**
- **Type**: Medical imaging dataset for lumbar spine classification.
- **Current Format**: DICOM.
- **Planned Future Conversion**: NIfTI format for **MONAI & MedicalNet**.

📌 **Preprocessing Steps**
- Normalization and contrast enhancement.
- Data augmentation (flip, rotation, intensity scaling).
- Extracting **3D volumetric features**.

---

## **🛠️ Model Architectures**
### **1️⃣ Current Approach: YOLO + 3D Vision Transformers (ViT) + LDSC**
- **YOLO**: Detects spine regions in medical images.
- **3D ViT**: Extracts deep volumetric features.
- **LDSC (Lumbar Disc Shape Classification)**: Further refines diagnosis.

📌 **Findings**:
- **Further tuning required** for improving sensitivity & specificity.

---

### **2️⃣ Future Work: MONAI & MedicalNet**
- **MONAI** (Medical Open Network for AI):
  - Provides optimized architectures for **3D segmentation & classification**.
  - Requires **NIfTI format** for medical imaging.
- **MedicalNet**:
  - Pretrained models specifically designed for **3D medical images**.
  - Can improve feature extraction compared to current CNN-based approaches.

🔄 **Challenges**:
- **Need high-performance computing resources** for NIfTI model training.

---

📌 **Key Insights**:
- **3D feature extraction is crucial** for lumbar spine analysis.
- **Hybrid approaches combining CNNs & Transformers perform well**.
- **Further fine-tuning required for generalization**.

---

## **📷 Kaggle Submission Proof**
<img width="1233" alt="Screenshot 2024-12-11 at 12 51 57 AM" src="https://github.com/user-attachments/assets/5ddd1479-47a0-45ba-ae95-3fc27a8da266">

---

## **🔍 Next Steps**
1. **Convert dataset into NIfTI format** for compatibility with MONAI & MedicalNet.
2. **Experiment with MONAI & MedicalNet models** to enhance classification.
3. **Fine-tune hyperparameters & explore better ensemble techniques**.

---
