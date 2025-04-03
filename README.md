# 🌈 Hyperspectral Image Clustering using PCA and k-Means

This project is part of **Machine Learning Lab Project 2** (NTUA, School of Electrical and Computer Engineering, 7th semester)  
and focuses on unsupervised learning techniques applied to **hyperspectral image data**.

---

## 🧠 Objectives

- Apply **Principal Component Analysis (PCA)** to reduce dimensionality of high-dimensional image data
- Use **k-Means clustering** to segment the image into semantically meaningful classes
- Visualize and evaluate the results using pixel-level ground truth annotations

---

## 🖼 Dataset

- **Hyperspectral Image**: `indian_pines_corrected.npy`
- **Ground Truth Labels**: `indian_pines_gt.npy`
- Image shape: (145, 145, 220)
  - 145 × 145 pixels
  - 220 spectral channels per pixel
- 17 classes total (label 0 corresponds to “Undefined”)

---

## 📊 Tasks Performed

1. Load and inspect hyperspectral image and ground truth annotations
2. Visualize selected spectral channels (3rd, 65th, 95th)
3. Reshape data into 2D for PCA processing
4. Apply PCA to reduce spectral channels from 220 to 3
5. Apply k-Means clustering on the reduced data
6. Compare clustering result with ground truth map

---

## 🛠️ Technologies Used

- Python 3
- NumPy
- Matplotlib
- scikit-learn
- Google Colab or Jupyter Notebook

---

## ▶️ How to Run

1. Download the datasets from [this Google Drive link](https://drive.google.com/drive/folders/15hbGoLga9n4K6wxRP6qsLV1P-7Nj-Vht?usp=sharing)
2. Place `indian_pines_corrected.npy` and `indian_pines_gt.npy` in the working directory
3. Run the notebook `Δαλαμπέκης_ML2023_24_labproject2.ipynb`

---

## 📚 Educational Use

This notebook was developed as part of the Machine Learning course at **NTUA ECE** (Academic Year 2023–2024).  
All content is intended for educational purposes only.
