# MVTec AD Manufacturing Defect Detection

A hands-on computer vision project for real-time defect detection in manufacturing using the [MVTec Anomaly Detection (AD) Dataset](https://www.mvtec.com/company/research/datasets/mvtec-ad/).  
This project demonstrates how to train and evaluate an autoencoder-based anomaly detector to spot subtle defects in bottles and leather products—simulating industrial quality control.

---

## Features

- **Data Exploration:** View and analyze images from the MVTec AD dataset.
- **Autoencoder Training:** Learn “normal” product patterns using only non-defective images.
- **Defect Detection:** Automatically flag defective products based on reconstruction error.
- **Visualizations:** Show original images, reconstructions, and error maps for clear insight.
- **Jupyter Notebook:** All code, results, and step-by-step explanations are included.

---

## Dataset

- **Source:** [MVTec AD Dataset](https://www.mvtec.com/company/research/datasets/mvtec-ad/)
- **Categories used:** `bottle` and `leather`
- **Data split:** 
  - Train: Only “good” images (unsupervised anomaly detection)
  - Test: “Good” + multiple real-world defect types

---



