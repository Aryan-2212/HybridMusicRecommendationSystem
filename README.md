# 🎵 Hybrid Music Recommendation System  

A hybrid music recommendation engine that combines **Content-Based Filtering** (cosine similarity on audio features) and **Collaborative Filtering** (SVD) to provide personalized song recommendations.  

---

## 📌 Features  
- Content-Based Filtering using track-level audio features (danceability, energy, valence, tempo, etc.).  
- Collaborative Filtering with **Truncated SVD** to capture user-song interaction patterns.  
- Hybrid approach blending both methods for improved recommendation accuracy.  
- Clean preprocessing pipeline with duplicate removal and normalized features.  
- Easily extendable to include additional features like genre and artist similarity.  

---

## 📂 Dataset  
- Dataset: Custom curated dataset of **5,000+ unique songs** (based on Spotify Tracks DB).  
- Preprocessed to remove duplicates and standardize feature scales.  

---

## ⚙️ Tech Stack  
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit-Learn  
- **Techniques:** Content-Based Filtering, Collaborative Filtering (SVD), Cosine Similarity  

---

## 🚀 Usage  

### 1️⃣ Clone Repository  
```bash
git clone https://github.com/Aryan-2212/hybrid-music-recommender.git
cd hybrid-music-recommender
