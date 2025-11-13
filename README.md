# 📚 Book Recommendation System

A content-based recommendation system built using Goodreads book metadata.  
The project computes similarity between books using **TF-IDF vectors** and **cosine similarity**, enabling users to get recommendations based on a selected title.

---

## 🔍 Overview
- Extracts book titles, authors, and descriptions  
- Cleans and preprocesses text (lowercasing, stopwords removal, tokenization)  
- Generates TF-IDF representations of book descriptions  
- Computes cosine similarity to find the closest matches  
- Returns the top recommended books for any selected title

This demonstrates how natural-language features can power simple but effective recommendation engines.

---

## 📊 Dataset
- Goodreads books metadata (title, author, description)  
- Cleaned and filtered for duplicates and missing values  
- Text prepared for TF-IDF vectorization

---

## 🧠 Method Highlights
- Text preprocessing & normalization  
- TF-IDF vector construction  
- Cosine similarity matrix  
- Recommendation function based on nearest neighbors  

---

## 🛠️ Technologies
**Python**, Pandas, scikit-learn, NumPy
