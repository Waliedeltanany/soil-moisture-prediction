# Soil Moisture Prediction Using Deep Learning

## Overview

This project focuses on soil moisture prediction using Deep Learning techniques and remote sensing data. The system applies Convolutional Neural Networks (CNNs) to analyze geospatial and environmental features in order to estimate soil moisture levels with high accuracy.

The notebook includes the complete machine learning workflow starting from data preprocessing and feature preparation to model training, evaluation, and performance visualization.

---

## Project Objectives

- Predict soil moisture values using Deep Learning models.
- Process and analyze remote sensing and geospatial datasets.
- Improve prediction accuracy compared to baseline approaches.
- Visualize model performance and training behavior.
- Support environmental monitoring and agricultural analysis.

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Deep Learning Approach

The project uses Convolutional Neural Networks (CNNs) for spatial feature extraction and soil moisture estimation.

### Workflow

1. Data loading and preprocessing.
2. Feature normalization and preparation.
3. Dataset splitting for training and testing.
4. CNN model construction.
5. Model training and validation.
6. Performance evaluation using statistical metrics.
7. Visualization of prediction results and loss curves.

---

## Model Evaluation Metrics

The model performance is evaluated using several metrics including:

- Pearson Correlation Coefficient (r)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

These metrics help measure prediction accuracy and model reliability.

---

## Results

### Model Performance

| Metric | CNN Model | Baseline | Improvement |
|---|---|---|---|
| Pearson Correlation (r) | 0.87 | 0.79 | +0.08 |

### Training Analysis

- The CNN model achieved strong prediction accuracy during testing.
- Training and validation loss curves showed stable convergence.
- Early stopping techniques helped reduce overfitting.
- The model demonstrated good generalization on unseen data.
- Spatial feature extraction improved soil moisture estimation quality.

### Key Findings

- Deep Learning improved prediction performance compared to traditional approaches.
- CNN architecture successfully captured spatial relationships in the dataset.
- Remote sensing features contributed significantly to prediction accuracy.

---

## Project Structure

```bash
soil-moisture-prediction/
│
├── soil-moisture-project.ipynb
├── README.md
└── dataset/
```

### How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/soil-moisture-prediction.git
```
### Open the Notebook

```bash
jupyter notebook soil-moisture-project.ipynb
```
### Install Required Libraries
```bash
pip install tensorflow pandas numpy matplotlib scikit-learn
```
### Author
## Waleed Eltanany

### License
## This project is intended for educational and research purposes

