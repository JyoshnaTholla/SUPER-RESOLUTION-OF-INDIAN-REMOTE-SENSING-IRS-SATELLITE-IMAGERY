# 🛰️ SUPER-RESOLUTION OF INDIAN REMOTE SENSING (IRS) SATELLITE IMAGERY

A **comparative evaluation of SRCNN, SRGAN, and ESRGAN** for geospatial image super-resolution, upscaling medium-resolution (5m) to high-resolution (1m) satellite imagery.  

---

## 📌 Project Overview
Satellite imagery plays a critical role in remote sensing applications such as **land monitoring and urban planning**. However, the resolution of these images is often constrained by satellite sensor limitations, resulting in medium-resolution data that lacks the fine details necessary for accurate analysis.  

This study explores the potential of **deep learning-based super-resolution techniques** to enhance the resolution of satellite images, focusing on upscaling 5-meter MR images to 1-meter HR outputs.  

We evaluate three SR models:  
- **SRCNN** – baseline method offering modest resolution improvements.  
- **SRGAN** – generative adversarial framework improving image realism.  
- **ESRGAN** – advanced architecture with residual-in-residual dense blocks, achieving superior results.  

These findings underscore the potential of advanced deep learning techniques to transform medium-resolution satellite imagery into **high-quality data**, providing substantial benefits for real-world remote sensing applications.

---

## 🔎 Notes
- _Due to limited resources, we trained the models for **80 epochs**. For better results, models (especially SRGAN) require training for days/weeks, as claimed in the original research papers._  
- _**Dataset Sources:** The dataset used in this project cannot be shared due to security reasons._  

---

## ✨ Features
- **Model Implementations:** Complete implementations of SRCNN, SRGAN, and ESRGAN.  
- **Evaluation Metrics:** PSNR, SSIM, MSE with visualizations (histograms, error maps, bar charts).  
- **Data Preparation:** Image loading, augmentation, RGB/BGR handling for VGG compatibility.  
- **Training Loops:** Custom learning rate schedules and adversarial training for SRGAN/ESRGAN.  
- **Comparative Analysis:** Performance comparison across datasets.  
- **Visualizations:** Sample outputs, loss curves, and metric distributions.  

---

## 🛠️ Installation

### Clone the repository
```bash
git clone https://github.com/JyoshnaTholla/SUPER-RESOLUTION-OF-INDIAN-REMOTE-SENSING-IRS-SATELLITE-IMAGERY.git
cd SUPER-RESOLUTION-OF-INDIAN-REMOTE-SENSING-IRS-SATELLITE-IMAGERY
