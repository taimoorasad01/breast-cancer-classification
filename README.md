# Breast Cancer Classification — Machine Learning with scikit-learn

## Overview
A machine learning project comparing three classification models for
predicting breast tumor diagnosis (malignant vs benign) using the
Wisconsin Breast Cancer Dataset.

## Results
| Model | Accuracy | Precision | Recall | F1 Score |
|---|---|---|---|---|
| Logistic Regression | 0.9825 | 0.9861 | 0.9861 | 0.9861 |
| Random Forest | 0.9561 | 0.9589 | 0.9722 | 0.9655 |
| SVM | 0.9825 | 0.9861 | 0.9861 | 0.9861 |

## Key Findings
- All models achieved >95% accuracy on unseen data
- Logistic Regression & SVM tied at 98.25% accuracy
- worst concave points & worst radius are top predictors
- High recall is critical in medical diagnosis to minimize false negatives

## Visualizations
| Plot | Description |
|---|---|
| plot1 | Class distribution (count + pie) |
| plot2 | Feature distributions by diagnosis |
| plot3 | Model performance comparison |
| plot4 | Confusion matrices — all 3 models |
| plot5 | ROC curves with AUC scores |
| plot6 | Top 10 feature importance (Random Forest) |

## Tech Stack
- Python 3.13
- scikit-learn, pandas, NumPy, matplotlib, seaborn
- Dataset: Wisconsin Breast Cancer (built into scikit-learn)

## Author
Taimoor Asad — Python & ML Developer
