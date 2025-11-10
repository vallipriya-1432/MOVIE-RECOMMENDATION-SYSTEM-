# 🎬 Movie Recommendation System

This project uses the **TMDB 5000 Movies Dataset** to build a content-based recommendation system.  
It suggests similar movies based on the text of their overviews and genres using TF-IDF and  similarity.

---

## 🧠 Objective
To help users find movies similar to the ones they already like, purely by analyzing movie content.

---

## 🧰 Tools Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Google Colab

---

## 📊 Key Steps
1. Data Cleaning – Extracted genres and combined them with overviews.  
2. Feature Engineering – Used TF-IDF to convert text into vectors.  
3. Similarity Computation – Applied cosine similarity to find close matches.  
4. Recommendation Function – Built a function that returns top similar movies.

---

## 💡 Example Output
**Input:** `Avatar`  
**Output:**  
- Guardians of the Galaxy  
- Star Trek  
- The Fifth Element  
- Jupiter Ascending  
- The Matrix  

---

## 🚀 Future Improvements
- Add user ratings and collaborative filtering.  
- Integrate with a web interface (Streamlit).  
- Include actor, director, and keyword metadata.

