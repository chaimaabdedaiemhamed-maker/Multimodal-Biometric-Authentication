# Multimodal-Biometric-Authentication
Retina and Iris biometric authentication using Transfer Learning
# Multimodal Biometric Authentication (Retina & Iris)

## Overview

This project presents a **multimodal biometric authentication system** based on **retina and iris images**.
It leverages **transfer learning** and a **feature-level fusion strategy** to improve authentication accuracy and robustness.

---

## Objectives

* Design biometric authentication systems using **retina** and **iris** modalities
* Apply **transfer learning** for effective feature extraction
* Propose a **multimodal fusion strategy** combining both modalities
* Demonstrate that **multimodal fusion outperforms unimodal approaches**

---

## Datasets

* **DRIVE** dataset for retinal images
* **UBIRIS.v2** dataset for iris images

These public datasets are commonly used in biometric research and include variations in illumination and image quality.

---

## Methodology

* **Feature extraction** using pre-trained CNN models with transfer learning
* Independent processing of retina and iris images
* **Feature-level fusion** by concatenating deep representations from both modalities
* Final authentication decision using fully connected layers

---

## Results (Summary)

The proposed **multimodal feature-level fusion method** combining retinal and iris biometric traits achieves **significantly higher performance** than all unimodal models evaluated in this work:

* **Accuracy:** **95%**
* **Precision:** **97.5%**
* **Recall:** **95%**
* **F1-score:** **95%**

📌 These results clearly demonstrate that the fusion of retina and iris modalities **outperforms retina-only and iris-only approaches**, leading to a more accurate and robust biometric authentication system.

---

## Evaluation Metrics

Accuracy · Precision · Recall · F1-score · Confusion Matrix · Training and Validation Curves

---

## Repository Structure

```
📦 Multimodal-Biometric-Authentication
 ┣ 📂 code
 ┃ ┣ retina_model.ipynb
 ┃ ┣ iris_model.ipynb
 ┃ ┗ fusion_model.ipynb
 ┗ 📄 README.md
```

---

## Tools & Technologies

Python · TensorFlow/Keras · Convolutional Neural Networks (CNN) · Transfer Learning · Multimodal Biometric Fusion

---

## Author

**Chaima Abdedaiem**


📄 *The full thesis document is not publicly shared and is available upon academic request.*
