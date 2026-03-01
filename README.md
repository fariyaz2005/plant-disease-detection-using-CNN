# 🌿 Plant Disease Detection using CNN

This repository is about building an Image Classifier CNN with Python for Plant Disease Prediction.

## 🚀 Project Overview

Plant diseases significantly affect agricultural productivity and crop yield. This project uses Deep Learning and Computer Vision techniques to detect and classify plant diseases from leaf images using a Convolutional Neural Network (CNN).

The system helps in early disease detection, allowing farmers and agricultural experts to take preventive measures and improve crop health management.

---

## 📁 Dataset

The model is trained using the PlantVillage dataset.

🔗 Kaggle Dataset Link:  
https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset

The dataset contains labeled images of healthy and diseased plant leaves across multiple crop types.

---

## 🧠 Model Architecture

- Built using TensorFlow / Keras
- Convolutional Layers for feature extraction
- MaxPooling Layers for dimensionality reduction
- Fully Connected (Dense) Layers for classification
- Softmax activation for multi-class prediction

### Image Preprocessing:
- Image resizing
- Normalization
- Data augmentation (if applied)

---

## 📊 Model Performance

- Trained on labeled plant leaf images
- Evaluated using training and validation accuracy
- Achieved high classification accuracy on validation data

(Training and validation accuracy/loss graphs are available in the notebook.)

---

## 📌 Trained Model

You can download the trained model from the link below:

🔗 Trained Model Link:  
https://drive.google.com/file/d/1rKh-IElSdHTqax7XdfSdZTn-r8T_qWPf/view?usp=drive_link

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- OpenCV (optional)

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/fariyaz2005/plant-disease-detection-using-CNN.git
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from Kaggle and place it in the project directory.

4. Run the training notebook or prediction script.

---

## 🎯 Future Improvements

- Deploy as a web application using Flask or Streamlit
- Convert model to mobile-friendly format (TensorFlow Lite)
- Improve accuracy using Transfer Learning (ResNet, VGG, EfficientNet)

---

## 👨‍💻 Author

**Md Fariyaz Rahaman**  
GitHub: https://github.com/fariyaz2005/
