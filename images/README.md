# IMAGES

This directory contains all figures, illustrations, and visualizations used throughout the project documentation. These images provide a visual understanding of the dataset, preprocessing pipeline, and the proposed deep learning architecture, making the workflow easier to interpret.

A brief description of each figure is provided below.

---

## Figure 1: Dataset Examples

Examples from the Figshare brain tumor dataset showing:

- **(a)** Original contrast-enhanced MRI image
- **(b)** Corresponding binary tumor mask
- **(c)** Tumor overlay on the MRI image

---

## Figure 2: Image Preprocessing

Illustration of the preprocessing pipeline showing 
- **(a)** the original T1-weighted contrast-enhanced MRI slice
- **(b)** the corresponding transformed image used as input for model training.

---

## Figure 3: Proposed Model Architecture

Architecture of the proposed multi-task deep learning framework consisting of a shared DenseNet121 encoder with separate branches for brain tumor classification and tumor segmentation.

---

## Figure 4: Confusion Matrix

Confusion matrix showing the classification performance of the proposed model on the test dataset.

---

## Figure 5: Training and Validation Accuracy

Training and validation accuracy of the proposed model over 20 training epochs.

---

## Figure 6: Training and Validation Loss

Training and validation loss of the proposed model over 20 training epochs.

--

## Figure 7: Multi-class ROC Curve

ROC curves illustrating the classification performance of the proposed model across the three brain tumor classes.

---

## Figure 8: Representative Classification Predictions

Representative examples of correctly classified brain tumor images showing with predictions matching the corresponding ground-truth labels.
- **(a)** Pituitary Tumor
- **(b)** Meningioma
- **(c)** Glioma

---

## Figure 9: Representative Segmentation Results

Representative segmentation results showing **Row 1:** Pituitary Tumor, **Row 2:** Meningioma, and **Row 3:** Glioma. Each row presents the original MRI image, the corresponding ground-truth mask, and the predicted segmentation mask.
