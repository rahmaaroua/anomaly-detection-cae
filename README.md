# Anomaly Detection with Convolutional Autoencoder (CAE)

This project is part of the Data Mining module at the Faculty of Sciences of Tunis.  
It uses a Convolutional Autoencoder (CAE) to detect anomalies in images of fish (fresh vs not fresh).

## 📦 Dataset
- **Dataset used:** [Fresh and Not Fresh Fish Dataset on Kaggle](https://www.kaggle.com/datasets/arifagustyawan/fresh-and-not-fresh-fish-dataset)
- Contains two classes:
  - `fresh` (normal)
  - `not fresh` (anomalous)

## 🧠 What we Did
- Preprocessed image data (resizing, normalizing)
- Built and trained a CAE model using Keras
- Calculated reconstruction error to detect anomalies
- Evaluated with metrics (accuracy, precision, recall, F1-score)
- Visualized original vs reconstructed images

## 📁 Files in This Repository
- `anomaly-detection-and-multi-class-classification.ipynb` — the main notebook
- `README.md` — project overview (this file)

## 🚀 Tools Used
- Python
- TensorFlow / Keras
- OpenCV
- Matplotlib

## 👩‍💻 Authors
- Rahma Aroua & Wiem Mehri  — Software Engineering Students at FST, Tunisia
