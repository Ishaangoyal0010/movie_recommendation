# 🎥 Movie Recommendation System (Content-Based)

A **Movie Recommendation System** built using **Python** that suggests movies similar to the one you search for — just like Google or Netflix!  
It uses **content-based filtering** powered by **TF-IDF** and **cosine similarity** to find movies with similar descriptions, genres, and features.

---

## 🚀 Features
- 🔎 Search any movie and get a list of similar movies.  
- 🧠 Content-based filtering using movie metadata (overview, genres, cast, etc.).  
- ⚡ Fast similarity computation using cosine similarity.  
- 📂 Works with the TMDB 5000 Movies dataset or any custom dataset.  
- 🌐 Easily extendable to a web app (e.g., Streamlit).

---

## 🧠 How It Works
1. **Data Preprocessing:** Cleans and merges features like title, genres, cast, crew, and overview.  
2. **Feature Extraction:** Converts movie data into numerical vectors using **TF-IDF / CountVectorizer**.  
3. **Similarity Computation:** Calculates **cosine similarity** between movie vectors.  
4. **Recommendation:** Returns top N movies with the highest similarity to the searched movie.

---
