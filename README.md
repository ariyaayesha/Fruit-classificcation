# 🍎🥦 Fruit & Vegetable Image Classification using CNN

This project is a **deep learning–based image classification system** that identifies **36 different types of fruits and vegetables** from images.  
It uses a **Convolutional Neural Network (CNN)** built with **TensorFlow/Keras** and is deployed as a **Streamlit web application** for real-time predictions.

The system is designed for **retail automation, agriculture, smart farming, food quality control, and inventory management**.

---

## 📂 Project Structure

<img width="335" height="326" alt="image" src="https://github.com/user-attachments/assets/895fd9be-9367-4e57-9271-5e29229b927f" />


---

## ✨ Features

- **Multi-Class Classification** – Identifies 36 fruits and vegetables
- **High Accuracy** – Achieves approximately 92% accuracy
- **CNN Architecture** – Uses convolution, pooling, and dense layers
- **Data Augmentation** – Rotation, zoom, and flipping
- **Real-Time Prediction** – Upload image and get instant result
- **Simple UI** – Easy-to-use Streamlit interface

---

## 🛠️ Tech Stack

- **Programming Language**: Python  
- **Deep Learning Framework**: TensorFlow, Keras  
- **Image Processing**: PIL, OpenCV  
- **Web Framework**: Streamlit  

---

## 🧠 Model Architecture

- Input Size: **100 × 100 RGB images**
- Convolutional Layers + Max Pooling
- Fully Connected Dense Layers
- Activation Functions:
  - ReLU (hidden layers)
  - Softmax (output layer)
- Optimizer: Adam
- Loss Function: Categorical Cross-Entropy
- Epochs: 25

---

## 🚀 Getting Started

### 1️⃣Install Dependencies
pip install -r requirements.txt

### 2️⃣Train the Model
python train_model.py

### 3️⃣ Run the Streamlit App
streamlit run app.py

## 📸 Screenshots

Steamlit app:
<img width="848" height="458" alt="image" src="https://github.com/user-attachments/assets/9025cb28-0c62-4348-a546-9c005e354587" />

Table: Performance Evaluation of CNN Model for Fruit Classification

<img width="542" height="126" alt="image" src="https://github.com/user-attachments/assets/a5e9d9bb-ae96-4919-9295-5085f2aab47a" />
data:
<img width="305" height="319" alt="image" src="https://github.com/user-attachments/assets/c2bf5f8a-497f-4364-a56d-122898bb0a98" />

accuricy and loss:
<img width="335" height="326" alt="image" src="https://github.com/user-attachments/assets/895fd9be-9367-4e57-9271-5e29229b927f" />


