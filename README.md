# 🧠 Liver Tumor Segmentation using MONAI & PyTorch

Deep Learning-based medical image segmentation project for detecting liver tumors from CT scan data.

---

## 📌 Overview

This project implements a **3D medical image segmentation pipeline** using **MONAI and PyTorch** to segment liver regions and tumors from volumetric CT scans.

The model is based on a **3D U-Net architecture**, widely used in medical imaging tasks for accurate pixel-level prediction.

---

## 🚀 Key Features

* 3D U-Net based segmentation model
* Built using **MONAI (Medical Open Network for AI)**
* Medical image preprocessing & transformations
* Visualization of CT scan slices and segmentation masks
* Performance evaluation using **Dice Score**

---

## 🧠 Tech Stack

* Python
* PyTorch
* MONAI
* NumPy
* Matplotlib

---

## ⚙️ Model Architecture

* 3D U-Net (Encoder–Decoder structure)
* Multi-level feature extraction
* Skip connections for better localization

---

## 🧪 Data Processing

* Data loading using MONAI pipelines
* Preprocessing and normalization
* Augmentation for improved generalization

---

## 👁️ Visualization

Example function used to visualize CT scan slices and segmentation output:

```python
def show_patient(data, SLICE_NUMBER=1, train=True, test=False):
    # Visualizes CT slice and segmentation mask
    pass
```

Helps in verifying preprocessing and model predictions visually.

---

## ▶️ Training

Model is trained using MONAI’s training pipeline:

* Loss Function: Dice Loss
* Optimizer: Adam
* Input: 3D CT volumes
* Output: Segmentation masks

Run training:

```bash
python train.py
```

---

## 📊 Evaluation Metrics

* Dice Coefficient
* Intersection over Union (IoU)

---

## 📈 Results

* Achieved strong segmentation performance on validation data
* Accurate detection of liver regions and tumor boundaries

---

## 📁 Project Structure

```
├── train.py
├── preprocess.py
├── testing.ipynb
├── dataset/
├── images/
```

---

## ⚠️ Note

This project is implemented for learning and experimentation using publicly available resources and medical imaging frameworks.

---

## 📬 Contact

Shivam Shaurya
📧 [shivamshaurya774@gmail.com](mailto:shivamshaurya774@gmail.com)

---
