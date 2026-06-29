# Asteroid Spectral Taxonomy Classification using Machine Learning and Deep Learning

## Overview

This project develops an end-to-end machine learning pipeline for asteroid taxonomy classification using visible reflectance spectra from the SMASS-II (Small Main-Belt Asteroid Spectroscopic Survey II) dataset. The pipeline covers every stage of the workflow, from raw spectral data acquisition and preprocessing to traditional machine learning, deep learning, hyperparameter optimization, and unsupervised representation learning.

The objective is to automatically classify asteroids into their major taxonomic groups based solely on their spectral signatures, reducing the need for manual spectral analysis while providing a scalable framework for asteroid characterization.

---

## Features

- Automated downloading and verification of SMASS-II spectral dataset
- Parsing and preprocessing of raw asteroid spectra
- Spectral normalization and data enrichment
- Interactive spectral visualization
- Binary asteroid classification using Support Vector Machines (SVM)
- Multi-class taxonomy prediction
- Hyperparameter optimization using Grid Search and Halving Grid Search
- Deep Neural Network classifier
- 1D Convolutional Neural Network (CNN) for spectral classification
- Bayesian hyperparameter optimization
- Autoencoder-based spectral feature learning
- Latent space visualization
- Unsupervised clustering using UMAP and HDBSCAN

---

## Project Workflow

```
SMASS-II Dataset
        │
        ▼
Data Download & Verification
        │
        ▼
Data Parsing
        │
        ▼
Data Enrichment
        │
        ▼
Spectral Visualization
        │
        ▼
Machine Learning Models
   ├── Binary SVM
   ├── Multi-class SVM
   ├── Grid Search
   └── Halving Grid Search
        │
        ▼
Deep Learning Models
   ├── Dense Neural Network
   ├── 1D CNN
   └── Bayesian Optimization
        │
        ▼
Representation Learning
   ├── Autoencoder
   ├── Latent Space
   ├── UMAP
   └── HDBSCAN Clustering
```

---

## Repository Structure

```
01_data_fetching.ipynb
02_data_parsing.ipynb
03_data_enrichment.ipynb
04_spectra_viewer.ipynb
05_ml_svm_binary.ipynb
06_ml_svm_grid_search.ipynb
07_ml_svm_halving_grid_search.ipynb
08_ml_svm_multiclass.ipynb
09_ml_svm_multiclass_halving_grid.ipynb
10_dl_dense_multiclass.ipynb
11_dl_conv1d_multiclass.ipynb
12_dl_hyperparameter_search.ipynb
13_dl_bayesian_optimization.ipynb
14_autoencoder_reconstruction.ipynb
15_autoencoder_latent_space.ipynb
16_autoencoder_clustering.ipynb
17_autoencoder_clustering_hdbscan.ipynb
```

---

## Machine Learning Models

### Traditional Machine Learning

- Support Vector Machine (Binary Classification)
- Support Vector Machine (Multi-class Classification)
- GridSearchCV
- HalvingGridSearchCV

### Deep Learning

- Dense Neural Network
- 1D Convolutional Neural Network (Conv1D)
- Bayesian Hyperparameter Optimization

### Unsupervised Learning

- Autoencoder
- UMAP Dimensionality Reduction
- HDBSCAN Clustering

---

## Dataset

**Source**

SMASS-II (Small Main-Belt Asteroid Spectroscopic Survey II)

The dataset contains visible reflectance spectra of asteroids measured across multiple wavelengths. Each spectrum is normalized before being used for machine learning.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- UMAP
- HDBSCAN
- Jupyter Notebook

---

## Learning Outcomes

This project demonstrates:

- Scientific data preprocessing
- Spectral feature engineering
- Classical machine learning
- Deep learning for 1D spectral signals
- Hyperparameter optimization
- Representation learning
- Dimensionality reduction
- Unsupervised clustering
- Scientific data visualization
