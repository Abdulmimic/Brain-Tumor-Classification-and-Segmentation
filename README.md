# BRAIN TUMOR CLASSIFICATION AND SEGMENTATION USING DENSENET121

## PROJECT OVERVIEW

This project presents a deep learning framework for the simultaneous classification and segmentation of brain tumors from contrast-enhanced MRI images. The proposed model employs a pretrained DenseNet121 as a shared encoder with two task-specific branches: a classification head for identifying tumor types and a U-Net-style decoder for tumor segmentation. The multi-task learning approach enables accurate tumor diagnosis while simultaneously localizing tumor regions.

---

## OBJECTIVES

- Develop a dual-task deep learning model for simultaneous brain tumor classification and segmentation.
- Classify brain tumors into three categories:
  - Meningioma
  - Glioma
  - Pituitary Tumor
- Accurately segment tumor regions from MRI images.
- Improve diagnostic performance using shared feature representations.
- Evaluate the model using both classification and segmentation metrics.

---

## FEATURES

- Multi-task Deep Learning Framework
- DenseNet121 Pretrained Encoder
- U-Net-style Segmentation Decoder
- Multi-class Brain Tumor Classification
- Binary Tumor Segmentation
- Data Augmentation using Albumentations
- Transfer Learning with ImageNet Weights
- Comprehensive Performance Evaluation

---

## DATASET

- **Dataset:** Figshare Brain Tumor Dataset
- **Modality:** Contrast-Enhanced T1-weighted MRI
- **Total Images:** 3,064 MRI slices
- **Patients:** 233
- **Image Size:** 224 × 224
- **Tumor Classes:**
  - Meningioma
  - Glioma
  - Pituitary Tumor

---

## TECHNOLOGIES USED

- Python
- PyTorch
- Torchvision
- Albumentations
- NumPy
- Matplotlib
- OpenCV
- Scikit-learn
- Google Colab

---

## MODEL ARCHITECTURE

The proposed framework consists of:

- DenseNet121 (Pretrained on ImageNet)
- Shared Feature Encoder
- Classification Head
- U-Net-style Segmentation Decoder
- Multi-task Learning Framework

---

## PROJECT WORKFLOW

1. Load MRI Dataset
2. Image Preprocessing
3. Data Augmentation
4. Dataset Splitting
5. Model Construction
6. Model Training
7. Classification Prediction
8. Tumor Segmentation
9. Performance Evaluation

---

## RESULTS

### Classification Performance

| Metric | Value |
|--------|-------:|
| Test Accuracy | 99.13% |
| Precision | 98.90% |
| Recall | 98.98% |
| F1 Score | 98.94% |
| ROC-AUC | 99.99% |

### Segmentation Performance

| Metric | Value |
|--------|-------:|
| Dice Score | 0.7691 |
| IoU | 0.6738 |
| Pixel Accuracy | 0.9941 |

---

## INSTALLATION

1. Clone the repository

```bash
git clone https://github.com/Abdulmimic/Brain-Tumor-Classification-and-Segmentation.git
```

2. Install the required libraries

```bash
pip install -r requirements.txt
```

3. Open `brain_tumor_classification_segmentation.ipynb` and run all cells sequentially.

---

## PROJECT STRUCTURE

```text
Brain-Tumor-Classification-and-Segmentation/
│
├── brain_tumor_classification_segmentation.ipynb
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
└── images/
```

---

## FUTURE IMPROVEMENTS

- Extend to 3D MRI volumetric analysis.
- Support multi-modal MRI sequences.
- Improve segmentation using Transformer-based architectures.
- Deploy the model as a web application.
- Integrate Explainable AI techniques such as Grad-CAM.

---

## LICENSE

This project is licensed under the MIT License.

---

## AUTHOR

**Abdul Rahman**

Biomedical Engineering Graduate (2026)

Aspiring AI / Machine Learning Engineer
