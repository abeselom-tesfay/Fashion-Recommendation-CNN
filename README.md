# Fashion Product Recommendation System 👗🧥👕

This project is a deep learning-based content-based image recommendation system that suggests similar fashion items based on an input image. It leverages a pretrained CNN model (ResNet50) and uses K-Nearest Neighbors (KNN) for visual similarity search.

---

## 📌 Overview

The goal is to help users discover visually similar fashion products by uploading an image. This can be used in e-commerce platforms to improve user experience and product discovery.

---

## 🧠 Technologies Used

- **TensorFlow / Keras** – For feature extraction using ResNet50  
- **Scikit-learn** – KNN algorithm for nearest neighbor search  
- **Streamlit** – To build the web-based user interface  
- **Python** – Core development language  

---

## 🚀 How It Works

1. User uploads a fashion item image.  
2. The CNN model extracts visual features from the image.  
3. KNN compares these features with the dataset.  
4. Top 5 visually similar products are displayed as recommendations.

---

## 📂 Dataset

The dataset used in this project consists of fashion product images, sourced from Kaggle. It provides a diverse set of clothing items suitable for training a content-based recommendation system.

🔗 [Fashion Product Dataset on Kaggle](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small)

*Note: You must have a Kaggle account and accept the terms to access the dataset.*

---
