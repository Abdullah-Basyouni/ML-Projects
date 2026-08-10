# 🤖 Machine Learning Projects 🚀

---

## 👋 About This Repository

Welcome to my **Machine Learning Projects** repository! 🚀

This repository is my growing **Machine Learning portfolio**, where I document my journey of learning and building practical ML projects.

Each project focuses on solving a real-world problem using data, from **data cleaning and preprocessing** to **feature engineering, model building, evaluation, and visualization**.

> 💡 My goal is to continuously improve my Machine Learning skills by building projects, experimenting with different approaches, and learning from every result.

---

## 🧠 What You'll Find Here

Throughout this repository, you'll find projects covering:

* 🧹 **Data Cleaning & Preprocessing**
* 🔍 **Exploratory Data Analysis (EDA)**
* ⚙️ **Feature Engineering**
* 📊 **Data Visualization**
* 🤖 **Machine Learning Models**
* 🧠 **Neural Networks & Deep Learning**
* 📈 **Model Evaluation & Comparison**
* 🎯 **Hyperparameter Tuning**
* 📉 **Error & Performance Analysis**

---

# 🚀 Projects

## ❤️ 1. Heart Disease Prediction

A Machine Learning project focused on predicting the presence of heart disease using patient medical data.

### 🔧 Techniques & Models

* Logistic Regression
* Random Forest
* Data Preprocessing
* Outlier Handling
* Model Evaluation
* Performance Comparison

### 📊 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 🟢 81%   |
| Random Forest       | 🟢 98%   |

### 📂 Dataset

[Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

📁 Project Folder:

`HeartDiseaseProject`

---

## 🚀 2. Spaceship Titanic

A Neural Network classification project based on the **Spaceship Titanic** Kaggle competition.

The goal is to predict whether a passenger was **Transported to another dimension** based on passenger and travel information.

### 🔧 Techniques & Concepts

* Data Cleaning
* Missing Values Handling
* Feature Engineering
* Categorical Encoding
* Outlier Analysis
* Log Transformation
* Robust Scaling
* Neural Networks
* Adam Optimizer
* AdamW Optimizer
* Batch Normalization
* Dropout
* Early Stopping
* Learning Rate Scheduling
* Model Evaluation

### 🧠 Model Performance

🏆 **Validation Accuracy: ~82%**

The project also includes experiments comparing different Neural Network architectures and optimization strategies.

📁 Project Folder:

`Spaceship Titanic 2026`

---

## ✋ 3. CV Project - Rock Paper Scissors

A **Computer Vision and Deep Learning** project that uses a **Convolutional Neural Network (CNN)** to classify hand gestures into **Rock, Paper, or Scissors** in real time.

The project combines **Image Processing, Deep Learning, and OpenCV** to build an interactive Rock Paper Scissors game using a webcam.

### 🔧 Techniques & Concepts

* Image Acquisition
* Image Preprocessing
* RGB & HSV Color Spaces
* Image Resizing
* Median Filtering
* Data Augmentation
* Image Normalization
* Convolutional Neural Networks (CNN)
* Max Pooling
* Batch Normalization
* Dropout
* Softmax Classification
* Confusion Matrix
* Classification Report
* Real-Time Computer Vision
* OpenCV
* Webcam Integration

### 🧠 CNN Architecture

```text
Input Image (224 × 224 × 3)
        ↓
Data Augmentation
        ↓
Normalization
        ↓
Conv2D (32 Filters)
        ↓
MaxPooling
        ↓
Conv2D (64 Filters)
        ↓
MaxPooling
        ↓
Conv2D (128 Filters)
        ↓
MaxPooling
        ↓
Flatten
        ↓
Dense (128)
        ↓
Batch Normalization
        ↓
Dropout
        ↓
Softmax (3 Classes)
```

### 🎯 Classes

| Class       | Gesture  |
| ----------- | -------- |
| ✋ Paper     | Paper    |
| ✊ Rock      | Rock     |
| ✌️ Scissors | Scissors |

### 📊 Dataset

The project uses a **Rock Paper Scissors image dataset** containing **2,187 images** across three classes.

| Class     |    Images |
| --------- | --------: |
| Paper     |       711 |
| Rock      |       726 |
| Scissors  |       750 |
| **Total** | **2,187** |

The images are processed and resized to:

```text
224 × 224 × 3
```

### 🖼️ Image Processing Pipeline

```text
Image Acquisition
        ↓
RGB Conversion
        ↓
Image Resizing
        ↓
Image Preprocessing
        ↓
Data Augmentation
        ↓
Normalization
        ↓
CNN Classification
```

### 🎮 Real-Time Game

The trained CNN model is integrated with **OpenCV** to perform real-time hand gesture classification using a webcam.

The camera feed is divided into two **Regions of Interest (ROIs)**, one for each player.

The system:

1. Captures frames from the webcam.
2. Extracts the two player ROIs.
3. Preprocesses each ROI.
4. Sends the images to the trained CNN.
5. Predicts **Rock, Paper, or Scissors**.
6. Compares both predictions.
7. Determines and displays the winner in real time.

### 🧪 Model Evaluation

The model was evaluated using:

* Accuracy
* Validation Accuracy
* Confusion Matrix
* Classification Report
* Prediction Visualization

### 🛠️ Technologies

* Python
* TensorFlow
* Keras
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

📁 Project Folder:

`CV Project`

---

# 🛠️ Tech Stack

| Category            | Technologies                   |
| ------------------- | ------------------------------ |
| 💻 Programming      | Python                         |
| 📊 Data Analysis    | Pandas, NumPy                  |
| 📈 Visualization    | Matplotlib, Seaborn            |
| 🤖 Machine Learning | Scikit-learn                   |
| 🧠 Deep Learning    | TensorFlow, Keras              |
| 📓 Development      | Jupyter Notebook, Google Colab |
| 🗂️ Version Control | Git & GitHub                   |

---

# 📚 Learning Journey

This repository is continuously evolving as I learn more about:

```text
Data Analysis
     ↓
Data Preprocessing
     ↓
Exploratory Data Analysis
     ↓
Feature Engineering
     ↓
Machine Learning
     ↓
Deep Learning
     ↓
Model Optimization
     ↓
Real-World Projects 🚀
```
