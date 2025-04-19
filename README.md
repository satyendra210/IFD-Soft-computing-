# 🕵️‍♂️ Image Manipulation Detection using Hybrid Feature Extraction and ML Classifiers

## 📸 Overview

In today’s digital era, images play a critical role in communication—be it on social media, news, education, or entertainment platforms. However, with the easy availability of image editing software and AI-based manipulation tools, **image forgeries** have become increasingly sophisticated and harder to detect.

This project presents a **robust framework for detecting image splicing and copy-move forgeries** using a hybrid approach combining handcrafted feature extraction techniques with classical machine learning algorithms.

---

## 🚀 Key Features

- Detects **copy-move** and **splicing** forgeries
- Combines **LBP**, **FFT**, **DFT**, and **FCM** for feature extraction
- Uses **LDA** for dimensionality reduction
- Classifies using **Logistic Regression (LR)**, **K-Nearest Neighbors (KNN)**, and **Support Vector Machines (SVM)**
- Tested on **CASIA v1** and **CASIA v2** datasets
- Evaluated using **Accuracy**, **Precision**, **Recall**, and **F1-score**

---

## 🧪 Experimental Results

| Dataset     | Features Used         | Classifier | Accuracy (%) |
|-------------|------------------------|------------|---------------|
| CASIA v1    | LBP + FFT + FCM        | LR         | 98.36         |
| CASIA v2    | LBP + DFT + FCM        | SVM        | 98.82         |

---

## 🛠️ Tech Stack

- 🧠 Machine Learning: Logistic Regression, KNN, SVM
- 📊 Feature Extraction: LBP, FFT, DFT, FCM
- 📉 Dimensionality Reduction: LDA
- 📚 Dataset: CASIA v1 & CASIA v2
- 🐍 Language: Python 3.10+

