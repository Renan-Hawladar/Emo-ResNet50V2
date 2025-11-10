# Emo-Res50V2: Emotion Recognition System

This repository contains two main Jupyter notebooks that work together to build and test an emotion recognition system using deep learning and computer vision for mental health detection.

## Project Structure

- `EmoResnet50v2.ipynb` – Model development notebook. This trains a deep learning model (ResNet50v2) for recognizing emotions from images or video frames.

---

## Features

- Custom emotion classification using deep learning.
- Real-time or batch video frame testing.
- Transfer learning with pre-trained ResNet50v2.
- Visualizations for model performance and predictions.

---

## Getting Started

### Installation

Before running the notebooks, install the required dependencies. You can use pip:

```bash
pip install numpy pandas seaborn opencv-python tensorflow matplotlib scikit-learn visualkeras
```

## How to Use

### 1. Train the Model

Open and run EmoResnet50v2.ipynb. This will:

- Load and preprocess data.
- Train a deep learning model for emotion recognition.
- Save the trained model for later use.


## 🧠 Model

The model uses ResNet50v2 as the base with added layers for emotion classification. Transfer learning ensures faster convergence and better accuracy on small datasets. And a survey to generate mental health score for mental health condition 
