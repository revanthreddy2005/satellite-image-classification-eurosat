# Deep Learning for Satellite Image Classification (EuroSAT)

This project uses transfer learning (MobileNetV2) to classify satellite images into 10 land-use categories such as Forest, River, Residential, and Agricultural areas using the EuroSAT dataset.

---

## Key Features
- Transfer learning using MobileNetV2
- Achieved ~90% validation accuracy
- Prediction with confidence scores
- Top-3 class predictions
- Confusion matrix for evaluation
- Visualization of accuracy and loss

---

## Model Architecture
The model is based on MobileNetV2 pretrained on ImageNet, followed by a custom classification head consisting of:
- Global Average Pooling
- Dense layer (ReLU activation)
- Dropout for regularization
- Final Softmax layer for classification

---
  
## Results

### Accuracy & Loss
![Accuracy](accuracy.png)
![Loss](loss.png)

---

### Confusion Matrix
![Confusion Matrix](confusion_matrix.png)

---

### Sample Prediction
![Prediction](prediction.png)

---

### Top-3 Predictions
![Top 3 Predictions](top3.png)

---

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn

---

## Dataset
EuroSAT Dataset – Satellite imagery dataset for land-use and land-cover classification.

---

## Project Highlights
- Implemented deep learning model for satellite image classification
- Applied transfer learning using MobileNetV2
- Achieved strong performance with minimal training time
- Demonstrated real-world application in remote sensing and geospatial analysis

---

## Author
- Revanth Reddy Bommala
- saireddybommala2005@gmail.com
