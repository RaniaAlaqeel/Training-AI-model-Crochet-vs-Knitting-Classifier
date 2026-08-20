# Crochet vs Knitting Classifier 🧶

A Deep Learning Image Classification project built using **Google Teachable Machine** and evaluated with **TensorFlow / Keras** in Python (Google Colab).

The goal of this project is to classify and distinguish between two visually similar textile crafts: **Crochet (كروشيه)** and **Knitting (تريكو)**.

---

## 📌 Project Overview
- **Problem Statement:** Differentiating between crochet and knitting patterns can be challenging due to their close textures and yarn structures.
- **Classes:**
  1. `crochet`
  2. `knitting`
- **Tools & Frameworks:**
  - [Google Teachable Machine](https://teachablemachine.withgoogle.com/) for model training and export.
  - **TensorFlow / Keras** (`keras_model.h5`) for inference.
  - **Google Colab** environment for testing and execution.

---

## 📁 Repository Structure
```text
├── keras_model.h5      # Exported Keras model from Teachable Machine
├── labels.txt          # Class labels (crochet, knitting)
├── test.jpeg           # Sample test image used for validation
├── main.py  # Python inference code
└── README.md           # Project documentation
