# 📚 Book Recommendation System

A content-based recommendation system that suggests similar books using **Bag-of-Words (CountVectorizer)** and **cosine similarity**.  
The model compares book descriptions and identifies titles with the closest textual content.

---

## 🔍 Overview
- Preprocesses book titles, authors, and descriptions  
- Converts text into numerical vectors using **CountVectorizer (Bag-of-Words)**  
- Computes **cosine similarity** between all books  
- Returns the top nearest-neighbour recommendations for any selected title

This light-weight, training-free approach provides fast and explainable recommendations.

---

## 📊 Dataset
- Goodreads metadata (title, author, description)  
- Cleaned and filtered for validity  
- Text processed for vectorization

---

## 🧠 Method Highlights
- Lowercasing, punctuation removal, stopwords handling  
- Bag-of-Words vectorization with CountVectorizer  
- Cosine similarity matrix  
- Top-N nearest neighbor retrieval  

---

## 🛠️ Technologies
**Python**, Pandas, scikit-learn, NumPy

