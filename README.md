# 🌌 Asteroid Spectral Analysis using Neural Networks

This project implements a **non-web based machine learning framework** to analyze asteroid reflectance spectra using both **supervised classification** and **unsupervised learning**.

---

## 🚀 Overview

- Uses deep learning to classify asteroid spectra  
- Explores hidden structure using latent space learning  
- Combines **SPEC-ANN (CNN)** and **AEC-Net (Autoencoder)**  

---

## 🧠 Models

- **SPEC-ANN** → 1D CNN for spectral classification  
- **AEC-Net** → Autoencoder for latent representation  
- **HDBSCAN** → Clustering on latent space  

---

## 📊 Dataset

- **SMASS II asteroid dataset**  
- Visible spectrum (0.44–0.92 µm)  
- 4 classes: C, S, X, Other  

---

## ⚙️ Workflow

1. Data preprocessing  
2. Train SPEC-ANN  
3. Train AEC-Net  
4. Extract latent features  
5. Clustering & analysis  

---

## 📈 Results

- ~97% classification accuracy  
- Spectral classes show overlap (continuous distribution)  
- Identified dense, high-confidence subgroups  

---

## 🛠️ Tech Stack

- Python, TensorFlow/Keras  
- NumPy, Pandas, Scikit-learn  
- Matplotlib, HDBSCAN  

---

## 👨‍💻 Author

Ravi Saini  

---

## ⭐ Note

This project is part of an academic research work on asteroid spectral taxonomy.
