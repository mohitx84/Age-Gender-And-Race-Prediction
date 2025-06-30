# Age-Gender-And-Race-Prediction

# 🧠 Age, Gender & Race Prediction from Facial Images

This project implements a multi-task deep learning model to predict **age**, **gender**, and **race** from facial images. The solution uses **MobileNetV2** as a transfer learning backbone and is trained on the **UTKFace** dataset with high accuracy.

---

## 📌 Overview

- **Model**: Multi-output CNN (based on MobileNetV2)
- **Dataset**: [UTKFace](https://susanqq.github.io/UTKFace/)
- **Outputs**:
  - Age → Regression (MAE)
  - Gender → Binary Classification (Accuracy)
  - Race → Multi-class Classification (Accuracy)

---

## 🚀 Features

- ✅ Multi-task learning: Age, gender, and race prediction in a single model
- 🧠 Transfer learning with **MobileNetV2**
- ⚖️ Custom loss weighting for balanced training
- 🛠️ Early stopping, learning rate scheduling, and model checkpointing
- 🔍 Real-time prediction demo on test images

---

## 📈 Results

| Task     | Metric         | Result     |
|----------|----------------|------------|
| Gender   | Accuracy        | **~95%**    |
| Race     | Accuracy        | **~83%**    |
| Age      | MAE (years)     | **~4.7**    |

---

## 🧰 Tech Stack

- Python, TensorFlow/Keras
- MobileNetV2 (pretrained on ImageNet)
- OpenCV, NumPy, Matplotlib
- Google Colab / GPU or TPU acceleration

