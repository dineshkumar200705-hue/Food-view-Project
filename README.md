## Overview

**Food Vision** is a Deep Learning project that classifies food images into different categories using **TensorFlow** and **Transfer Learning**. The model is trained on a large-scale food image dataset to recognize various food items with high accuracy.

This project demonstrates the complete workflow of an image classification task, including data preprocessing, model training, evaluation, and prediction.

---

# Features

- Food Image Classification
-  Transfer Learning with EfficientNet
-  Model Evaluation
-  Training & Validation Accuracy Graphs
-  Image Prediction
-  Model Saving & Loading
-  TensorFlow & Keras Implementation

---

#  Dataset

This project uses the **Food101 Dataset**, which contains:

- **101 Food Categories**
- **101,000 Images**
- **750 Training Images per Class**
- **250 Testing Images per Class**

Example classes include:

- Pizza
- Burger
- Sushi
- Ice Cream
- Pasta
- Steak
- Sandwich
- Donuts
- Salad
- Ramen

---

# Tech Stack

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

---

# Workflow

```
Dataset
   │
   ▼
Data Preprocessing
   │
   ▼
Image Augmentation
   │
   ▼
Transfer Learning
(EfficientNet)
   │
   ▼
Model Training
   │
   ▼
Evaluation
   │
   ▼
Prediction
```

---

# Model Architecture

The project uses **Transfer Learning** with:

- EfficientNetB0 (or your chosen model)
- Global Average Pooling
- Dense Layer
- Softmax Output Layer

---

# Performance

The model is evaluated using:

- Training Accuracy
- Validation Accuracy
- Loss Curves
- Prediction Samples
- Confusion Matrix *(optional)*

---

# Sample Predictions

| Input Image | Predicted Class |
|-------------|-----------------|
| 🍕 Pizza | Pizza |
| 🍔 Burger | Burger |
| 🍣 Sushi | Sushi |

> Add screenshots of your predictions in the `images/` folder.

---

# Installation

Clone the repository

```bash
git clone https://github.com/ankurdotio/Youtube-project-food-view.git
```

Move into the project directory

```bash
cd Youtube-project-food-view
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

# Requirements

```text
tensorflow
keras
numpy
pandas
matplotlib
scikit-learn
opencv-python
jupyter
```

---

# Example Prediction

```python
from tensorflow.keras.models import load_model

model = load_model("food_vision_model.h5")

prediction = model.predict(image)

print(prediction)
```

---

# Future Improvements

- Vision Transformer (ViT)
- MobileNetV3
- Streamlit Web App
- FastAPI Deployment
- Docker Support
- TensorFlow Lite Conversion
- Real-Time Webcam Prediction

---

# Applications

- Smart Restaurant Systems
- Diet & Nutrition Apps
- Food Calorie Estimation
- AI Menu Recognition
- Self-Service Ordering Kiosks
- Food Delivery Platforms

---

# Contributing

Contributions are welcome!

1. Fork this repository
2. Create a feature branch
3. Commit your changes
4. Push your branch
5. Open a Pull Request

---

# Author

**Dinesh Kumar**

GitHub: https://github.com/dineshkumar200705-hue

---

# ⭐ Support

If you found this project helpful, please ⭐ star the repository and share it with others.

Happy Coding! 🚀
