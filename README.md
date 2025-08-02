## Fashion Product Recommendation System

This project is an advanced deep learning-based content-based image recommendation system that suggests visually similar fashion items based on an input image. It leverages a fine-tunable pretrained CNN model (ResNet50) for feature extraction and uses FAISS, a highly efficient similarity search library, to enable fast and scalable nearest neighbor retrieval over large datasets.

----

### Overview

The goal is to help users discover visually similar fashion products by uploading an image. This can be integrated into e-commerce platforms to enhance product discovery and improve user experience through fast and accurate visual recommendations.


----

### Technologies Used

- **TensorFlow / Keras** – For building and fine-tuning the ResNet50 feature extractor with L2-normalized embeddings  
- **FAISS (Facebook AI Similarity Search)** – High-performance nearest neighbor search for scalable similarity matching 
- **Streamlit** – To build the web-based interactive user interface for image upload and recommendations  
- **Python** – Core development language  

----

### How It Works

1. User uploads a fashion item image.  
2. The ResNet50-based CNN extracts normalized feature embeddings from the image.
3. FAISS performs a fast nearest neighbor search against a large precomputed database of product embeddings.
4. Top 5 visually similar products are displayed as recommendations.The system returns the top 5 visually similar fashion products as recommendations, displayed alongside the uploaded image.

----

### Dataset

The dataset used in this project consists of fashion product images, sourced from Kaggle. It provides a diverse set of clothing items suitable for training a content-based recommendation system.

 [Fashion Product Dataset on Kaggle](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small)

----
