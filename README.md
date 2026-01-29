# Image Classification Using CNN (Fashion-MNIST)

## 📌 Overview
This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify grayscale clothing images from the Fashion-MNIST dataset.  
It demonstrates the complete deep learning workflow including preprocessing, model building, training, evaluation, and prediction visualization.

---

## 🧾 Dataset
- Dataset: Fashion-MNIST
- Images: 28 × 28 grayscale
- Classes: 10 clothing categories
- Total images: 70,000 (60k train, 10k test)
- Source: TensorFlow/Keras built-in dataset

### Classes
| Label | Class |
|------|--------|
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |

---

## 🧠 Model Architecture
Input (28x28x1)
→ Conv2D(32, 3x3) + ReLU
→ MaxPooling2D
→ Conv2D(64, 3x3) + ReLU
→ MaxPooling2D
→ Flatten
→ Dense(128) + ReLU
→ Dense(10) + Softmax

---

## ⚙️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook

---
📈 Results
---

Training Accuracy: ~90–92%

Test Accuracy: ~88–91%

CNN significantly outperforms simple Dense models

(Exact results depend on epochs and hyperparameters)

---
🔮 Future Improvements
---

Add data augmentation

Try BatchNormalization

Tune hyperparameters

Use deeper CNN

Deploy using Flask / Streamlit

Convert to mobile using TensorFlow Lite

---
👨‍💻 Author
---

Rudresh
Student | Machine Learning Enthusiast
