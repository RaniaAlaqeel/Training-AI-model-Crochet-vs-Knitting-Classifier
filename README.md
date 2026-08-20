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

### Model Testing Output
![model testing output](https://github.com/RaniaAlaqeel/Training-AI-model-Crochet-vs-Knitting-Classifier/blob/main/result.jpeg)
---

## 📁 Repository Structure
```text
├── keras_model.h5      # Exported Keras model from Teachable Machine
├── labels.txt          # Class labels (crochet, knitting)
├── test.jpeg           # Sample test image used for validation
├── main.py             # Python inference code
├── result.jpeg         # the result of the test
└── README.md           # Project documentation
