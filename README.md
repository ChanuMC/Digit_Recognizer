
# 🧠 Digit Recognizer using CNN (MNIST)

## 📌 Project Overview

This project implements a **Convolutional Neural Network (CNN)** using **TensorFlow/Keras** to classify handwritten digits from the MNIST dataset.

The model is trained to recognize digits (0–9) from grayscale images of size **28×28 pixels**.

---

## 🚀 Features

* Uses **CNN (Convolutional Neural Network)** for image classification
* Achieves high accuracy on handwritten digit recognition
* Simple and beginner-friendly implementation
* Visualizes predictions using Matplotlib
* Saves trained model for future use

---

## 🛠️ Tech Stack

* Python 🐍
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## 📂 Project Structure

```
├── digit_classifier.py   # Main Python script
├── digit_model.keras     # Saved trained model
└── README.md             # Project documentation
```

---

## 📊 Dataset

This project uses the built-in **MNIST dataset** from Keras:

* 60,000 training images
* 10,000 testing images
* 10 classes (digits 0–9)

---

## 🧪 Model Architecture

The CNN model consists of:

* Conv2D (32 filters, 3x3) + ReLU
* MaxPooling (2x2)
* Conv2D (64 filters, 3x3) + ReLU
* MaxPooling (2x2)
* Flatten Layer
* Dense Layer (64 neurons, ReLU)
* Output Layer (10 neurons, Softmax)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/digit-classifier.git
cd digit-classifier
```

### 2️⃣ Install dependencies

```bash
pip install tensorflow matplotlib numpy
```

---

## ▶️ How to Run

```bash
python digit_classifier.py
```

---

## 📈 Output

* Displays model accuracy on test data
* Shows prediction for a sample image
* Visualizes the digit using Matplotlib

Example:

```
Accuracy: 0.98
Predicted: 7
```

---

## 💾 Model Saving

The trained model is saved as:

```
digit_model.keras
```

You can later load it using:

```python
from tensorflow import keras
model = keras.models.load_model("digit_model.keras")
```
---

## 📷 Sample Prediction

The model predicts a digit and displays the corresponding image.

---

## 🔮 Future Improvements

* Increase accuracy with deeper CNN architecture
* Add Dropout to reduce overfitting
* Use data augmentation
* Build a web app using Flask/Streamlit
* Deploy model online

---

---

## 🙌 Acknowledgements

* MNIST Dataset
* TensorFlow & Keras documentation

---
