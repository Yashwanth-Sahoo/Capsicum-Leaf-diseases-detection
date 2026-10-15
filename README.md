# 🌿 Capsicum Leaf Disease Detection Using Deep Learning

A deep learning project that classifies capsicum (bell pepper) leaf images into healthy and disease-related categories using **TensorFlow, MobileNetV2, and transfer learning**.

## 📌 Overview

Plant diseases can affect crop health and agricultural productivity. This project uses a convolutional neural network based on MobileNetV2 to identify different conditions in capsicum leaves from images.

The model is trained using a labeled leaf image dataset and evaluated using standard classification metrics. It also supports prediction on an individual leaf image, displaying the predicted class and confidence score.

## ✨ Features

- Six-class capsicum leaf classification
- Transfer learning using pretrained MobileNetV2
- Image augmentation for training
- Fine-tuning of the pretrained model
- Model evaluation using accuracy, precision, recall, and F1-score
- Confusion matrix and classification report
- Prediction and confidence scores for individual images

## 🦠 Supported Classes

1. Bacterial Spot
2. Cercospora Leaf Spot
3. Healthy
4. Leaf Curl
5. Nutrition Deficiency
6. Powdery Mildew

## 🛠️ Tech Stack

- Python
- TensorFlow and Keras
- MobileNetV2
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## ⚙️ Methodology

1. Load and prepare the labeled dataset.
2. Resize images to 224 × 224 pixels.
3. Apply data augmentation, including random flipping, rotation, zoom, and contrast adjustments.
4. Use pretrained MobileNetV2 as the feature extraction backbone.
5. Train a six-class classification head.
6. Fine-tune selected MobileNetV2 layers.
7. Evaluate the model and predict classes for new images.

## 📊 Results

The notebook's final fine-tuned model evaluation reports:

- **Test accuracy:** 99.78%
- **Weighted precision:** 99.79%
- **Weighted recall:** 99.78%
- **Weighted F1-score:** 99.78%

These results are specific to the dataset and evaluation procedure used in the notebook and should be independently validated on new images.

## 🚀 Getting Started

1. Clone this repository.
2. Open `leaf_capsicum_.ipynb` in Google Colab or Jupyter Notebook.
3. Install the required Python libraries.
4. Download the compatible Pepper Bell Leaf Disease dataset and configure the dataset path in the notebook.
5. Run the notebook cells in order to train, evaluate, and test the model.

## 📁 Repository Structure

```text
Capsicum-Leaf-diseases-detection/
├── leaf_capsicum_.ipynb
├── README.md
└── .gitignore
```

## 🔮 Future Improvements

- Build a web application for image-based predictions.
- Deploy the trained model for practical agricultural use.

## 👨‍💻 Author

Developed as a deep learning project focused on agricultural image classification.

