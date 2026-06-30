# Disaster Tweet Classification using Support Vector Machines

## Overview

This project explores Natural Language Processing (NLP) techniques for automatically identifying whether a tweet describes a real disaster event.

The workflow includes text preprocessing, feature extraction using TF-IDF, dimensionality reduction with PCA, and a comparison of several machine learning classifiers.

---

## Dataset

The project uses the **Natural Language Processing with Disaster Tweets** dataset from Kaggle.

Each sample contains:

- Tweet text
- Keyword
- Location
- Binary target

Target:

- **0** → Not a real disaster
- **1** → Real disaster

Dataset source:

https://www.kaggle.com/competitions/nlp-getting-started

---

## Project Workflow

### Data Preparation

- Dataset exploration
- Train/Test split using stratified sampling
- Missing value handling
- Feature merging
- Text preprocessing
- Noise removal

### Feature Extraction

Text documents are converted into numerical feature vectors using:

- TF-IDF Vectorization

### Machine Learning Models

The following classifiers were implemented:

- Linear Support Vector Machine (LinearSVC)
- Support Vector Machine with RBF Kernel
- Support Vector Machine with RBF Kernel (Gamma = Auto)
- Gaussian Naive Bayes

### Dimensionality Reduction

Principal Component Analysis (PCA) was applied to preserve 95% of the dataset variance before training additional SVM models.

### Model Evaluation

The models were evaluated using multiple classification metrics and compared through visualization.

---

## Machine Learning Techniques

- Natural Language Processing
- Text Preprocessing
- TF-IDF
- Support Vector Machines
- Gaussian Naive Bayes
- Principal Component Analysis (PCA)
- Text Classification

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow
- Google Colab

---

## Evaluation Metrics

Classification performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score

---

## Repository Structure

```
├── Assignment7_SVM_Bayes.ipynb
├── train.csv
├── test.csv
├── sample_submission.csv
├── README.md
```

---

## Key Skills Demonstrated

- Natural Language Processing
- Text Classification
- Feature Engineering
- TF-IDF Vectorization
- Support Vector Machines
- Naive Bayes
- Dimensionality Reduction
- Machine Learning Model Evaluation

---

## Author

Georgia Takatzoglou

M.Sc. Data and Web Science

Physics Graduate | Machine Learning | Data Science
