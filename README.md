# 🛍️ Smart E-Commerce Visual Product Recommendation System

An AI-powered e-commerce backend feature that allows users to upload an image of an item (e.g., shoes or shirts) and receive visually similar product recommendations using deep learning embeddings.

## 🚀 Tech Stack
* **Language:** Python
* **Deep Learning:** PyTorch, torchvision (ResNet50)
* **Vector Search Engine:** FAISS (Facebook AI Similarity Search)
* **Backend Framework:** FastAPI & Uvicorn
* **Data Processing:** Pandas, NumPy, PIL

## ⚙️ How It Works
1. **Feature Extraction:** Passes uploaded images through a pre-trained **ResNet50** CNN to convert visual attributes into 2,048-dimensional feature vectors.
2. **Indexing:** Stores vectors inside a **FAISS** index for millisecond similarity retrieval using Euclidean distance ($L_2$).
3. **API Serving:** Uses **FastAPI** to accept multipart image uploads via POST requests and returns JSON payload recommendations.

## 📌 Dataset
Uses the [Fashion Product Images Dataset](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small) from Kaggle.
