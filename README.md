![nexus_software_pvt_ltd_cover](https://github.com/Shreyaprasad21/Project-3-AI-ML-Series-Multiple-Disease-Detection-system/assets/142075353/1e542e0d-2db0-41cb-99b7-d8f61c9da7cb)
# Project 1 - Breast Cancer Prediction

This project was completed as part of an internship program at Nexus Info. The internship was conducted remotely. The objective of this project is to analyze and predict breast cancer using machine learning techniques. The dataset and associated files are used to build and evaluate models that can accurately diagnose breast cancer based on various medical parameters.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Results](#results)

## Introduction

Breast cancer is one of the most common cancers among women worldwide. Early detection and diagnosis are crucial for improving survival rates and treatment outcomes. This project leverages machine learning techniques to develop a model that can predict breast cancer based on various medical parameters.

## Dataset

The dataset includes the following columns:

- `ID`: Unique identifier for each patient.
- `Diagnosis`: The diagnosis of breast tissues (M = malignant, B = benign).
- `Radius`: Mean of distances from the center to points on the perimeter.
- `Texture`: Standard deviation of gray-scale values.
- `Perimeter`: Mean size of the core tumor.
- `Area`: Mean area of the tumor.
- `Smoothness`: Mean of local variation in radius lengths.
- `Compactness`: Mean of perimeter^2 / area - 1.0.
- `Concavity`: Mean of severity of concave portions of the contour.
- `Concave points`: Mean of number of concave portions of the contour.
- `Symmetry`: Mean of symmetry.
- `Fractal dimension`: Mean of "coastline approximation" - 1.

## Requirements

To run this project, you will need the following software and libraries:

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install the required libraries using the following command:

```bash
pip install pandas
pip install numpy
pip install scikit-learn
pip install matplotlib
pip install seaborn
```

## Installation
1. Clone the repository:
```
git clone https://github.com/himankgupta1/breast-cancer-prediction.git
```
2. Navigate to the project directory:
```
cd breast-cancer-prediction
```
3. Install the required libraries

## Results
The results of the model evaluation are documented in the Jupyter Notebook. The model's performance is assessed using various metrics such as accuracy, precision, recall, and F1-score. Additionally, visualizations are provided to help understand the model's behavior and predictions.
