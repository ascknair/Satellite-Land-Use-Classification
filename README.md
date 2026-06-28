# Satellite Land-Use Classification using Deep Learning

## Project Overview

This project presents a deep learning framework for satellite land-use classification using the EuroSAT RGB dataset. The objective is to classify satellite images into ten different land-use categories by comparing a custom Convolutional Neural Network (CNN) with two state-of-the-art transfer learning models: MobileNetV2 and EfficientNetB0.

The project was developed as part of the **Pattern Recognition** course and demonstrates the complete deep learning workflow, including dataset preprocessing, model development, transfer learning, evaluation, and error analysis.

---

## Dataset

**Dataset:** EuroSAT RGB Dataset

**Source:**
https://www.kaggle.com/datasets/apollo2506/eurosat-dataset

### Dataset Statistics

| Attribute | Value |
|------------|--------|
| Total Images | 27,000 |
| Classes | 10 |
| Image Size | 64 × 64 |
| Image Type | RGB |
| Training Split | 70% |
| Validation Split | 15% |
| Test Split | 15% |

---

## Land-Use Classes

- AnnualCrop
- Forest
- HerbaceousVegetation
- Highway
- Industrial
- Pasture
- PermanentCrop
- Residential
- River
- SeaLake

---

## Models Implemented

- Custom CNN
- MobileNetV2 (Transfer Learning)
- EfficientNetB0 (Transfer Learning)

---

## Methodology

The project follows the following workflow:

1. Dataset loading
2. Dataset exploration
3. Dataset cleaning
4. Data preprocessing
5. Data augmentation
6. Custom CNN training
7. MobileNetV2 transfer learning
8. EfficientNetB0 transfer learning
9. Model evaluation
10. ROC analysis
11. Error analysis
12. Inference time comparison

---

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report
- ROC Curve
- Error Analysis
- Inference Time

---

## Final Results

| Model | Test Accuracy |
|--------|--------------:|
| Custom CNN | 89.70% |
| MobileNetV2 | 86.12% |
| EfficientNetB0 | **92.05%** |

EfficientNetB0 achieved the highest overall classification performance on the EuroSAT RGB dataset.

---

## Project Structure

```
Satellite-Land-Use-Classification/
│
├── notebook/
│
├── outputs/
│   ├── confusion_matrices/
│   ├── figures/
│   ├── predictions/
│   ├── roc_curves/
│   └── tables/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/ascknair/Satellite-Land-Use-Classification.git
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the notebook using Jupyter Notebook or Kaggle Notebook.

---

## Generated Outputs

The notebook automatically generates:

- Trained Models
- Confusion Matrices
- Classification Reports
- ROC Curves
- Error Analysis
- Prediction Examples
- Model Comparison Tables

---

## Future Work

Possible future improvements include:

- Vision Transformers (ViT)
- EfficientNetV2
- Explainable AI (Grad-CAM)
- Multi-spectral satellite imagery
- Real-time deployment for environmental monitoring

---

## References

- EuroSAT RGB Dataset
- TensorFlow Documentation
- Keras Documentation
- Scikit-learn Documentation
- MobileNetV2 Paper
- EfficientNet Paper

---

## Author

**Akhil Nair**

MSc Software Engineering

University of Europe for Applied Sciences

Pattern Recognition Project