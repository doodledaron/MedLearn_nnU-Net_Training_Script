# 🫁 MedLearn – nnU-Net Training Script for Lung Lesion Segmentation

This repository contains the training script and notebook for **MedLearn**, a 3D lung lesion segmentation project using the [nnU-Net v2](https://github.com/MIC-DKFZ/nnUNet) framework. It is part of a final year project focused on applying deep learning to medical image segmentation, especially for educational use by medical students.

---

## 📂 Repository Structure

```
MedLearn_nnU-Net_Training_Script/
│
├── FYP-file/
│   └── FYP.ipynb              # Main Jupyter notebook for training/inference
├── Pipfile                   # (Optional) Environment dependencies
├── .gitignore                # Ignores large/model/data folders
└── README.md                 # This file
```

---

## 🧠 Project Highlights

- **Model**: nnU-Net 3D full-resolution U-Net
- **Domain**: Lung lesion segmentation on CT images
- **Data Format**: NIfTI (.nii.gz)
- **Target Users**: Medical students, educators, and researchers
- **Framework**: PyTorch, nnU-Net v2

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/doodledaron/MedLearn_nnU-Net_Training_Script.git
cd MedLearn_nnU-Net_Training_Script
```


### 2. Open the notebook and run the installation cell

Run Jupyter Lab or VSCode and open:

```
FYP-file/FYP.ipynb
```

Follow the steps inside the notebook to prepare the dataset, train, and evaluate.

---

## 📦 Pretrained Models & Data (Not Included)

Due to GitHub's file size limits, models and datasets are not stored in this repository.

| Resource            | Link / Access |
|---------------------|----------------|
| Pretrained Model    | [Request via email / Google Drive link] |
| Sample CT Dataset   | [Available upon request or link to public dataset] |

Estimated model size: ~1.06 GB

---

## 📊 Performance Summary

- 📈 **Mean Dice Score**: ~0.78 on internal validation (Medical Segmentation Decathlon Lung Tumor Dataset)
- 📈 **Mean Dice Score**: ~0.98 on internal validation (LCTSC | Lung CT Segmentation Challenge 2017)

---

## 👨‍💻 Author

**Tang Yu Xuan (Daron)**  
Final Year Project – Multimedia University (MMU), Cyberjaya  
🔗 [LinkedIn]([https://www.linkedin.com/in/doodledaron](https://www.linkedin.com/in/daron-tang-5052b5222/))

---

> ⚠️ This code is for educational and non-commercial research use. Please credit appropriately if reused.
