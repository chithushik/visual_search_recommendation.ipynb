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

## Screen shots

<img width="1696" height="702" alt="1" src="https://github.com/user-attachments/assets/e8ca9286-ec21-4578-8eaf-a8e856b04a34" />

<img width="1817" height="922" alt="2" src="https://github.com/user-attachments/assets/91f44545-3f01-443c-8aeb-d90003fc84ae" />

<img width="1610" height="791" alt="3" src="https://github.com/user-attachments/assets/bd8e2e3a-a1f5-4ebd-9d49-f9b18602018c" />

<img width="1656" height="847" alt="4" src="https://github.com/user-attachments/assets/a814d239-0944-4df8-850a-7d7c37dcbcc9" />



