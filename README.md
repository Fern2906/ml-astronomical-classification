# Photometric Classification of Astronomical Objects

This project implements machine learning models to classify astronomical objects using photometric data from the ELAsTiCC dataset.

## Models Used

- Support Vector Machine (RBF kernel)
- Random Forest

## Dataset

Subset of ELAsTiCC dataset:
- 164,152 samples
- 4 classes:
  - Cepheid
  - RR Lyrae
  - Delta Scuti
  - Eclipsing Binary

## Key Results

| Model | Accuracy | Macro F1 |
|------|--------|---------|
| SVM | 0.62 | 0.37 |
| Random Forest | 0.85 | 0.75 |

## Notes

- SVM was trained using a subsample due to computational limitations
- Random Forest was trained on the full dataset

## Author

Kevin Fernando De Leon Ramirez
