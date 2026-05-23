

# 👕 Breast Cancer Classification using TensorFlow

This project demonstrates the complete workflow of a binary classification problem in Machine Learning and Deep Learning.

---

# 🚀 Project Overview

This project demonstrates:

- Data loading and preprocessing
- Feature scaling
- Exploratory data understanding
- Logistic Regression baseline model
- Artificial Neural Network (ANN) implementation
- Model training and evaluation
- Confusion matrix analysis
- Prediction comparison

The model is trained on the Breast Cancer Wisconsin Dataset.

---

# 📂 Dataset

Dataset Used: Breast Cancer Wisconsin

The dataset contains features computed from digitized images of breast mass cell nuclei, such as:

Radius
Texture
Perimeter
Area
Smoothness
Compactness
Symmetry
Fractal Dimension

| Label | Meaning   |
| ----- | --------- |
| 0     | Malignant |
| 1     | Benign    |

---

# 🧠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- PIL (Python Imaging Library)
- Streamlit
- Ngrok
- Google Colab

---

# 🏗️ CNN Architecture

The Convolutional Neural Network includes:

- Convolution Layers
- MaxPooling Layers
- Flatten Layer
- Dense Fully Connected Layers
- Softmax Output Layer

The model is trained using:

- Adam Optimizer
- Sparse Categorical Crossentropy Loss
- Accuracy Evaluation Metric

---

# 📊 Features

✅ CNN-based image classification  
✅ Real-time image prediction  
✅ Streamlit web application  
✅ TensorFlow/Keras model saving  
✅ Public deployment support using Ngrok  
✅ Interactive prediction interface  

---

# 📁 Project Structure
```bash
├── cnn_model.keras
├── Image_Classification_CNN.ipynb
└── README.md
```

---


# 🌐 Streamlit Deployment using Google Colab

This project also supports deployment directly from Google Colab using:

- Streamlit
- Pyngrok

Deployment Steps:

1. Train and save the model
2. Run deployment section code at end of file
3. Start Streamlit server
4. Create public URL using Ngrok

---

# 💾 Save Trained Model

```python
model.save("cnn_model.keras")
```

---

# 📥 Download Trained Model

```python
from google.colab import files

files.download("cnn_model.keras")
```

---

# 📸 Application Preview

The web application allows users to:

- Upload clothing images
- Predict clothing category
- View prediction confidence scores
- Display class probabilities

---


# 🎯 Learning Outcomes

Through this project, you can learn:

- CNN fundamentals
- TensorFlow/Keras workflow
- Image preprocessing
- Model training and evaluation
- Streamlit deployment
- Real-time AI application deployment

---

