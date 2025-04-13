---
layout: page
title: Datasets
permalink: /datasets/
---

## 📦 Supported Datasets

CephalometriX currently supports the following datasets for cephalometric analysis and model training:

---

### 'Aariz Dataset

**Description:**  
The AarizDataset is a locally curated dataset collected from private orthodontic clinics. It is designed for deep learning and traditional landmark detection approaches.

**Details:**
- 📊 **Number of Cephalograms:** 1,000
- 📍 **Number of Landmarks per Image:** 29
- 🗂️ **Annotations:** JSON and CSV formats
- 🔒 **Access:** Requires request & agreement

📄 [GitHub](https://github.com/manwaarkhd/aariz-cephalometric-dataset)  
📘 [Research Paper](https://arxiv.org/abs/2302.07797)

---

### ISBI Dataset

**Description:**  
The ISBI 2014 challenge dataset is one of the earliest standardized datasets for benchmarking cephalometric landmark detection. It contains both training and testing splits commonly used for evaluating deep learning methods.

**Details:**
- 📊 **Number of Cephalograms:** 400 (Training: 150, Test: 250)
- 📍 **Number of Landmarks:** 19

🌐 [ISBI Challenge](http://www-o.ntust.edu.tw/~cweiwang/celph/)

---

### PKU Dataset

**Description:**  
Released by Peking University, this dataset is often used for cross-dataset generalization studies. It includes annotations with 20 landmarks per image.

**Details:**
- 📊 **Number of Cephalograms:** 102
- 📍 **Number of Landmarks:** 20
- 🔓 **Access:** Public

📥 [Dataset](https://figshare.com/articles/dataset/dental-cepha-dataset_zip/13265471?file=48632311)  

---

## 🧪 Coming Soon

More datasets will be added with pre-built loaders and evaluation pipelines. Stay tuned!
