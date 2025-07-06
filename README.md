# 📚 Book Recommendation System

This project is a machine learning-based **Book Recommendation System** that uses **Collaborative Filtering** and the **K-Nearest Neighbors (KNN)** algorithm to provide personalized book suggestions to users. By analyzing user interactions and similarities in behavior, the system predicts books that a user is likely to enjoy.

---

## 🧠 Features

-  Personalized book recommendations  
-  Collaborative filtering using KNN  
-  Minkowski distance-based similarity matching  
-  Data preprocessing and cleaning (missing values, filtering inactive users/books)  
-  Sparse matrix optimization for performance  
-  Performance evaluation: Accuracy, Precision, Recall, F1 Score  
-  Visualizations including rating distribution and confusion matrix  

---

## 🗂️ Dataset

- Over **1.1 million** user ratings  
- Metadata for **271,000+ books**  
- **278,000** user profiles  
- Demographics: Age, Location, and User ID  
- Rating values from 1–10  

---

## ⚙️ Methodology

1. **Data Preprocessing**
   - Removed users with <200 ratings and books with <50 ratings
   - Normalized ratings
   - Cleaned non-contributive data (e.g., image URLs)

2. **Matrix Construction**
   - Created a user-book interaction matrix using pivot tables
   - Converted to sparse matrix for memory and speed optimization

3. **Recommendation Engine**
   - Implemented using **KNN** (brute-force) with **Minkowski Distance**
   - Top-N recommendations for a given book based on user similarity

---

## 📈 Results

- Confusion matrix demonstrates strong classification with high true positives
- Recommendation examples show effective and context-aware book suggestions

---

## 🖼️ Visuals

- Rating distribution histogram  
- Confusion matrix for evaluation  
