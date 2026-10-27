# PlantVillage Disease Classification with CNN & MobileNetV2

This repository contains a Deep Learning workflow using TensorFlow/Keras to classify plant leaf diseases from the PlantVillage dataset. It covers a baseline scratch Convolutional Neural Network (CNN) as well as an optimized Transfer Learning model using MobileNetV2, ending with TensorFlow Lite conversion for edge deployment.

---

## Key Features
* **Baseline Architecture:** Custom 3-block CNN built from scratch.
* **Transfer Learning:** Pre-trained MobileNetV2 feature extractor with custom classification head.
* **Optimization & Data Pipeline:** On-the-fly augmentation, rescaling, early stopping, and prefetching.
* **Evaluation:** Categorical classification reports and Seaborn confusion matrices.
* **Export Formats:** Native `.keras` and lightweight `.tflite` models.

---

##  Dataset links
https://www.kaggle.com/datasets/emmarex/plantdisease
