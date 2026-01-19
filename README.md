🍎🥦 Fruit & Vegetable Image Classification using CNN

This project is a deep learning–based image classification system that can accurately identify 36 different types of fruits and vegetables from images.
It uses a Convolutional Neural Network (CNN) built with TensorFlow/Keras and is deployed as a Streamlit web application for real-time predictions.

The system has practical applications in retail automation, agriculture, smart farming, food quality control, and inventory management.

📂 Project Structure
.
├── dataset/
│   ├── train/                  # Training images (36 classes)
│   ├── validation/             # Validation images
│   └── test/                   # Test images
├── model/
│   └── fruit_veg_cnn_model.h5  # Trained CNN model
├── app.py                      # Streamlit web application
├── train_model.py              # Model training script
├── requirements.txt            # Project dependencies
├── README.md                   # Project documentation

✨ Features

36-Class Classification – Identifies a wide variety of fruits and vegetables.

High Accuracy – Achieves approximately 92% accuracy on test data.

CNN-based Model – Built using TensorFlow and Keras.

Data Augmentation – Improves generalization and reduces overfitting.

Real-Time Prediction – Upload an image and get instant results.

User-Friendly UI – Deployed with Streamlit for easy interaction.

🛠️ Tech Stack

Programming Language: Python

Deep Learning Framework: TensorFlow, Keras

Image Processing: OpenCV, PIL

Web App: Streamlit

Model Type: Convolutional Neural Network (CNN)

🧠 Model Details

Input Image Size: 100 × 100 pixels

Architecture:

Convolutional layers

Max-pooling layers

Fully connected (Dense) layers

Activation Functions:

ReLU (hidden layers)

Softmax (output layer)

Optimizer: Adam

Loss Function: Categorical Cross-Entropy

Epochs: 25

Accuracy: ~92%


Get Ready
1. Install dependencies
pip install -r requirements.txt

2. Run the Streamlit app
streamlit run app.py

5. Open in browser

Streamlit will automatically open your browser.

📸 Screenshots


Example:

App Screenshot

<img width="795" height="449" alt="image" src="https://github.com/user-attachments/assets/cd8a4b6b-5aba-4930-be16-47ed7159aba5" />

Prediction Result
Table: Performance Evaluation of CNN Model for Fruit Classification
Metric	Value (%)
Accuracy	92.00
Precision	91.50
Recall	92.30
F1-Score	91.80
Training Time	~45 sec/epoch
Total Epochs	25



📜 License

This project is developed for academic and educational purposes.
You are free to use and modify it with proper credit.
