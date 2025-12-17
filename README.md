# 🇮🇳 Indian Currency Detection & Denomination Recognition

A Deep Learning project that identifies Indian currency notes and detects whether they are **Real or Fake**. This system utilizes Convolutional Neural Networks (CNN) and Image Processing techniques to analyze currency features.

![Project Status](https://img.shields.io/badge/Status-Completed-green)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-orange)

## 📌 Project Overview
Counterfeit currency is a major issue in the financial sector. This project aims to automate the detection process using Computer Vision.
* **Input:** Image of an Indian Currency Note (e.g., ₹100, ₹500, ₹2000).
* **Process:** The image is pre-processed (resized, gray-scaled) and passed through a trained CNN model.
* **Output:** Classification as **"Real"** or **"Fake"**.

## 🛠️ Tech Stack
* **Language:** Python
* **IDE:** Google Colab / Jupyter Notebook
* **Libraries:** TensorFlow/Keras, OpenCV, NumPy, Matplotlib, OS

## 📂 Dataset Structure
**Note:** This project relies on a dataset stored in **Google Drive**. To run this locally or on Colab, you must structure your data as follows:

```text
/My Drive/
  └── Indian_Currency_Dataset/
       ├── train/
       │    ├── Real/
       │    └── Fake/
       ├── test/
       │    ├── Real/
       │    └── Fake/
       └── valid/
