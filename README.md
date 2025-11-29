# Lung Cancer Classification with TensorFlow (CNN)

## Project Overview
This project implements a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify lung tissue images into three categories:

- **lung_aca** – Adenocarcinoma  
- **lung_n** – Normal lung tissue  
- **lung_scc** – Squamous cell carcinoma  

The goal is to build and train a CNN capable of accurately classifying lung images. The model uses TensorFlow’s deep learning framework and achieves an **average accuracy of around 90%** when tested on unseen data.

---

## Features
- End-to-end TensorFlow workflow  
- Image preprocessing (resize to 128×128, normalize pixel values)  
- CNN architecture with:
  - Convolution layers  
  - ReLU activation  
  - MaxPooling layers  
  - Flatten and Dense layers  
- Train/Test split (**98.6% training, 1.4% testing**)  
- Model evaluation with accuracy and loss plots  
- Predictions on test images  

---

## Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- OpenCV  
- Matplotlib  
- Jupyter Notebook  

---

## Requirements
You will need:
- Python 3.x  
- TensorFlow  
- NumPy  
- Matplotlib  
- OpenCV  
- scikit-learn  

Install everything with:
```bash
pip install tensorflow numpy matplotlib opencv-python scikit-learn
```

---

## Acknowledgments
All image credit belongs to the original **Kaggle contributors**.  This project is based on the concepts taught in the **W3Schools tutorial**.
